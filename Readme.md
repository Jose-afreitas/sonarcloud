# comando para rodar o sonar
sonar-scanner \
-Dsonar.projectKey=go-project \
-Dsonar.sources=. \
-Dsonar.host.url=http://localhost:9000 \
-Dsonar.login=sqp_5feda9a59bff56f91e87bb5e12fccedbdc18cdb2


 go test -coverprofile=coverage.out

 sonar-scanner