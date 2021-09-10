# Technical Assignment for Quality Engineers

This is the Pxr Tech GmbH technical assignment for Quality Engineers. You'll find two main automation tasks: 1) Webdriver and 2) API functional testing. These two tasks is required as part of this assignment.

The tasks below are simple and therefore we'd like simple solutions where you show good coding practices such as the clear folder structure, intuitive method names, Page Object Pattern and Object Oriented Principles as a starting point. We recommend you follow the coding guidelines below and read the tasks carefully.

### General Coding Guidelines:

- Don't check in unnecessary files. Use .gitignore to exclude bin folder and other unnecessary files.
- Granular commits – we want to see your thinking process.
- Following best coding practices ([SOLID](https://levelup.gitconnected.com/s-o-l-i-d-principles-explained-in-python-with-examples-83b2b43bdcde), [DRY and KISS](https://dzone.com/articles/software-design-principles-dry-and-kiss), leverage [OOP principles](https://www.analyticsvidhya.com/blog/2020/09/object-oriented-programming/)).
- Clear, maintainable code.
- Send us the repository link for the project along with the test results attached checked in as HTML report.
- Please use:
  - Python + playwright.dev or Selenium.

## Quality Engineer Assignment

## Task 1: Functional E2E Automation

Functional automation for web UI testing using Selenium Web Driver or Playwright.

- Open Google and perform a search for ‘ pxr legal ’.
- Get all search results displayed and validate how many pxr-legal links there are available (you may only focus on the first page of the search results for the purpose of this task).
- Navigate to pxr careers link and confirm that we have 11 open positions in the tech section of the page and one of them is QA Engineer position.

Requirements:

- If you use Python, please write a feature file in BDD style (Bonus - Optional).
- Develop the automation framework for the above feature file / spec.

On average, this task can be completed in 2-3 hours, but you are welcome to spend more time on it to submit a better quality code.

## Task 2: Functional API Testing

Functional automation for API testing.
Write a test in python for the following REST API:

https://jsonplaceholder.typicode.com/

Requirements:

- Get a random user (userID), print out its email address to console.
- Using this userID, get this user’s associated posts and verify they contains a valid Post IDs (an Integer between 1 and 100).
- Do a post using same userID with a non-empty title and body, verify the correct response is returned (since this is a mock API, it might not return Response code 200, so check the documentation).

On average, this task can be completed in 2-3 hours, but you are welcome to spend more time on it to submit a better quality code.

Thanks for taking part in our selection process and good luck!
