# CSC 510- Focus Bot: P.A.M- Personal Accountability Manager

## Presentation

Link to the presentation video: https://drive.google.com/drive/folders/1oku8uWDBFKL0ZUuJMFDwOJSx7OegTB_X?usp=sharing

## Report

### Problem the Bot Solved

*HOCUS POCUS, DON’T LOSE YOUR FOCUS*
 
The primary problem we expected to solve over the course of our BOT development is mitigating the effects of productivity loss particularly targetting these effects in a remote work environment.


https://www.techrepublic.com/article/distractions-and-the-downsides-to-working-from-home/

We are aware that a company’s profitability is proportional to the overall productivity of different departments which in turn depends on the employee’s throughput. How to get the most and aid the employees to achieve their potential in every project? Automation with BOTs. In light of the current pandemic causing seismic disruptions to work culture and forcing employees around the globe to transition to a remote work environment, employees could do with a little help to create a pseudo work environment without having to carry out mundane and non-essential tasks. Working from home, despite sounding great for the first few weeks comes with numerous challenges- from virtual collaborations, employees losing track of time and goals to be achieved, and a variety of other distractions. The lack of in-person interaction and collaboration makes it difficult for higher authority to create a high-performing environment and hence lies on the individual to create a strong communication process and the team to build a self-organizing culture especially in the development and deployment phases of the software development life cycle.

To facilitate this transition and avoid distractions, our bot acts as a mini personal assistant with a primary objective to enhance productivity and provide the option to collaborate in crucial instances and subsequently, lead to the timely development and smooth software life cycle progress from an individual and team’s perspective.

### Primary Features and Screenshots

Our Focus Bot has five primary use cases:

1. Personal To-Do List
2. Github Issues
3. Reminders
4. Scheduling a Meeting
5. Automatic Reminders for Github Issues

=> **Personal To-Do List**

The main features of this use case includes:

1. *add todo*
2. *show todo*
3. *remove todo*

The Focus Bot enables the users to create their own personal to-do list. Once created, the users have the option to view and remove tasks from the list. This feature allows the users to keep track of their tasks and make sure they don't have any backlogs.

* *add todo*

![add todo](https://media.github.ncsu.edu/user/22704/files/85f5d565-efaf-4f01-b131-bb9d20d39efb)

* *show todo*

![show todo](https://media.github.ncsu.edu/user/22704/files/b9d9e894-3654-4253-b789-930f19aed3a6)

* *remove todo*

![remove todo](https://media.github.ncsu.edu/user/22704/files/29e74448-7463-431c-a47f-b1c825caf41d)

=> **Github Issues**

The main features of this use case includes:

1. *create issue*
2. *show issues*
3. *close issue*

The bot allows the users to create issues in a specific repository. The created issues will be updated in Github and the users can view and close issues on the channel itself. The purpose of this feature is to facilate users to smoothly update issues in the channel itself instead of them going to Github everytime to update the status of an issue. 

* *create issue*

![create issue](https://media.github.ncsu.edu/user/22704/files/547bed2d-ed01-4475-922b-855bf3573825)

* *show issues*

![show issues](https://media.github.ncsu.edu/user/22704/files/0988b106-0183-4a1a-a7f6-757b3c7d8497)

* *close issue*

![close issue](https://media.github.ncsu.edu/user/22704/files/31bcd772-af88-49b7-b43f-3b08f0aa3946)

![check close issue](https://media.github.ncsu.edu/user/22704/files/fa9ce375-d27c-4cb1-a0d5-8d033ecb49d0)

=> **Reminders**

The main features of this use case includes:

1. *create reminder*
2. *show reminders*
3. *remove reminder*

The bot provides a feature for users to create reminders. Once created, the reminders can be viewed and also removed when required. This allows the user to keep updated about the events or tasks that need to be completed.

* *create reminder*

![create reminder 1](https://media.github.ncsu.edu/user/22704/files/f64da74b-6f72-44ab-97e9-8cd485fa5037)

![create reminder 2](https://media.github.ncsu.edu/user/22704/files/433e4647-59d8-47fe-9b28-b65b3bc52d5e)

* *show reminders*

![show reminders](https://media.github.ncsu.edu/user/22704/files/73bf41e2-1395-4999-8fe9-e7c527e427f7)

* *remove reminder*

![remove reminder](https://media.github.ncsu.edu/user/22704/files/cf348ecf-39a7-41ad-87b0-6c2057301f17)

During the specified date and time, the reminder is displayed as follows:

![reminder alert](https://media.github.ncsu.edu/user/22704/files/71196086-c422-427d-a756-6fa809e9edbb)

=> **Scheduling a Meeting**

The main features of this use case includes:

1. *create meeting*
2. *show meetings*

The bot enables the users to schedule meetings by specifying the name, description and duration (start and end date, start and end time). These meetings are updated on the users Google Calendar account. Additionally, these meetings can be viewed on the channel as well as the calendar by entering the "view meetings" command.

* *create meeting*

![create meeting](https://media.github.ncsu.edu/user/22704/files/221cb916-78cc-43d1-8b1d-fbd8a3d43853)

* *show meetings*

![show meetings](https://media.github.ncsu.edu/user/22704/files/13fab4ab-8b9b-45e0-8fc1-d588a5c2b6d3)

=> Automatic Reminders for Github Issues

Automatic reminders are set for Github issues that are newly created. Ideally, reminders are displayed 3 days after issue has been created but for testing purpose, it will be displayed after a minute (on Team 24's Channel).

![image](https://media.github.ncsu.edu/user/22704/files/ea452ce8-2000-4e5e-b062-54842fb4cfd9)

Note: If the Github issue is closed before the reminder is displayed, the reminder itself gets deleted.


### Reflection on Development Process and Project

Reflection and consistent improvement is one of the key aspects of software development. 


Through the course of the bot development, various software development practices were rigorously followed. The prescribed milestones provided high-level goals whilst also giving the freedom to implement them. The milestones also provided a structure to the bot development which ensured the team was able to manage the timely deliverables. The incorporation of milestones was particularly appreciated during the initial stages of the development wherein the team was able to iteratively define and decide the processes and technologies (such as platform, tools) that the PAM Bot would eventually incorporate.

* *Design Milestone*:

The first milestone was critical in setting up the foundation of the PAM-BOT. The designing of usecases(and other associated UML diagrams) provided a lucid image on how we expect our bot to function. The incorporation of wireframes provided a basic idea about the bot layout and it's iteractions. The storyboard designs provided us an opportunity to understand the bot, both as a developer and end-user.

What we achieved: Was able to understand what problem our bot solves and how we expect our bot to address these issues.

* *Bot Milestone*:

In this milestone, the team began working on all phases laid out in the design milestone.

One of the most important components of software testing is to create a test plan. The team carried out software testing throughout the entirety of the project.
Functional testing was used to ensure that each module of the project is operating as expected, and fulfilling the requirements. Moreover, it allowed us to detect bugs at the early stages of the software development. 

Mocking was primarily used during unit testing, so that external dependencies were not a constraint to the test phase. Mocking allowed the testing to start early, since all units of the project can be carried out in parallel without waiting for all modules of the application to be entirely ready.

* *Process Milestone*:

The team employed a hybrid approach of "Extreme Programming (Core practice) and Corollary practice" . 

We employed a few corollary practices such as "Team Continuity" and "Shared Code". Team members were encouraged to provide constructive criticism which furthered the development of the PAM-BOT. 

The incorporation of the Scrumban approach meant that the work was split into small shippable deliverables. The Kanban workflow facilitated a visual workflow management. The card-like task prioritizing ensured that the each individual's role was well defined. This also allowed the management of the collective work of the team.

* *Deployment Milestone*:

The culminating milestone provided a comprehensive overview of the BOT. Seeing the deployed bot allowed us to look back and better appreciate the software practices we employed throughout the bot's development. Creating the various acceptance tests allowed us to get into the end-user's mindset and work around the various edge-cases and error control mechanisms.

### Limitations and Future Work

* *Limitations*:

1. Our bot focuses on increasing an individual's productivity and hence currently the GitHub API calls that are being made to close, create, and show issues can only be done on repositories that are owned by the user. However, the user will be able to see member and owned repositories but access only owned repositories. 

2. Our bot depends on GitHub a bit more than desired as GitHub API calls have a tendency to fail often over a long period of time (From our observation over the entire project). In order to ensure that the username in GitHub is the same as the user's name in the Firebase Database, an API call is being made to get the user ID from GitHub. If GitHub is down when a new user is using the bot, the user may not be registered to the database which is something we would look to fix. However, all other functionalities will execute normally even when servers are down (eg. to-do list, reminders, meetings, etc.)

3. In order to set automatic reminders for newly created Issues on owned GitHub repositories, a cronJob (hits the API every 5 seconds) is set up that makes an API call to check if there are any new issues in all the owned repositories. This API call returns a success or a failure message. If the servers are up and running, the issues from the repositories are returned with a success code otherwise an error is caught and is printed to the Mattermost chat server (To the Team-24 Channel). This print would happen every 5 seconds since it is the exception caught as pat of the cronJob that sets out every 5 seconds.


* *Future Work*:

1. In order to increase the Team's productivity further, we would like our bot to act as a scrum master. The bot would send a message at a specified time every morning of the week to every channel ID/ user part of the Team (eg. members of Team 24) asking them to give thier summary as how they would in a scrum meeting. The bot would collect the replies from the users and post to the the Group channel (eg. Team 24 Channel) for everyone to get the summary of the scrum meeting. This would be ideal especially in these times where remote working is becoming a norm. This would also reduce the necessity to get on call and would continue the tradition of frequent/ daily scrum meetings amongst teams. The summary can also be stored for reviewing progress and performance of the individuals.

2. We would extend this bot to access owned as well as member repositories to create, show, and close issues. Currently the bot can show repositories that a user owns and is a member of but can only make changes with respect to issues on repositories that the user owns. This could be changed to owned and member repositories as this means Team projects/ repositories can be accessed and all users can create, close, and view the Team's GitHub issues for different repositories.

3. We could also include the concept of Conversational Aritficial Intelligence and empower our bot to do more complex tasks and develop the ability to understand human language. Keyword based querying would be reduced and natural language understanding could be increased. It would be easier to integrate user authentication with such a bot.

