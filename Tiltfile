allow_k8s_contexts('tap14')
allow_k8s_contexts('tap-iterate')
SOURCE_IMAGE = os.getenv("SOURCE_IMAGE", default='your-registry.io/project/steeltoe-weatherforecast-source') # update registry
LOCAL_PATH = os.getenv("LOCAL_PATH", default='.')
NAMESPACE = os.getenv("NAMESPACE", default='default')
OUTPUT_TO_NULL_COMMAND = os.getenv("OUTPUT_TO_NULL_COMMAND", default=' > /dev/null ')
NAME = "weatherforecast-steeltoe"

k8s_custom_deploy(
  NAME,
  apply_cmd="tanzu apps workload apply -f config/workload.yaml --debug --live-update" +
            " --local-path " + LOCAL_PATH +
            " --source-image " + SOURCE_IMAGE +
            " --namespace " + NAMESPACE +
            " --yes " +
            OUTPUT_TO_NULL_COMMAND +
            " && kubectl get workload " + NAME + " --namespace " + NAMESPACE + " -o yaml",
  delete_cmd="tanzu apps workload delete " + NAME + " --namespace " + NAMESPACE + " --yes",
  deps=['./bin'],
  container_selector='workload',
  live_update=[
    sync('./bin/Debug/net6.0', '/workspace')
  ]
)

k8s_resource(NAME, port_forwards=["8080:8080"],
            extra_pod_selectors=[{'carto.run/workload-name': 'weatherforecast-steeltoe', 'app.kubernetes.io/component': 'run'}])

allow_k8s_contexts('<context>') # update the context
