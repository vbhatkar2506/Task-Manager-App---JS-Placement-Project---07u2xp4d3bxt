# html-css-js-project-boilerplate

Guidelines 
Why do we need to create projects?
We learn coding by actually coding software. Projects are a good way to build solutions to interesting problems.
Projects reflect that a student has all the skills needed to build real-life software. 
Good projects make it easier for employers to assess and decide on hiring a candidate.
 
What do some good projects look like? (only for reference purpose)
Snake game
UI similar to the snake eating food game in old phones
Features: snake grows in length & speed by eating food, game over when the snake hits the boundary or eats its own-self
https://www.youtube.com/watch?v=-oOgsGP3t5o
Alarm
UI comparable to android/ios alarm app
Features: CRUD, view & delete multiple alarms together, alarm notifications, snooze
Sample: https://drive.google.com/drive/folders/1YMlOOIlNVAd4rK6JwriwXSeXZ9MfhKzt?usp=sharing
Ecommerce ordering
Features: Catalogue of products, check-out cart, payment integration, deployment on netlify/heroku or similar web hosting
Sample: React Phone E-Commerce Project - YouTube
 
How should students build projects?
Start with smaller projects consisting of only a few features. Small projects will help you in learning. Once you are confident with making projects, then move on to larger real-world projects that you can add to your resume.
Prepare step by step plan with a timeline on how you will build the project. These steps can include
Problem statement
Design
Static components identification
Logic & flow of data - architecture
Libraries & frameworks needed
Coding individual components
Also, have an understanding of why you are using a particular stack/ framework/ library/ tool/ architecture.
 
 
What makes a good project?
Problem statement
Start with a problem statement relevant to the real world, your project should solve that problem
The problem statement should not be too big for students to complete in one month
Define
Designing
The design of a project is very important, especially for front-end developer students.
Design guidelines
If the student is familiar with design tools like Figma, it would be a bonus.
Front-end
Detailed styling of UI components, preferably on CSS instead of bootstrap/tailwind
The website is responsive & adaptive to different devices
Using modern libraries like particle JS, material UI, etc.
Minor animations over each component would be a bonus
Data manipulation
Logically decoupled modules should be in separate files
Data of multiple components should be stored & transferred through state & props
Dynamic update (Live interactions) - value updated in one tab is also reflected in another tab of the same app
Clean code
Ensuring proper indentation & presentation of code
Variable names should not be random
https://www.youtube.com/watch?v=UjhX2sVf0eg
Deployment
Asynchronous Data/API interactions in the project (eg. Google Authentication, payment, Maps, unsplash, lyrics API, etc.)
Demonstrating deployment & infra (eg. hosting on netlify/heroku/AWS)
Managing versions on GitHub
 
When to make projects?
Students should start building small learning projects while they are learning HTML. Then keep building projects for every topic covered in class.
A student should start working on projects that they will add in their resume after they complete learning React.



# Task Manager App

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/dadea1ac-94f3-4e97-b9d5-59585c2a6906/Untitled.png)

**Note- You can ignore the comment field in the image given above. We will be adding only the name and the description of the task**

## Project o**bjective**

- You will be building a Task Manager application using html, CSS and JavaScript
- In the end, we’ll have a web application which allows user to manage tasks. It will have four sections - Open, In Progress, In Review and Done

## **Project Context**

- It has become difficult to manage and tasks daily for us due to the modern busy lifestyle. So we will be building a task manager app that helps us organize our things well.

**Tech stack Prerequisite:**  HTML, CSS, JavaScript

## Project Steps

- Step 1
    - Create a text input field which takes in a name input and creates a task with that name
- Step 2
    - The task gets created in the open section
- Step 3
    - We can add a small description for each task. When we click on the task a modal should open up in which we can add description of the task and save it.
- Step 4
    - The task can be drag and dropped to the other 3 sections (In Progress, In Review and Done).
    

## Project Checkpoints

- Input which creates a task
- The App has four sections - Open, In Progress, In Review and Done
- Every Task should have its own description
- Add the drag and drop functionality to the tasks so that they can be moved to the other three sections.