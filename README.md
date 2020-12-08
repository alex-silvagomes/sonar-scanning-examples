### License

Copyright 2016-2017 SonarSource.

Licensed under the [GNU Lesser General Public License, Version 3.0](http://www.gnu.org/licenses/lgpl.txt)

## Requirements
Copy:
https://docs.sonarqube.org/latest/analysis/scan/sonarscanner/

## SonarQube Server (Docker)
Copy:
https://docs.sonarqube.org/latest/setup/get-started-2-minutes/#

1. Start the server by running:

Commandline:
$ docker run -d --name sonarqube -e SONAR_ES_BOOTSTRAP_CHECKS_DISABLE=true -p 9000:9000 sonarqube:latest

2. Log in to http://localhost:9000 with System Administrator credentials (login=admin, password=admin).


3. Install sonarscanner
Copy:
https://docs.sonarqube.org/latest/analysis/scan/sonarscanner/

4. Execute sonar-scanner

Baixe e configure o sonar-scanner libs, configure as variaveis de ambiente e execute o comando abaixo na raiz do projeto 

$ .\bin\sonar-scanner.bat