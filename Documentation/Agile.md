# Agile methods used by software developers

by Rens Vlooswijk

## Introduction

There are more than one ways to work as a group on a large project.
There is no correct answer to which method is the best, it is all based on personal preference, even so there are certain pro's and cons to certain methods.
But the overall idea of agile is a flexible work method.

### The Finland project

Our group project was in cooperation with a group of Finnish students.
3 members of our group went to Finland in February to establish a connection with the other students and think of a project that we could work on for the coming months.
In may those same Finnish students came to the Netherlands to finish the project.

<br><br>

## Scrum 
(Rens Vlooswijk)

We decided to use the Scrum method which is extremely versatile. It allows you to change your goals on a day to day or week to week basis. This makes task way easier to oversee and get done. It also provides a more joyous work experience since you get a task done basically every day which is very satisfying.

### Roles:

##### Product owner

The product owner is in close contact with the person or company giving the assignment
He makes most of the decisions and can add items to the backlog if the stakeholders requests them.

#### Scrum master

He is basically the groups coach, He oversees the project and tries to get the team to function optimally .

#### Developer / team member

They are the people that create most of the assignment.
This is the remainder of the developers, they code under the "Supervision" of the scrum master and try to get as much of the requirements done in time.

### What do I need

First of all you create a product backlog, this contains all the items that you are planning on making divided in small tasks which you can finish in about a day.

Then you need a sprint backlog, a sprint is 2 to 4 weeks depending on the size of the project, in which you try to finish a certain part of the assignment.

The sprint backlog is similar to the product backlog but it only has all the tasks that you are planning to do in that sprint.

You also need acceptation criteria, these are predetermined criteria of when you consider a task to be complete. These are decided by the group at the beginning and make sure that when you finish a task everybody is satisfied and it doesn’t need changing.

And last but not least you need a scrum board, A place that shows all the tasks and in what stage of completion they are.
This board is divided in sprints as well and you can assign a task to someone who will then be responsible for that part of the project.

<br><br>

## Extreme Programming (XP)
(Robin van Hoof)

A second form of agile workmethods is Extreme Programming, also known as XP. XP is an agile workmethod developed troughout the early 90's, that emphasizes teamwork, communication and feedback. One of the core advantages of XP is that its a agile method that encorperates dynamically changing software requirements. This feature makes XP a very good work method for for example developing new technologies where requiremenents might not always be able to be predetermined.

<br>

### Why XP?
XP is an agile workmethod that is applicable for specific development teams. A few requirements need to be met to make XP a viable workmethod. These are the following:

- #### Small local development team
Because one of the key aspects of XP is communication and teamwork, XP doest not really work on large remote development teams. To use the XP workmethod, a smaller development team is required and face to face contact with the team working in one workspace or office is highly recommended if not required.

- #### Changing software requirements
As talked about before, XP incorperates dynamically changing software requirements making it a very good workmethod for projects where requirements can not be determined in advance. This might for example be the case in projects where completely new technologies are developed and reuirements might change over the course of the project because of new research results.

- #### Automated unit testing possible
Finally one of the requirements to use XP is the possibility to apply automated unit testing to whatever platform the team is developing. The reason why this is important is because of the way a definition of done is defined in XP. This will be talked about more later on

<br>

### XP cycle
XP works in cycles that usually last one week. One cycle and thus one week is synonymous to an iteration. When working with XP, the team meets on the first day of the cycle to do a few tasks:

- Reflect on progress to date;
- Let customer pick what user stories they would like to be delivered that cycle;
- The team will discuss how to approach these selected stories;

The goal of an XP cycle is to deliver the selected features, where the definition of done is always backed up by unit and functionality testing. This done first of all to ensure that a deliverd feature works in the first place, but more importantly since requirements can change throughout the course of the project, also ensures later on that feature keep working even if the project steers into a different direction.

<br>

#### Quarterly cycle
Besides the weekly cycle XP also works with a Quarterly cycle (3 montly / 12 weekly cycles) which is synonymous to a release. This cycles has to key functions: First of all, the project will be delivered to the customer which can use this to give feedback but also to get an image of the complete picture of the project and give the customer an idea of when feature will be available. Second of all, this cycle functions as an ancher point for the development team: A point to look back at the whole project and see the direction its going.

<br>

### Testing
As mentioned before, XP incorperates testing into the definition of done for user stories. XP focusus on a Test-first programming aproach rather then the usual workflow of Code-first. This means instead of the normal workflow of "develop code -> write tests -> run tests", XP follows a "Write failing automated test -> Run failing test -> develop code to make test pass -> run test -> repeat" workflow.

<br>

#### Continous Integration
Since XP focusus on a Test-first, continous integration is a very import step. Continous integration means the automated testing of code when added to the larger codebase. This means that not only Unit testing is important (As talked about above) but also intergration testing.

<br>

### 10-Minute build
The goal of "10-minute build" is to automatically build and test the entire system within a timeframe of 10 minutes. The reasoning behind this is that if the step of building and testing the system were to take longer then 10 minutes, it would likely be done on a less frequent basis making it less likely for bugs to be cought onto and possible fixed earlier on in the development process.

<br>

### Roles
XP knows a few different important roles. These are the following:

<br>

- #### Customer
The customer is responsible for making all the business descisons in the project. This means deciding what functionality the system should provide, defining the acceptance criteria, setting budgets and making decision on what stories the development team should work on next.

In XP the customer is actively engaged in the development project and actively steers it into the direction they want it to go, practically making them part of the team itself. 

- #### Developer
The developers are defined as all team members working on realizing the project stories. What skills these developers should posses can vary a lot depending on what type of project is worked on.

- #### Tracker
Some teams working with XP might have a Tracker as part of their team. The tracker is a member of the development team that also carries the tracker role. The tracker is responsible for tracking any information or metric the teams deems important enough to actively keep track of. This is quite a broad term as the tracker can be used in a lot of different ways, but is also not needed in a lot of project.

- #### Coach
Every team using the XP workmethod will have a coach. The coach wil usually be a third party person, for example a consultant or someone from elsewhere in the organistation, that becouse part of the team. The job of the coach is to mentor the team and maintain discipline throughout the project