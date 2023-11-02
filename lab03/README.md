# SEG4105 - Lab 3 & Delierable 1

| Outline | Value |
| --- | --- |
| Course | SEG 4105 |
| Date | Fall 2023 |
| Student | Andy Ung, aung015@uottawa.ca |
| TA | Shabnam Hassaniahari, shass126@uottawa.ca <br> Ali Mirferdos , smirf045@uottawa.ca| 
| Professor | Andrew Forward, aforward@hey.com |  
| Team | Andy Ung 300117710 <br>|

## Breadboarding
### Stage 1
![Alt text](image.png)

### Stage 2 (Refined)
![Alt text](image-1.png)

# Deliverable 1

## FitShare - Overview
We want to create a gym web-application for those who are looking to start working out or share their own workouts. The application will function similar to how spotify users share playlists of their songs. Users will be able to follow their friends or other creators and view the various exercises within their workouts. Within the application, each workout will track the reps and sets of the different exercises. Over time users will be able to see their improvements such a new personal records or goals that have been accomplished. Workouts will also provide information such as the number of calories that have been burned. Exercises will also have a visual demonstration to ensure the client is following proper form. The product will be targeting all levels of fitness knowledge.

## Feature - Workout Generation
This feature represents a survey that takes in answers and creates a workout routine split that reflects specific choices. This accomdates certain restrictions and preferences provided from the user and creates user specific workout routines to ensure maximium satisfaction and performance. The goal is to allow any kind of user (any level of expertise) to take advantage of the survey to produce an informative playlist.  

## Shaping Work
### Problem
- Often times, one of the hardest parts of becoming active is the over abundance of choices with the amount of exercises available to you. Decision paralysis creates picking exercises much more difficult than it has to be with the fear of not knowing the most optimal exercises. Having a defined list created for you is a step that makes the whole process of becoming healthier even more simpler and easier.  

### Appetite
- This feature of workout generation needs to be done within 6 weeks and this should enable us to create a simple survey that asks a few questions on the individual to formulate a plan for them. It is imperative that these questions are closed (type) to ensure less extrapolating from the generation process. The survey should be designed to ask enough questions without any personal ones to gather enough details to form a concrete workout playlist to support one of the core values of creating and sharing workouts. This feature needs to be implemented within the existing `FitShare` framework web application.

### Solution
- A survey should be created with the intent to support users who would like an alternative means of creating workouts for a set of questions. This should be widely available and acessible on many fronts, but most important on the welcoming screen of the application. The survey is designed with closed questions in mind that can accepts a variety of answers to generate a specific tailored workout routine list. During the process and even after submission, they should be able to undo or restart the survey. The user would be allowed to save this workout routine such that the application allows them to use it to store information in regards to their exercises. The generator should formulate the answers in some kind of metric to easily translate the many forms of questions in some tangible unit to create a playlist. The survey must include a friendly user interface that allows any kind of user (technology proficiency) to maneuver and understand at what stage they are at. Each playlist should have a clear indication to the level of expertise (beginner, intermediate, advanced). 

### Rabbit Holes
- It is imperative that the answers collected in the survey are not collected or stored. The answers submitted are sent and then formulated into a list with only the list of exercises being kept. It is important to make sure that each question is well understood and with little to no possibilty of misinterpretion. Ideally with closed answered questions to have a quick submission and result time. With each question avoiding any type of bias (`loaded, leading, ambiguous`). 

### No Go's
- The workout generator should not take any consideration on previous workouts or goals in the decision process. Any questions relating to personal questions should be avoided as it is not necessary for this feature. 

