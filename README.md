# ReadMe-Generator


![readmde](https://user-images.githubusercontent.com/65749636/107004876-c9bcde80-6743-11eb-9aac-f8b818465fbd.PNG)
https://user-images.githubusercontent.com/65749636/107005975-55833a80-6745-11eb-98d9-89d95b1a60cc.mp4

![Recording 1 (2)](https://user-images.githubusercontent.com/65749636/107002806-a3497400-6740-11eb-97cc-51e3cccfc920.gif)



09 Node.js Homework: Professional README Generator

Your Task
When creating an open source project on GitHub, it’s important to have a high-quality README for the app. This should include what the app is for, how to use the app, how to install it, how to report issues, and how to make contributions—this last part increases the likelihood that other developers will contribute to the success of the project.
You can quickly and easily create a README file by using a command-line application to generate one. This allows the project creator to devote more time to working on the project.
Your task is to create a command-line application that dynamically generates a professional README.md file from a user's input using the Inquirer package. Review the Good README Guide as a reminder of everything that a high-quality, professional README should contain.
The application will be invoked by using the following command:
node index.js
Because this application won’t be deployed, you’ll also need to provide a link to a walkthrough video that demonstrates its functionality. Revisit the Screencastify Tutorial in the prework as a refresher on how to record video from your computer. You’ll need to submit a link to the video and add it to the README of your project.

User Story
AS A developer
I WANT a README generator
SO THAT I can quickly create a professional README for a new project

Acceptance Criteria
GIVEN a command-line application that accepts user input
WHEN I am prompted for information about my application repository
THEN a high-quality, professional README.md is generated with the title of my project and sections entitled 
Description
Table of Contents
Installation
Usage
License
Contributing 
Tests
Questions

WHEN I enter my project title
THEN this is displayed as the title of the README
WHEN I enter a description, installation instructions, usage information, contribution guidelines, and test instructions
THEN this information is added to the sections of the README entitled Description, Installation, Usage, Contributing, and Tests
WHEN I choose a license for my application from a list of options
THEN a badge for that license is added near the top of the README and a notice is added to the section of the README entitled License that explains which license the application is covered under
WHEN I enter my GitHub username
THEN this is added to the section of the README entitled Questions, with a link to my GitHub profile
WHEN I enter my email address
THEN this is added to the section of the README entitled Questions, with instructions on how to reach me with additional questions
WHEN I click on the links in the Table of Contents
THEN I am taken to the corresponding section of the README
