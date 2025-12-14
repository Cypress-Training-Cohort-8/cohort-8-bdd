## BDD Explained

---

### Packages and Dependencies

---

- [Cypress](https://docs.cypress.io/app/get-started/install-cypress "Cypress Documentation Guide")
- [Faker](https://www.npmjs.com/package/@faker-js/faker "Helps to generate unique random variables")
- [LambdaTest CLI](https://www.npmjs.com/package/lambdatest-cypress-cli "A good tool for cross browser testing and accessibility testing")
- [Cypress Cucumber Preprocessor](https://www.npmjs.com/package/@badeball/cypress-cucumber-preprocessor)
- [Cypress Esbuild Preprocessor](https://www.npmjs.com/package/@bahmutov/cypress-esbuild-preprocessor)

---

### Installation Guide

---

1. Clone the Repository to your desired local machine with `git clone <project-web-url>`.
2. Navigate into the cloned repository and open a terminal within it.
3. To install the dependencies, you can run `npm ci` or `npm install` depending on how you wish to install.

   > [!NOTE] `npm ci` means you're installing via the package-lock.json while `npm install` means you are installing via package.json
   >

---

### Execution

---

#### Via Lambdatest:

* You need to first create an account on [lambdatest](https://www.lambdatest.com/)
* Copy the credentials and add it to the `lambdatest-config.json` file like this above the browser object.
  ```
  "lambdatest_auth": {
        "username": "lt-username",
        "access_key": "lt-access-key"
     },
  ```

- Run the test with `npx lambdatest-cypress run`

#### Run Test Locally

From the root of the folder, run `npx cypress run` for headless mode. You can run `npx cypress open --e2e` for browser mode where the test runner will be launched.

---
