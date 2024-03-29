# What do I want? - Defining requirements using BDD
## Understanding the business goals: Feature Injection and related techniques
```
  - High-level requirements-analysis techniques
  - Using Feature Injection to identify business goals and supporting features
  - Visualizing high-level requirements with Impact Mapping
  - Identifying stakeholders and their needs
```
- Feature Injection: A high-level requirements-analysis technique, takes BDD beyond scenarios and stories and can help you discover what features you really need to build
- Impact Mapping: A visual technique for identifying the business goals behind a project and the features that will help you achieve them.
- Purpose Alignment Model: A technique for identifying stakeholders and their needs.
### Introducing Flying High Airlines
### Feature Injection
![Feature Injection](/resoucrce/FeatureInjection.png)
- Hunt the value
- Inject the features
- Spot the examples
- Putting it all together
![putting it all together](/resoucrce/PuttingAllTogether.png)
### What do you want to achieve? Start with a vision
- The vision statement
- Using vision statement templates
### How will it benefit the business? - Indentifying business goals
- Writing good business goals
- Show me the money - business goals and revenue
- Popping the "why stack": digging out the business goals
### Impact Mapping: a visual approach 
![Impact Mapping](/resoucrce/ImpactMapping.png)
### Who will benefit? Identify stakeholders and their needs
### What do you need to build? Identify capabilities
![Impact Mapping2](/resoucrce/ImpactMapping2.png)
### What features will provide the most ROI?
- Differentiating features
- Parity features
- Partner features
- Minimun impact



## Defining and illustrating features
```
  - Describing and organizing features and user stories
  - Illustrating features with examples
  - Using these examples to build up a common understanding of the requirements
```
### What is a feature?
- Features deliver capabilities
![Feature](/resoucrce/FeaturesDeliverCapabilities.png)
- Features can be broken down into more manageable chunks
- A feature can be described by one or more user stories
- A feature is not a user story
- Epics are really big user stories
- Not everything fits into a hierarchy
### Illustrating features with examples
### Real Option: Don't make commitments before you have to
- Options have value
- Options expire
- Never commit early unless you know why
### Deliverate Discovery
### From Examples to working software: The Bigger Picture



## From examples to executable specifications
```
  - Turning concrete examples into executable scenarios
  - Writing basic scenarios
  - Using data tables to drive scenarios
  - Writing more advanced scenarios using more Gherkin keywords
  - Organizing scenarios in feature files
```
![From Examples to executable specifications](/resoucrce/ExamplesToExecutableSpecifications.png)
### Truning examples into executable scenarios
### Writing excutable scenarios
- A feature file has a title and a description
- Describing scenarios
- The Given-When-Then structure
- Using the And and But keywords
- Comments
### Using tables in scenarios
- Using tables in individual steps
- Using tables of examples
![TableScenario](/resoucrce/TableScenarios.png)
### Expressive scenarios: Patterns and anti-patterns
- Writing expressive Given steps
- Writing expressive When steps
- Writing expressive Then steps
- Providing context with Background
- Avoid dependencies between scenarios
### Organizing scenarios using feature files and tags
- The scenarios go in a feature file
![ScenariosInFeatureFile](/resoucrce/ScenariosInFeatureFile.png)
- A feature file can contain multiple scenarios
- Organizing feature files
- Annotating your scenarios with tags



## Automation the scenarios
```
  - The basic principles of automating scenarios steps
  - The responsibilities of a step definition method
  - Implementing step definitions in Java Using JBehave and Cuucmber-JVM
  - Implementing step definitions in Python using Behave
  - Implementing step definitions in .NET using SpecFlow
  - Implementing step definitions in JavaScript using Cucumber.js
```
![Automation the scenarios](/resoucrce/AutomateExamplesUsingBDDTools.png)
### Introduction to automating scenarios
- Step definitions interpret the steps
![StepDefinitions](/resoucrce/ScenarioToStepDefinition.png)
![AutomationSuite](/resoucrce/WellDesignedAutomationSuite.png)
![AutomationSuite2](/resoucrce/WellDesignApplication.png)
- Keep your step definitions simple
### Implementing step definitions: General principles
- Installing the BDD tools
- Implementing step definitions
- Passing parameters to step definitions
- Maintaining state between steps
- Using table data from step definitions
- Implementing example-based scenarios
- Understanding scenario outcomes
### Implementing BDD more effectively with Thucydides(Serenity)
### Automating scenarios in Java with JBehave
- Installing and setting up JBehave
- JBehave step definitions
- Sharing data between steps
- Using tables in step definitions
- Step definition for tables of examples
- Pattern variants
- Fallures and errors in th scenarios outcomes
### Automating scenarios in Java with Cucumber-JVM
- Cucumber-JVM project setup and structure
- Cucumber-JVM step definitions
- Pattern variants
- Using tables in step definitions
- Step definitions for tables of examples
- Sharing data between steps
- Pending steps and step outcomes
### Automating scenarios in Python with Behave
### Automating scenarios in .NET with SpecFlow
### Automating scenarios in JavaScript with Cucumber.js