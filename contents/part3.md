## From executable specifications to rock-solid automated acceptance tests
```
  - The importantce of writing high-quality automation tests
  - Preparing test data for the tests
  - Implementing reliable and sustainable tests
```
### Writing industrial-strength acceptance tests
### Automating your test setup process
- Initializing the database before each test
- Initializing the database before each test suite
- Using initialization hooks
- Setting up scenarios-specific data
- Using personas and known entities
### Separating the what from the how
- The Business Rules layer describes the expected outcomes
- The Business Flow layer describes the user's journey
- The Technical layer interacts with the system
- How many layers should you have?
## Automating acceptance criteria for the UI layer
```
  - Why and when should you automate UI tests
  - Using Selenium WebDriver to automate UI tests
  - Finding and interacting with elements
  - Using the Page Object pattern to encapsulate UI details
  - Libraries that extend Selenium WebDriver
```
### When and how should you test the UI
- The risks of too many web tests
- Web testing with headless browsers
- How much web testing do you really need?
### Automating web-based acceptance criteria using Selenium WebDriver
- Getting started with Selenium WebDriver in Java
- Identifying elements
- Interacting with elements
- Working with asynchronous pages and testing AJAX
- Writing test-friendly web applications
### Using the Page Object pattern to make test cleaner
- The Page Object pattern
- Writing well-designed Page Objects
- Using libraries that extend Selenium WebDriver
## Automating acceptance criteria for the Non-UI layer
```
  - Balancing UI and Non-UI acceptance criteria
  - Where to use Non-UI tests
  - Automation acceptance tests for the controller layer of a web application
  - Automation acceptance tests that test application code directly
  - Automating acceptance tests for remote services
  - Automating acceptance tests for non-functional requirements
  - Discovering applicatioin design through Non-UI tests
```
### Balancing UI and Non-UI tests
### When to use Non-UI tests
### Types of Non-UI tests
- Testing against the controller layer
- Testing business logic directly
- Testing service layer
### Defining and testing non-functional requirements
### Discovering the design
## BDD and unit testing
```
  - The relationship between BDD, TDD and unit testing
  - Going from automated acceptance criteria to implemented features
  - Using BDD to discover design and explore low-level requirements
  - Tools that help you write BDD unit tests more easily
```
### BDD, TDD and unit testing
- BDD is about writing specifications, not tests, at all levels
- BDD builds on established TDD practices
- BDD unit-testing tools are there to help
### Going from acceptance criteria to implemented features
- BDD favors an outside-in approach
- Start with a high-level acceptance criteria
- Automate the acceptance criteria scenario
- Implement the step definitions
- Understand the domain model
- Write the code you'd like to have
- Use the step definition code to specify and implement that application code
- How did BDD help?
### Exploring low-level requirements, discovering design, and implementing more complex functionality
- Use step definition code to explore low-level requirements
- Working with tables of examples
- Discover new classes and services as you implement the production code
- Implement simple classes or methods immediately
- Use a minimal implementation
- Use stubs and mocks to test-drive the implementation of more complex functionality
- Expand on low-level technical specifications
### Tools that make BDD unit testing easier
- Practicing BDD with traditional unit-testing tools
- Writing specifications, not tests: the RSpec family
- Writing more expressive specifications with Spock
### Using executable specifications as living documentation
- Using fluent coding to improve readability
- Fluent assertions in JavaScript
- Fluent assertions in static languages