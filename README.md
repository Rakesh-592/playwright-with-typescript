# Playwright with TypeScript

A simple end-to-end test automation project using **Playwright** and
**TypeScript**.

## Tech Stack

-   Playwright
-   TypeScript
-   Node.js
-   Git & GitHub

## Project Structure

``` text
Playwright/
├── mytest/
│   └── login.spec.ts
├── tests/
├── playwright.config.js
├── tsconfig.json
├── package.json
├── package-lock.json
└── .gitignore
```

## Prerequisites

Make sure you have the following installed:

-   Node.js
-   npm

Check the installations:

``` bash
node --version
npm --version
```

## Installation

Clone the repository:

``` bash
git clone https://github.com/Rakesh-592/playwright-with-typescript.git
```

Go to the project directory:

``` bash
cd playwright-with-typescript
```

Install the dependencies:

``` bash
npm install
```

If Playwright browsers are not installed, run:

``` bash
npx playwright install
```

## Running Tests

Run all Playwright tests:

``` bash
npx playwright test
```

Run a specific test:

``` bash
npx playwright test mytest/login.spec.ts
```

Run tests with the browser visible:

``` bash
npx playwright test mytest/login.spec.ts --headed
```

## Playwright Report

After test execution, open the HTML report using:

``` bash
npx playwright show-report
```

## Purpose

This project is a simple Playwright automation project created to
practice and demonstrate end-to-end web application testing using
TypeScript.

## Author

**Rakesh Sai Sankar Kunapareddy**

GitHub: https://github.com/Rakesh-592
