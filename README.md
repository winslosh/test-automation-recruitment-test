# Test Automation Recruitment Test

🚀 Thank you for taking the time to do our technical test. It consists of two parts 🚀

- A technical test
- A few technical questions

---

# Before You Start

You will be committing your code and answers to your own repository on **GitHub**, so you will need an account if you do not already have one.

---

# Demo Site Under Test

We will use **Automation Test Store**:

https://automationteststore.com/

Notes about the site:

- This is a **demo e-commerce store designed for practising automation testing**.
- No real purchases occur.
- The site contains login and registration functionality, but **login automation is not required for this exercise**.
- You may use **guest checkout and test data**.

---

# 🖥️ Technical Test

The technical test consists of **three tasks**.

---

# Task 1 – Write Test Scenarios (Gherkin)

Write test scenarios for the following feature.

```gherkin
Feature: Guest checkout for a shopper

  As a shopper
  I want to find a product and purchase it using guest checkout
  So that I can place an order without creating an account

  Acceptance Criteria:
    - A shopper can browse categories and open a product details page
    - A shopper can add a product to the basket from the product page
    - A shopper can update quantities in the basket and see totals update
    - A shopper can proceed to checkout using guest checkout
    - Checkout fields validate correctly when missing or invalid
    - After submitting checkout details, an order confirmation page is shown
```

Guidance:

- Keep scenarios **user focused**
- Include **both happy path and validation scenarios**
- You do **not** need to automate every scenario you write
- Your automated scenarios should reflect **your testing priorities**

---

# Task 2 – Add Three Additional Test Cases

Describe **three additional test cases** you believe would improve confidence in the quality of this website.

We are interested in seeing **how you think about testing**.

Examples of areas you might explore include:

- Search behaviour and empty results
- Basket behaviour (remove item, quantity limits, totals)
- Product price consistency between listing, product page and basket
- Category navigation and pagination
- Basic accessibility checks (page titles, accessible buttons, keyboard behaviour)
- Visual regression of a key page such as the home page or product page

You may choose any three scenarios you believe are valuable.

Explain briefly **why you selected them**.

---

# Task 3 – Generate a Test Report

Generate a **test report that is readable by non-technical stakeholders**.

You may use:

- **Allure**
- **Extent Reports**
- Or a similar reporting tool

Your report should include:

- Test execution summary
- Pass/fail status
- Execution timestamps
- Screenshots for failed tests
- Clear failure messages

The goal is that **someone without a testing background can quickly understand what happened**.

---

# Platform Choice

You may use **any language or framework you are comfortable with**.

Examples include:

- Playwright
- Cypress
- Selenium
- WebdriverIO
- or another framework you prefer

We are interested in seeing:

- Clean test structure
- Maintainable code
- Reliable selectors
- Sensible waiting strategies
- Tests that run consistently

---

# Task Requirements

Please ensure the following requirements are met:

- Complete the three tasks above
- Provide **clear setup and execution instructions**
- Create a **README file** explaining:

  - prerequisites
  - installation steps
  - how to run the tests
  - how to generate or view the report
  - any assumptions or trade-offs made

You may also include **additional notes or observations** if helpful.

---

# Optional Enhancements (Nice to Have)

These are **not required**, but demonstrate modern automation practices:

- CI workflow (for example GitHub Actions)
- Parallel test execution
- Basic test data strategy
- Retry logic or stability improvements
- Linting or formatting rules
- Clean project structure

---

# 💬 Technical Questions

Answer the following questions in a markdown file called:

`Answers to technical questions.md`

### 1

How long did you spend on the technical test?

What would you add to your solution if you had more time?

### 2

What do you think is the most interesting trend in **test automation today**?

### 3

How would you implement test automation in a **legacy application**?

Have you ever done this before?

---

# 🏁 Finished?

Commit your project to **GitHub** and ensure the repository is **Public**.

Your repository should include:

1. A folder containing the automated tests
2. The test report (or instructions to generate it)
3. `Answers to technical questions.md`

Once complete, send us the **URL of your GitHub repository**.

---

# ✅ What We Review

We assess submissions based on:

**Correctness**  
Do the tests compile and run successfully?

**Code Quality**  
Is the code readable, maintainable and well structured?

**Quality Focus**  
Do the selected scenarios provide confidence in the application?

**Communication**  
Are the README instructions clear and easy to follow?

**Automation Practice**  
Selectors, waits, reporting, structure and reliability.

![Good Luck!](http://i.imgur.com/DHxjAeQ.jpg)

#### :wave:Thanks for your time, we look forward to hearing from you!
