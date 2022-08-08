# Portfolio Management API Project

## Overview

Your team is challenged with designing the outline of a application to manage a financial portfolio.

The portfolio may contain some or all of stocks, bonds, cash etc. Part of the challenge is to make use of your financial markets training to decide on what data should be stored.

The challenge has two parts:

1. Design the application on paper, including an overall system architecture diagram and user interface mockups

2. Implement a single REST API spring boot application as a Proof of Concept of one small piece of your application. You DO NOT need to implement the complete application.

Your team, or team members may choose to emphasise or work more on either item 1 or item 2 above depending on your experience and skillsets.

## Technical Goals

You should aim to create a Proof Of Concept spring boot REST API.

This API should allow saving and retrieving records that describe the contents of a financial portofolio.

## Notes

1. There will be no authentication and a single user is assumed, i.e. there is no requirement to manage users.

2. You should use MySQL for any persistent storage. IF you have any experience with MongoDB you may choose to use that instead.

3. You should include a swagger-ui for your REST api. This makes it easier for instructors to help.

4. Make good use of git, ensure all code is kept in revision control.

5. Include a Dockerfile to build your spring boot application into a Docker image.

6. Include a Jenkinsfile to build a jenkins pipeline that will test, build and deploy your application to OpenShift. Note - your instructors will give you a skeleton Jenkinsfile that you can use as a base. You DO NOT need to write a Jenkinsfile from scratch.

## Technical Getting Started Checklist

1. Create a spring boot skeleton project including the necessary dependencies (e.g. with start.spring.io)

2. Create a bitbucket repository.

3. Add, commit, push your skeleton spring-boot project to your bitbucket repository.

4. Ensure your team has access to the bitbucket repository.

5. Decide on the absolute MINIMUM fields to store in the database for a first working system e.g. the first version of your model object may just be: String id, String stockTicker, int volume, String costPrice, String buyOrSell.

If you get stuck getting any of the above completed then contact your instructor for help.

## Project Management Getting Started Checklist

1. As a team decide how you will approach the work.

2. Make a task list. Ideally use a tool such as trello to keep track of tasks.

3. Some or your team may work on the DESIGN of an outline application. While some of your team work on BUILDING the demonstration REST API.

4. Choose the tasks required for a MINIMAL implementation first.

4. Your instructor will drop in regularly to see how you're progressing. Make a note of any questions so that you're ready to ask them then.

5. Your team should get together and decide on an initial set of data that you will store. A good team decision on this is a good path to success, however remember to STAY AGILE.

Note: The single biggest mistake that teams make in this project is starting out with a data model that is too complex.

## Suggestions for Success

1. START SMALL. Get a system working that stores a very simple object with minimal fields. You can then enhance to store more complex records.

2. Try pair programming, it can be very effective.

3. Take concious steps to keep a good energy in the team. E.g. give your team a name, systematically plan check-ins with each other.

4. Emphasise quality over quantity.


## End of Hackathon

1. You will be asked to submit the URLs of your bitbucket repositories.

2. You will be asked to prepare a short 10/15min presentation on your work.

3. Your presentation should include an outline of your DESIGN of a portfolio application. And a demonstration of your IMPLEMENTATION of a spring boot API.

4. Everyone should speak at the presentation.

##
### Appendix A: Notes on Teamwork

It is expected that you work closely as a team during this project.

Your team should be self-organising, but should raise issues with instructors if they are potential blockers to progress. 

Your team should use a task management system such as Trello to keep track of tasks and progress. Divide the work 

Your team should keep track of all source code with git and bitbucket.

You may choose to create a separate bitbucket repository for each component that you tackle e.g. front-end code can be in its own repository. If you create more than one spring-boot application, then each can have its own bitbucket repository. To keep track of your repositories, you can use a single bitbucket 'Project' that each of your repositories is part of.

Your instructor and team members need to access all repositories, so they should be either A) made public OR B) shared with your instructor and all team members.

Throughout your work, you should ensure good communication and organise regular check-ins with each other.

##
### Appendix B: UI Ideas

The screen below might give you some ideas about User Interfaces. You are DEFINITELY NOT expected to implement a user interface. This is JUST FOR DEMONSTRATION of the type of thing that COULD be shown in mockups for your DESIGN.

Just to repeat.... This is NOT what is expected to be implemented, it is simply here to give ideas for your DESIGN!!

![Demonstration Portfolio UI](https://www.benivade.com/neueda-training/Tech2020/DemoPortfolioScreen.png)
