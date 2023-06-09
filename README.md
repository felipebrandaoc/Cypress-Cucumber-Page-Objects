# Challenge Cypress - Cucumber - Page Objects

To download this project dependencies just run the command below on your terminal:

```
npm install
```

To run the tests with Cypress in window mode you can run:

```
npx cypress open
```

To run the tests with Cypress in headless mode, just use the command:

```
npx cypress run
```

The project is divided in:

**Cypress**<br />
**- Downloads:** Any files downloaded while testing an application's file download feature will be stored in the downloadsFolder which is set to cypress/downloads by default.<br />
**- Fixtures:** Fixtures are used as external pieces of static data that can be used by your tests. Fixture files are located in cypress/fixtures by default, but can be configured to another directory.<br />
**- e2e:** This folder contains all things related with the test cases (features and step definitions).<br />
**- Features:** Here we have the .feature files, where we describe and document our test scenarios in Gherkin language.<br />
**- Step_Definitions:** In this folder we have the test scripts itself, where cucumber do your magic and make all the test scenarios work based on the BDD description.<br />
**- Support:** The support folder is a great place to put reusable behavior such as custom commands or global overrides that you want applied and available to all of your spec files. Files in here runs before every single spec file.<br />
**- Support/PageObjects:** The PageObjects folder is the one where we apply our design pattern that will help to organize and make our code pleasurable. Page Object is a Design Pattern that enhances test maintenance and reduce code duplication.<br />
**- Screenshots:** this folder contains some screenshots taken after each test scenario's run. This can help to evidence application's behaviour and examine/fix bugs. <br />
**- Videos:** this folder contains some short videos taken after each test scenario's run. This can help to evidence application's behaviour and examine/fix bugs alongside with Screenshots. <br />
