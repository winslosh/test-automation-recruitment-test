Test Automation Recruitment Test
==================================

:rocket:Thank you for taking the time to do our technical test. It consists of two parts::rocket:

* [A technical test](https://github.com/winslosh/test-automation-recruitment-test/blob/main/README.md#computertechnical-test)
* [A few technical questions](https://github.com/winslosh/test-automation-recruitment-test/blob/main/README.md#speech_balloontechnical-questions)

### Before You Start
You will be committing your code and answers to your repo on [GitHub](http://github.com) so you will need to create an account if you do not already have one. 



# 🖥️ Technical Test

We have a [demo ecommerce](https://magento.softwaretestingboard.com/) site that you will be using.

The Technical test consists of 3 tasks:

## Task 1. Write test scenarios for the below feature

```gherkin
Feature: User Registration on the Demo Website

  As a visitor, I want to register an account so that I can access personalized features on the site.

  Acceptance Criteria:
    - The user must be on the registration page of the demo website to attempt registration.
    - When the user submits valid and unique credentials (username, email, password), a new account is successfully created.
    - If the credentials are not unique (e.g., the email or username already exists), the user is informed with an error message stating the issue.
    - Invalid credentials, such as an incorrectly formatted email or insufficient password complexity, result in an appropriate error message detailing what needs to be corrected.
    - Upon successful registration, the user is redirected to a confirmation or welcome page indicating successful account creation.

```

## Task 2. Add three more test cases which you feel would enhance the test coverage of the site

Describe additional scenarios you believe are important for testing the registration process, considering various user inputs and system responses.

## Task 3. Generate a test report that is easily readable by non-technical people

Utilize **Extent Reports** or **Allure** to create a comprehensive and visually appealing test report. The report should include detailed test execution results and summaries that facilitate quick understanding for non-technical stakeholders. Include screenshots, error details, and execution timelines in the report to enhance clarity and engagement.


### :file_folder:Platform Choice

You can use any testing framework / language you are experienced with

### Task requirements

Feel free to spend as much or as little time on the exercise as you like as long as the following requirements have been met.  

- Complete the three tasks described above.
- You should provide clear instructions on your test setup and how to execute your tests. The clarity and precision of these instructions - and the ease with which the interviewers can execute them - will be a key part of the assessment. 
- Create a README file detailing said instructions. 
- Please also use this README for listing any additional comments or observations you might want to share about your submission.

# :speech_balloon:Technical Questions

**Answer the following questions in a markdown file called** `Answers to technical questions.md`.

1. How long did you spend on the technical test? What would you add to your solution if you had more time? If you didn't spend much time on the technical test then use this as an opportunity to explain what you would add.
2. What do you think is the most interesting trend in test automation?
3. How would you implement test automation in a legacy application? Have you ever had to do this?

## :trophy:Finished?

:triangular_flag_on_post:Please commit your project to your GitHub and ensure it is set to **Public** .

**Your repository should include:** 

1. a folder containing the technical tests
2. the test report
3. a [markdown file](https://github.com/winslosh/test-automation-recruitment-test/blob/main/README.md#speech_balloontechnical-questions) with your answers to the Technical Questions 

:e-mail: Once you've completed all that's required, send the url of your GitHub repository to us for review.

### :heavy_check_mark:What we review

* **Correctness:** Do your tests compile and run?  
* **Code Quality:** Is your code maintainable, easy to understand, and conducive for future reuse or expansion?
* **Quality Focused:** Does your choice of test case scenarios provide adequate, given the limits, confidence in the quality of the web app tested?
* **Communication:** Are you able to explain why you picked your test case scenarios and what they do in your README and through other forms of communication?


![Good Luck!](http://i.imgur.com/DHxjAeQ.jpg)

#### :wave:Thanks for your time, we look forward to hearing from you!
