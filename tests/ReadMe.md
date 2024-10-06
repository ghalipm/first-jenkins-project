// One time commands:
npm install
npm install allure-commandline
npm install -D @playwright/test allure-playwright

// run the tests and see the report: 
npx playwright test
npx allure generate allure-results -o allure-report --clean
npx allure open allure-report