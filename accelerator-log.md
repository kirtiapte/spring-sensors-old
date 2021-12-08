# Accelerator Log

## Options
```json
{
  "gitBranch" : "main",
  "gitUrl" : "https://github.com/kirtiapte/spring-sensors.git",
  "projectName" : "spring-sensors-rabbit"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(Combo, UniquePath)
┃ ┏ engine.transformations[0] (Combo)
┃ ┃  Info Combo running as Chain(Merge(merge), UniquePath(UseLast))
┃ ┃ engine.transformations[0].merge (Chain)
┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┏ engine.transformations[0].merge.transformations[0] (Merge)
┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo)
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Exclude)
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[0].<combo> (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Include, Exclude)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[0].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug README.MD matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug mvnw matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/tanzu/demo/SensorData.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/tanzu/demo/SensorRepository.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/tanzu/demo/SensorsApplication.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/tanzu/demo/SensorsDataSink.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/tanzu/demo/SensorsUiController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/tanzu.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/tanzu/demo/SensorsApplicationTests.java matched [**] -> included
┃ ┃ ┃ ┃ ┗ Debug tap/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[0].<combo>.transformations[1] (Exclude)
┃ ┃ ┃ ┃ ┃  Info Will exclude [tap/workload.yaml, src/main/resources/application.yaml]
┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [tap/workload.yaml, src/main/resources/application.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java didn't match [tap/workload.yaml, src/main/resources/application.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [tap/workload.yaml, src/main/resources/application.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [tap/workload.yaml, src/main/resources/application.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug README.MD didn't match [tap/workload.yaml, src/main/resources/application.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [tap/workload.yaml, src/main/resources/application.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [tap/workload.yaml, src/main/resources/application.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [tap/workload.yaml, src/main/resources/application.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/tanzu/demo/SensorData.java didn't match [tap/workload.yaml, src/main/resources/application.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/tanzu/demo/SensorRepository.java didn't match [tap/workload.yaml, src/main/resources/application.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/tanzu/demo/SensorsApplication.java didn't match [tap/workload.yaml, src/main/resources/application.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/tanzu/demo/SensorsDataSink.java didn't match [tap/workload.yaml, src/main/resources/application.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/tanzu/demo/SensorsUiController.java didn't match [tap/workload.yaml, src/main/resources/application.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yaml matched [tap/workload.yaml, src/main/resources/application.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/tanzu.css didn't match [tap/workload.yaml, src/main/resources/application.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html didn't match [tap/workload.yaml, src/main/resources/application.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/tanzu/demo/SensorsApplicationTests.java didn't match [tap/workload.yaml, src/main/resources/application.yaml] -> included
┃ ┃ ┃ ┗ ┗ Debug tap/workload.yaml matched [tap/workload.yaml, src/main/resources/application.yaml] -> excluded
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[1].<combo> (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [tap/workload.yaml]
┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug README.MD didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/tanzu/demo/SensorData.java didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/tanzu/demo/SensorRepository.java didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/tanzu/demo/SensorsApplication.java didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/tanzu/demo/SensorsDataSink.java didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/tanzu/demo/SensorsUiController.java didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yaml didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/tanzu.css didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/tanzu/demo/SensorsApplicationTests.java didn't match [tap/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┗ Debug tap/workload.yaml matched [tap/workload.yaml] -> included
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [https://github.com/tanzu-end-to-end/spring-sensors.git->https://github.com/k...(truncated), main->main]
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[2].<combo> (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[2].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [src/main/resources/application.yaml]
┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [src/main/resources/application.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/MavenWrapperDownloader.java didn't match [src/main/resources/application.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.jar didn't match [src/main/resources/application.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [src/main/resources/application.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug README.MD didn't match [src/main/resources/application.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [src/main/resources/application.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [src/main/resources/application.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [src/main/resources/application.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/tanzu/demo/SensorData.java didn't match [src/main/resources/application.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/tanzu/demo/SensorRepository.java didn't match [src/main/resources/application.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/tanzu/demo/SensorsApplication.java didn't match [src/main/resources/application.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/tanzu/demo/SensorsDataSink.java didn't match [src/main/resources/application.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/java/org/tanzu/demo/SensorsUiController.java didn't match [src/main/resources/application.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yaml matched [src/main/resources/application.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/tanzu.css didn't match [src/main/resources/application.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/index.html didn't match [src/main/resources/application.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug src/test/java/org/tanzu/demo/SensorsApplicationTests.java didn't match [src/main/resources/application.yaml] -> excluded
┃ ┃ ┃ ┃ ┗ Debug tap/workload.yaml didn't match [src/main/resources/application.yaml] -> excluded
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[2].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[2].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┗ ┗ ┗ ┗  Info Will replace [Sensor Database->Tanzu Sensor Databas...(truncated)]
┃ ┗ ╺ engine.transformations[0].merge.transformations[1] (UniquePath)
┗ ╺ engine.transformations[1] (UniquePath)
```
