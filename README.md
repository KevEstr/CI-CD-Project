[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=KevEstr_CI-CD-Project&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=KevEstr_CI-CD-Project) [![Bugs](https://sonarcloud.io/api/project_badges/measure?project=KevEstr_CI-CD-Project&metric=bugs)](https://sonarcloud.io/summary/new_code?id=KevEstr_CI-CD-Project)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=KevEstr_CI-CD-Project&metric=code_smells)](https://sonarcloud.io/summary/new_code?id=KevEstr_CI-CD-Project)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=KevEstr_CI-CD-Project&metric=coverage)](https://sonarcloud.io/summary/new_code?id=KevEstr_CI-CD-Project)
[![Duplicated Lines (%)](https://sonarcloud.io/api/project_badges/measure?project=KevEstr_CI-CD-Project&metric=duplicated_lines_density)](https://sonarcloud.io/summary/new_code?id=KevEstr_CI-CD-Project)
[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=KevEstr_CI-CD-Project&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=KevEstr_CI-CD-Project)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=KevEstr_CI-CD-Project&metric=reliability_rating)](https://sonarcloud.io/summary/new_code?id=KevEstr_CI-CD-Project)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=KevEstr_CI-CD-Project&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=KevEstr_CI-CD-Project)
[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=KevEstr_CI-CD-Project&metric=sqale_index)](https://sonarcloud.io/summary/new_code?id=KevEstr_CI-CD-Project)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=KevEstr_CI-CD-Project&metric=sqale_rating)](https://sonarcloud.io/summary/new_code?id=KevEstr_CI-CD-Project)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=KevEstr_CI-CD-Project&metric=vulnerabilities)](https://sonarcloud.io/summary/new_code?id=KevEstr_CI-CD-Project)

Implementation of a Simple App with the next operations: 
* Get random nations 
* Get random currencies 
* Get random Aircraft 
* Get application version 
* health check 
Including integration with GitHub Actions, Sonarqube (SonarCloud), Coveralls and 
Snyk 
### Folders Structure 
In the folder `src` is located the main code of the app 
In the folder `test` is located the unit tests 
### How to install it 
Execute: 
```shell 
$ mvnw spring-boot:run 
``` 
to download the node dependencies 
### How to test it 
Execute: 
```shell 
$ mvnw clean install 
``` 
### How to get coverage test 
Execute: 
```shell 
$ mvwn -B package -DskipTests --file pom.xml
