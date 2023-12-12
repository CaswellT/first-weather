# Accelerator Log

## Options
```json
{
  "projectName" : "first-csharp-weatherforecast",
  "applicationName" : "First-Weather"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(GeneratorValidationTransform, UniquePath)
┃ ┏ ┏ engine.transformations[0].validated (Combo)
┃ ┃ ┃  Info Combo running as Let
┃ ┃ ┃ engine.transformations[0].validated.delegate (Let)
┃ ┃ ┃ Debug Adding symbol compilerSafeAppName with value 'First_Weather'
┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo, Provenance)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[0].sources[0].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Exclude, ReplaceText, RewritePath)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[0].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Program.cs matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Sample.csproj matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Sample.sln matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug WeatherForecast.cs matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.Development.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug global.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Controllers/WeatherForecastController.cs matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Properties/launchSettings.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug StaticFiles/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[0].delegate.transformations[1] (Exclude)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will exclude [README.md, config/**, catalog/**, Tiltfile]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Program.cs didn't match [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Sample.csproj didn't match [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Sample.sln didn't match [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug WeatherForecast.cs didn't match [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.Development.json didn't match [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.json didn't match [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug global.json didn't match [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Controllers/WeatherForecastController.cs didn't match [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Properties/launchSettings.json didn't match [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug StaticFiles/index.html didn't match [README.md, config/**, catalog/**, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug config/workload.yaml matched [README.md, config/**, catalog/**, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[0].delegate.transformations[2] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [Sample->First-Weather]
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[0].delegate.transformations[3] (RewritePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'Sample.csproj' matched 'Sample(.*)' with groups {g0=Sample.csproj, g1=.csproj} and was rewritten to 'First-Weather.csproj'
┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'Sample.sln' matched 'Sample(.*)' with groups {g0=Sample.sln, g1=.sln} and was rewritten to 'First-Weather.sln'
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[0].sources[1].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText, Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[1].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [README.md, config/*.yaml, catalog/*.yaml, Tiltfile]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [README.md, config/*.yaml, catalog/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [README.md, config/*.yaml, catalog/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [README.md, config/*.yaml, catalog/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Program.cs didn't match [README.md, config/*.yaml, catalog/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [README.md, config/*.yaml, catalog/*.yaml, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Sample.csproj didn't match [README.md, config/*.yaml, catalog/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Sample.sln didn't match [README.md, config/*.yaml, catalog/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [README.md, config/*.yaml, catalog/*.yaml, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug WeatherForecast.cs didn't match [README.md, config/*.yaml, catalog/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.Development.json didn't match [README.md, config/*.yaml, catalog/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.json didn't match [README.md, config/*.yaml, catalog/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug global.json didn't match [README.md, config/*.yaml, catalog/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Controllers/WeatherForecastController.cs didn't match [README.md, config/*.yaml, catalog/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Properties/launchSettings.json didn't match [README.md, config/*.yaml, catalog/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug StaticFiles/index.html didn't match [README.md, config/*.yaml, catalog/*.yaml, Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [README.md, config/*.yaml, catalog/*.yaml, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug config/workload.yaml matched [README.md, config/*.yaml, catalog/*.yaml, Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[1].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [Sample->First-Weather, sample-app->first-csharp-weather...(truncated)]
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[1].delegate.transformations[2] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[0].sources[1].delegate.transformations[2].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[1].delegate.transformations[2].delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(InvokeFragment, Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[1].delegate.transformations[2].delegate.transformations[0].sources[0] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[1].delegate.transformations[2].delegate.transformations[0].sources[0].validated (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#bsGitRepository != null) evaluated to false
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ null ()
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[1].delegate.transformations[2].delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[0].sources[1].delegate.transformations[2].delegate.transformations[0].sources[1].delegate (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┗ ┗ ╺ engine.transformations[0].validated.delegate.in.transformations[0].sources[1].delegate.transformations[2].delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[0].sources[2].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[2].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/*.cs]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Program.cs matched [**/*.cs] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Sample.csproj didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Sample.sln didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug WeatherForecast.cs matched [**/*.cs] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.Development.json didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug appsettings.json didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug global.json didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Controllers/WeatherForecastController.cs matched [**/*.cs] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Properties/launchSettings.json didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug StaticFiles/index.html didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug config/workload.yaml didn't match [**/*.cs] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].sources[2].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗ ┗  Info Will replace [Sample->First_Weather]
┃ ┃ ┃ ┃ ┗ ╺ engine.transformations[0].validated.delegate.in.transformations[0].sources[3] (Provenance)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'Controllers/WeatherForecastController.cs', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'WeatherForecast.cs', will use the one appearing last 
┃ ┗ ┗ ┗ ┗ Debug Multiple representations for path 'Program.cs', will use the one appearing last 
┗ ╺ engine.transformations[1] (UniquePath)
```
