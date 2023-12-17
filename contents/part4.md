# Taking BDD Further

## Living Documentation: Reporting and project management
```
    - What we mean by living documentation
    - Keeping track of project progress using feature readiness and feature coverage
    - Organizing living documentation
    - Technical living documentation
```
![Living Document](/resoucrce/LivingDocument.png)
### Living documentation: A High-Level View
![Living Document](/resoucrce/LivingDocumentation.png)
### Are we there yet? Reporting on feature readiness and feature coverage
- Feature readiness: what feature are ready to deliver
![Feature Readiness](/resoucrce/FeatureReadiness.png)
- Feature coverage: what requirements are covered
![Feature Coverage](/resoucrce/FeatureCoverage.png)
### Integrating a digital product backlog
![Digital Product Backlog](/resoucrce/ProductBacklog.png)
### Organizing the living documentation
- Organizing the living documentation by high-level requirements
- Organizing the living documentation using tags
- Living documentation for release reporting
### Providing more free-form documentation
### Technical living documentation
- Unit tests as living documentation
- Living documentation for legacy applications



## BDD in the build process
```
    - Executable specifications and the automated build process
    - The role of BDD in CI/CD
    - Using a CI server to publish living documentation
    - Using a CI server to speed up automated acceptance tests
```
### Executable specifications should be part of an automated build
- Each specification should be self-sufficient
- Executable specifications should be stored under version control
- You should be able to run the executable specifications from the command line
### Continuous integration speeds up the feeedback cycle
### Continuous delivery: Any build is a potential release
![Simple Pipeline](/resoucrce/SimplePipeline.png)
![Jenkins Pipeline](/resoucrce/JenkinsPipeline.png)
### Coninuous Integration used to deploy living documentation
- Publishing living documentation on the build server
![Jenkins Thucydide Report](/resoucrce/JenkinsThucydideReport.png)
- Publishing living documentation to a dedicated server
### Faster automated acceptance criteria
- Running parallel tests within automated builds
- Running parallel tests on multiple machines
- Running parallel web tests using Selenium Grid