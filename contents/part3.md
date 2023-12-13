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
```
### Balancing UI and Non-UI tests
### When to use Non-UI tests
### Types of Non-UI tests
### Defining and testing non-functional requirements
### Discovering the design
## BDD and unit testing
### BDD, TDD and unit testing
### Going from acceptance criteria to implemented features
### Exploring low-level requirements, discovering design, and implementing more complex functionality
### Tools that make BDD unit testing easier
### Using executable specifications as living documentation