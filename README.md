# Socle-back-end-java-generator
## generator of back-end socle respecting DDD

### How to use:
- on windows -> double click on -> windows-run.bat
- choose the name of your project respecting variable closes nominations
- a (.zip) file will be generated in the same folder of the (.bat)

### more infos: 
- it generates a spring-boot project who respects hexagonal architecture with (domain, infrastructure, application and presentation) layers.
- you will find some example to call resources.
- a controllerAdvice is implemented with a good handler format,
- a H2 simple DB configuration is on the application.yml to use with hibernate and also you can modify everything on the configuration,
- the project run under port 8081 configuration on application.yml
- to run the project go to infrastructure.spring.ProjectApplication.java and execute the main class
