# Accelerator Log

## Options
```json
{
  "applicationName" : "Forecast",
  "bsGitBranch" : "main",
  "bsGitRepository" : "github.com?owner=odedia&repo=Weather+Forecast",
  "projectName" : "weatherforecast-steeltoe"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(GeneratorValidationTransform, UniquePath)
┃ ┏ ┏ engine.transformations[0].validated (Combo)
┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ engine.transformations[0].validated.delegate (Chain)
┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[0].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Exclude, ReplaceText, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[0].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug Controllers/WeatherForecastController.cs matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug Program.cs matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug Properties/launchSettings.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug Sample.csproj matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug Sample.sln matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug StaticFiles/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug WeatherForecast.cs matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug app.config matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.Development.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┗ Debug global.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[0].delegate.transformations[1] (Exclude)
┃ ┃ ┃ ┃ ┃ ┃  Info Will exclude [README.md, config/**, catalog/**, Tiltfile]
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug Controllers/WeatherForecastController.cs didn't match [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug Program.cs didn't match [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug Properties/launchSettings.json didn't match [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Sample.csproj didn't match [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug Sample.sln didn't match [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug StaticFiles/index.html didn't match [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug WeatherForecast.cs didn't match [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug app.config didn't match [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.Development.json didn't match [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.json didn't match [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug global.json didn't match [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[0].delegate.transformations[2] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [Sample->Forecast]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[0].delegate.transformations[3] (RewritePath)
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'Sample.csproj' matched 'Sample(.*)' with groups {g0=Sample.csproj, g1=.csproj} and was rewritten to 'Forecast.csproj'
┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'Sample.sln' matched 'Sample(.*)' with groups {g0=Sample.sln, g1=.sln} and was rewritten to 'Forecast.sln'
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText, Combo)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [README.md, config/**, catalog/**, Tiltfile]
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Controllers/WeatherForecastController.cs didn't match [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Program.cs didn't match [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Properties/launchSettings.json didn't match [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug Sample.csproj didn't match [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Sample.sln didn't match [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug StaticFiles/index.html didn't match [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug WeatherForecast.cs didn't match [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug app.config didn't match [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.Development.json didn't match [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.json didn't match [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┗ Debug global.json didn't match [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [Sample->Forecast, sample-app->weatherforecast-stee...(truncated)]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate.transformations[2] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate.transformations[2].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate.transformations[2].delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(InvokeFragment, Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate.transformations[2].delegate.transformations[0].sources[0] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate.transformations[2].delegate.transformations[0].sources[0].validated (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#bsGitRepository != null) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Let
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate.transformations[2].delegate.transformations[0].sources[0].validated.delegate (Let)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Adding symbol repoUrl with value 'https://github.com?owner=odedia&repo=Weather+Forecast'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate.transformations[2].delegate.transformations[0].sources[0].validated.delegate.in (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(OpenRewriteRecipe, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ╺ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate.transformations[2].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0] (OpenRewriteRecipe)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate.transformations[2].delegate.transformations[0].sources[0].validated.delegate.in.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗ ┗  Info Will replace regex '(?<beforeBranch>[\s\S]+)(?<branch>branch: [\S]+)(?<rest>[\S\s]*)' with '${beforeBranch}branc...(truncated)'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate.transformations[2].delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate.transformations[2].delegate.transformations[0].sources[1].delegate (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate.transformations[2].delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'config/workload.yaml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'Tiltfile', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'catalog/catalog-info.yaml', will use the one appearing first 
┃ ┃ ┃ ┗ ┗ ┗ ┗ Debug Multiple representations for path 'README.md', will use the one appearing first 
┃ ┗ ┗ ╺ engine.transformations[0].validated.delegate.transformations[1] (UniquePath)
┗ ╺ engine.transformations[1] (UniquePath)
```
