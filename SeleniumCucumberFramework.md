
## 1. Setup & Configuration
- JDK
- Eclipse
- Cucumber plugin&dependencies
- Set Environment Variables
  - JAVA_HOME
  - MAVEN_HOME
  - M2_HOME

## 2. Creating Maven Project and Updating POM.xml with below dependencies
- Cucumber-Java
- Cucumber-JUnit
- Cucumber-core
- Cucumber-html
- Cucumber-jvm-deps
- Cucumber-reporting
- Cucumber-compiler
- cobertura-code-coverage
- Hamcrest-core
- Gherkin
- Selenium-Java
- JUnit
- Log4j

## 3. Creating Foler Stucture

```
   Project Name
    |src/test/java
      |pageObjects(Package)
        |AddCustomerPage.java
        |LoginPage.java
        |SearchCustomerPage.java
      |stepDefinitions(Package)
        |steps.java
      |testRunner(Package)
        |TestRunner.java
      |utilities(Package)
        |ReadConfig.java
        |BaseClass.java
        |BrowserFactory.java
        |ExcelUtils.java
        |Helper.java
        |Log.java
    |Features(Folder)
      |Login.feature
      |Customer.feature
      |SearchCustomer.feature
    |log4j.properties -> Add this file in "steps.java" under "stepDefinitions" package
    |log(Folder)
    |config.properties -> Add this file in "steps.java" under "stepDefinitions" package
    |Drivers(Folder)
      |chromedriver.exe
      |geckodriver.exe
      |IEDriverServer.exe
    |pom.xml
    |Target(Report)
```

## 4. Copy Drivers to "Drivers" Folder

## 5. Automating (Login) Test Cases
- Create **Login.feature** file under **Features** folder
- Create Page Object Model(POM) class **LoginPage.java** under **pageObjects** package
- Create **steps.java** file under **stepDefinitions** package to implement required steps
- Create **TestRunner.java** file under **testRunner** package to run the tests

## 6. Automating Add New Customer Test Cases
- Create a **Customer.feature** file under **Features** folder
- Create Page Object Model(POM) class **AddCustomerPage.java** under **pageObjects** package
- Create **steps.java** file under **stepDefinitions** package to implement required steps
- Create **TestRunner.java** file under **testRunner** package to run the tests

## 7. Automating Search Customer by Email&Name Test Cases
- Create a **SearchCustomer.feature** file under **Features** folder
- Create Page Object Model(POM) class **SearchCustomerPage.java** under **pageObjects** package
- Create **steps.java** file under **stepDefinitions** package to implement required steps
- Create **TestRunner.java** file under **testRunner** package to run the tests

## 8. Adding Logs using Log4j API
- Create **log4j.properties** file in project root folder
- Add new method **setup()** with **@Before** annotation in **steps.java** under **stepDefinitions** package
- Write setup code inside **setup()** method to load **log4j.properties** file

## 9. Running Tests on different browsers
- Create **config.properties** file in project root folder which contains common properties(like browser, url, username, password, etc) for all the tests
- Load **config.properties** file and use common properties in **setup()** method in **steps.java** under **stepDefinitions** package
- Write setup code inside **setup()** method to load **config.properties** file
## 10. Running Specific Scenarios by Adding Tags

## 11. Run Tests using Maven POM.xml, Command Line and run.bat file

## 12. Running Tests using Jenkins

## 13. Push the code to GitHub