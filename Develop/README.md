# 03 JavaScript: Password Generator

Create an application that generates a random password based on user-selected criteria. This app will run in the browser and feature dynamically updated HTML and CSS powered by your JavaScript code. It will also feature a clean and polished user interface and be responsive, ensuring that it adapts to multiple screen sizes.

If you are unfamiliar with special characters, take a look at [some examples](https://www.owasp.org/index.php/Password_special_characters).

## User Story

```
AS AN employee with access to sensitive data
I WANT to randomly generate a password that meets certain criteria
SO THAT I can create a strong password that provides greater security
```

## Acceptance Criteria

```
GIVEN I need a new, secure password...

WHEN I click the button to generate a password
THEN I am presented with a series of prompts for password criteria

WHEN prompted for password criteria
THEN I select which criteria to include in the password

WHEN prompted for the length of the password
THEN I choose a length of at least 8 characters and no more than 128 characters

WHEN prompted for character types to include in the password
THEN I choose lowercase, uppercase, numeric, and/or special characters

WHEN I answer each prompt
THEN my input should be validated and at least one character type should be selected

WHEN all prompts are answered
THEN a password is generated that matches the selected criteria

WHEN the password is generated
THEN the password is either displayed in an alert or written to the page
```

The following image demonstrates the application functionality:

![password generator demo](./Assets/03-javascript-homework-demo.png)

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

## Repository Quality Requirements

* The repository must have a unique name. (Does not contain words like "assignment" or "homework" in the repository name.)

* Follows best practices for file structure and naming conventions.
  * Avoid uppercase letters in file names. (Except for .js files which export a constructor or React component.)
  * File names MUST NOT contain spaces. Use "-" or "_" to separate words in a file name.
  * Avoid using special characters.
  * Organize assets using folders.
  * Has an `index.html` file at the root of the repo if deploying on GitHub pages.

* Follows best practices for code formatting.
  * Variable and function names use consistent casing such as camelCase or snake case. Avoid single letter names for things.
  * Indentation applied to functions, objects, and other code blocks.
  * Uses consistent indentation characters: tabs, 2 spaces, or 4 spaces.
  * Comments used where code is difficult to understand or reason for a series of expressions is not obvious.

* Repository contains a quality readme with a description, screenshot, link to deployed application, etc. (see [Good README Guide](../../01-HTML-Git-CSS/04-Supplemental/Good-README-GUIDE/README.md))

* Several commits should be made during the development process as features and assets were completed/updated. Refer to [Commit Early and Often](#commit-early-and-often) below.


## Application Quality Requirements

* Application user experience is intuitive and easy to navigate.

* Application user interface style is clean and polished.

* Application is free of errors in the console.

## Commit Early and Often

One of the most important skills to master as a web developer is version control. Building the habit of committing via Git is important for two reasons:

* Your commit history is a signal to employers that you are actively working on projects and learning new skills.

* Your commit history allows you to revert your codebase in the event that you need to return to a previous state.

Follow these guidelines for committing:

* Make single-purpose commits for related changes to ensure a clean, manageable history. If you are fixing two issues, make two commits.

* Write descriptive, meaningful commit messages so that you and anyone else looking at your repository can easily understand its history.

* Don't commit half-done work, for the sake of your collaborators (and your future self!).

* Test your application before you commit to ensure functionality at every step in the development process.

We would like you to have well over 200 commits by graduation, so commit early and often!

- - -
© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
