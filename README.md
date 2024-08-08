# Taskserver (CCSync)

## Google Summer of Code'24
_Name : Abhishek_ <br/>
_Slack : [Link to Slack ID](https://rhccgsoc15.slack.com/team/U0646QP9HDK)_ <br/>
_GitHub Username : [its-me-abhishek](https://github.com/its-me-abhishek)_ <br/>
_Mentor: [Mabud Alam](https://github.com/Pavel401)_ <br/>

## My project work

During the summer period, I worked on the development of CCSync - a web UI + API that helps in retreival of tasks from a [`taskchampion-sync-server`](https://github.com/GothenburgBitFactory/taskchampion-sync-server) container. The users can thus create, read,
or update tasks on either the Taskwarrior CLI or the frontend (website or the [Taskwarrior flutter app](https://github.com/CCExtractor/taskwarrior-flutter)) and sync them across all their Taskwarrior 3.0 clients (and higher).
My work revolved around creating series of commands on the backend that can be able to perform various actions on the Taskwarrior client of the user, and subsequently integrating all the endpoints to the frontend, i.e., both the [Taskwarrior flutter app](https://github.com/CCExtractor/taskwarrior-flutter) and the [website frontend.](https://github.com/its-me-abhishek/ccsync/tree/main/frontend)

I learnt alot during this process about Golang, React, Docker, Taskwarrior, Flutter, etc.

The following is a demo of working of 
- **CCSync website:**
  - _Landing Page:_
  
https://github.com/user-attachments/assets/b5359524-67ba-4a44-bd58-993cf3de63b4

  - _Home Page Screenshots:_
  - _Task view and details:_
  - _Adding/Modifying a Task:_
  - _Syncing Tasks and Deleting all tasks on Firestore:_
  - _Task Filters:_


- CCSync with Taskwarrior Flutter App:
// TO DO


## Work Track

1. Logic / Backend Development

_Objective_: To develop the core backend functionality of CCSync, enabling bidirectional synchronization between Taskwarrior clients and Taskchampion Sync Server.

| Name of the Task | Description | Link to work |
|------------------|-------------|--------------|
| Taskwarrior Integration | <ul><li>Develop functions to perform various operations on tasks from Taskwarrior.</li></ul> | [Link to work](https://github.com/its-me-abhishek/ccsync/tree/main/backend) |
| Authentication and Security | <ul><li>Implement OAuth Google Sign in so as to generate secrets for users, and for segregation of tasks on the Firestore Database depending on the email of the user</li> <li>Used CORS for restricting unauthorised access to the user's data</li></ul>| [Link to work](https://github.com/its-me-abhishek/ccsync/tree/main/backend) |

2. UI / Frontend Development

_Objective_: To develop the core frontend functionality of CCSync, using which, the users can sign up/sign in and get their credentials. The users can follow the setup guide to easily setup sync on their Taskwarrior 3.0 clients.

| Name of the Task | Description | Link to work |
|------------------|-------------|--------------|
| User Dashboard	 | <ul><li>Develop a dashboard for users to see their tasks, statistics, and sync status.</li></ul> | [Link to work] |
| Task List Display | <ul><li>Develop a user interface to display a list of tasks fetched from Taskwarrior.</li></ul> | [Link to work] |
| Task Detail View | <ul><li>Implement a detailed view for individual tasks, including all task attributes and actions.</li></ul> | [Link to work] |
| Task Creation and Editing		 | <ul><li>Create forms for adding new tasks and editing existing ones, with validation and error handling.</li></ul> | [Link to work] |
| Setup Guide	 | <ul><li>Create an easy guide using which the users can easily setup sync for all their Taskwarrior 3.0 clients (or  higher).</li></ul> | [Link to work] |


3. Dockerizing the web app

| Name of the Task | Description | Link to work |
|------------------|-------------|--------------|
| To-Do | <ul><li>To-Do</li></ul> | [Link to work] |

4. Integrating with Taskwarrior Flutter App

| Name of the Task | Description | Link to work |
|------------------|-------------|--------------|
| To-Do | <ul><li>To-Do</li></ul> | [Link to work] |

## Link to work
- [Link to CCSync repository](https://github.com/its-me-abhishek/ccsync)
- [Link to CCSync Docs repository](https://github.com/its-me-abhishek/ccsync-docs)
- [Link to all CCSync pull requests](https://github.com/its-me-abhishek/ccsync/pulls?q=is%3Apr+is%3Aclosed)
- [Link to all CCSync Docs commits](https://github.com/its-me-abhishek/ccsync-docs/commits/main/)

## Weekly Reports
These are the weekly reports that i had submitted to CCSync during GSoC period:
- [Week 1](https://abhishek31.medium.com/gsoc-week-1-at-ccextractor-abb9f13a4d94)
- [Week 2](https://abhishek31.medium.com/gsoc-week-2-at-ccextractor-b8538b394ef4)
- [Week 3](https://abhishek31.medium.com/gsoc-week-3-at-ccextractor-e15393457db9)
- [Week 4](https://abhishek31.medium.com/gsoc-week-4-at-ccextractor-429fc4c3d164)
- [Week 5](https://abhishek31.medium.com/gsoc-week-5-at-ccextractor-125b2607a0d7)
- [Week 6](https://abhishek31.medium.com/gsoc-week-6-at-ccextractor-75936fe98d98)
- [Week 7](https://abhishek31.medium.com/gsoc-week-7-at-ccextractor-12fc1036c081)
- [Week 8](https://abhishek31.medium.com/gsoc-week-8-at-ccextractor-41c57a724e88)
- [Week 9](https://abhishek31.medium.com/gsoc-week-9-at-ccextractor-f1060cdf5f71)
- [Week 10](https://abhishek31.medium.com/gsoc-week-10-at-ccextractor-9ba4840c434c)
- Week 11
- Week 12


