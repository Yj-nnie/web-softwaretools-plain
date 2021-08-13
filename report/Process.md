# Contents
- [Group working](Process.md#Group-Working)
  1. [Waterfall](Process.md#1-Waterfall)
  2. [Agile](Process.md#2-Agile)
  3. [The Key Difference between Waterfall and Agile](Process.md#3-The-Key-Difference-between-Waterfall-and-Agile)
  4. [Our Choice of Methodology](Process.md#4-Our-Choice-of-Methodology)
 
- [The Agile Project Management with Scrum](Process.md#The-Agile-Project-Management-with-Scrum)
 
- [Our Sprints Overview](Process.md#Our-Sprints-Overview)
  1. [User Story Creation](Process.md#1-User-Story-Creation)
  2. [Details of Our Sprints](Process.md#2-Details-of-Our-Sprints)
  3. [Daily Communication Methods and Tools](Process.md#3-Daily-Communication-Methods-and-Tools)

- [Team Roles](Process.md#Team-Roles)

- [Continuous Integration](Process.md#Continuous-Integration)
  1. [Centralized Workflow](Process.md#1-Centralized-Workflow)
  2. [Featured Branch Workflow](Process.md#2-Featured-Branch-Workflow)
  3. [Gitflow Workflow](Process.md#3-Gitflow-Workflow)
  4. [Our Git Working Style](Process.md#4-Our-Git-Working-Style)

- [References](Process.md#References)

# Group Working
Before the start of any group project, it is important to decide which project management framework and concept to adopt, which determines the future development method of the project, organizational changes and other important aspects.

Agile and waterfall are the two mainstream project management methodology. Agile and waterfall often represent an irreversible fork in the road for any initiative. Generally speaking, in the same project, members must choose one of these concepts as the project management framework. 

## 1. Waterfall
Waterfall is a traditional project management method. Waterfall development usually spends a lot of time at the beginning to formulate very detailed plans and requirements, and then follow the plan step by step. In general, waterfall management is mainly a linear process. The steps include Requirements Determination, Design, Implementation, Testing, Deployment and Maintenance. All of the requirements for each step is completed before the next begins. All requirements for each step are completed before the next one starts.

<p align="center">
  <img src="https://github.com/Yj-nnie/web-softwaretools-plain/blob/YingDuan/images/waterfall.PNG" width="800"/>
</p>
<div align="center">
  <em>Figure 1: The Waterfall workflow.</em>
    <br/><br/>
</div>

### Advantages of Waterfall 
- It works well for smaller size projects where requirements are easily understandable.
- Precise project planning and fixed deadlines.
- A predictable and well-specified final product.
- Clear roles and responsibilities among members

### Disadvantages of Waterfall 
- It is not an ideal model for a large size project.
- Lack of flexibility after project planning.
- If the market demand or technological environment changes, the project cannot meet the latest market demand.
- There are fewer opportunities to correct the project.

## 2. Agile
Agile project management is iterative, which means that agile is completed in stages (sprints), and each sprint builds and improves the lessons of the previous sprint. At the beginning of the project, agile requires only a rough plan and idea for the project, and then as multiple sprints are continuously completed, members can continuously re-evaluate and correct the new requirements and results of the project, that is to say, Agile development is a process in which the requirements are expected to change and evolve. The larger project is broken down into smaller parts so that the project can progress in each sprint.

<p align="center">
  <img src="https://github.com/Yj-nnie/web-softwaretools-plain/blob/YingDuan/images/agile%201.png" width="500"/>
</p>
<div align="center">
  <em>Figure 2: The Agile workflow.</em>
    <br/><br/>
</div>

### Advantages of Agile
- The project is flexible, and the content of the project can be continuously improved and revised as the project develops.
- Strict rhythm, flexibility of deadlines.
- Frequent updates and increased user value.

### Disadvantages of Agile
- Susceptible to a lack of focus and knee-jerk reactions from sprint to sprint.
- Loose planning can lead to unpredictable finished products and date delays.

## 3. The Key Difference between Waterfall and Agile
- Agile allows the requirements of the project to be changed and further specified during the development of the project, but once the project starts, waterfall does not change the scope of the requirements

- Agile method is more flexible, while waterfall is a structured project development method

- Waterfall is a liner sequential life cycle model whereas continuous iteration is the core feature of agile.

<p align="center">
  <img src="https://github.com/Yj-nnie/web-softwaretools-plain/blob/YingDuan/images/tra%20agile.png" width="600"/>
</p>
<div align="center">
  <em>Figure 3: The key difference between Waterfall and Agile.</em>
    <br/><br/>
</div>

## 4. Our Choice of Methodology
The working method of our group follows the agile management method. This is mainly based on the following reasons:

- This project needs to add new functions to the petstore site. At the beginning of the project, we listed several new functions that can be added, but the specific implementation of several new functions and the final effect of the new functions are uncertain. Therefore, we need to continuously adjust our project goals based on the results of the work during the subsequent development of the project. Based on this, the agile concept is more suitable for our project management.

- In addition, our project preparation time is only two weeks. The short preparation time requires us to decompose the complex project into multiple work parts to be completed by different members. Team members need to regularly check and improve each decomposed work product. Consequently, we decided to adopt agile concepts at the beginning of the project.

# The Agile Project Management with Scrum
Agile development is a development method and concept. There are many models for agile development, such as Scrum model, XP extreme programming and so on. The Scrum model is the most used development model in agile development, accounting for more than 66%. Our team uses the agile development framework of scrum.

## Scrum & Sprint
When using scrum to implement agile development, the entire project is divided into several small work parts, and each small part is called a “sprint”. This entire project is equivalent to scrum. A sprint usually takes one to three weeks. All the team members need to do is to repeat the sprint until the product features are fully developed, and finally get the project version that can be released. This work framework enables the team to accurately deliver products that meet the latest market needs of customers.

Every sprint has a goal to complete. Sprint is equivalent to an agile cycle. We have to complete in a sprint cycle, including, design, build , test, review and other steps.

<p align="center">
  <img src="https://github.com/Yj-nnie/web-softwaretools-plain/blob/YingDuan/images/sprint%201.png" width="700"/>
</p>
<div align="center">
  <em>Figure 4: The key difference between Waterfall and Agile.</em>
    <br/><br/>
</div>

Under the Scrum framework, the development of the project is mainly divided into the following five stages:

- Collect the user story, which is a way of describing a feature set. Then the product owner determines some of the features that the product needs to develop based on the user stories, and proposes the highlights of the product to form a product demand list -product backlog.
- In the sprint planning meeting, all members of the team discuss the top priority user story and assign different tasks according to the abilities of the members. At the same time, this meeting should also determine the user need that need to be developed for the next sprint.
- Make a sprint backlog according to the sprint planning of the previous stage, which a list of user stories that have been commits to the next sprint. The user story of the sprint backlog is what needs to be considered in the next phase of the sprint.
- Team members develop and complete the user requirements in the sprint list in a short time. During each sprint, team members conduct daily scrum basically every day. In the meeting, team members brief each other on their work progress and raise their own problems.
- After the completion of each sprint, team members need to hold a sprint review. During the meeting, members review the entire sprint process, show the functions that have been developed, discuss and reflect on the mistakes that occurred in this sprint, and avoid similar mistakes in the future.

<p align="center">
  <img src="https://github.com/Yj-nnie/web-softwaretools-plain/blob/YingDuan/images/sprint%20meet.png" width="500"/>
</p>
<div align="center">
  <em>Figure 5: The key difference between Waterfall and Agile.</em>
    <br/><br/>
</div>

# Our Sprints Overview

## 1. User Story Creation
As mentioned before, when using the Scum framework to develop a project, we must first collect user stories, which is the smallest and very critical unit of work in the Scrum framework. A user story is a short, informal description of the feature of a project, usually from the user’s perspective. Once the team agrees on a user story, this feature will be added to the product backlog and used as a goal for the subsequent sprint.

User stories are often expressed in a simple sentence, structured as follows:
"As a [persona], I [want to], [so that]."

<p align="center">
  <img src="https://github.com/Yj-nnie/web-softwaretools-plain/blob/YingDuan/images/user%20concept.PNG" width="500"/>
</p>
<div align="center">
  <em>Figure 6: The structure of user story.</em>
    <br/><br/>
</div>

According to the above structure, at the stage of sprint 1, as shown in the table below, we have constructed user stories. The information in the “Notes” column shows the result of the member meeting discussing whether to agree to petstore's construction of the feature. The “Sprint” column indicates in which sprint phase the function mentioned in the user story was built. Among them, for the needs mentioned by the ninth user, our members do not intend to incorporate this feature into the project, because we think it is unreasonable to judge someone’s best pet selection based on a quiz.

<p align="center">
  <img src="https://github.com/Yj-nnie/web-softwaretools-plain/blob/YingDuan/images/user%20story.png" width="900"/>
</p>
<div align="center">
  <em>Figure 7: User story creation.</em>
    <br/><br/>
</div>

## 2. Details of Our Sprints 
During the entire project development phase, our team carried out a total of five sprints. Because our design time is only two weeks, we have shortened the time of each sprint. The duration of the first four sprints is basically 2 to 3 days. The main content of each sprint is to establish and improve the 1 or 2 features that need to be established for the project. During the sprint, the members' working attitude was very positive. In the end, we successfully completed the first four sprints and established most of the functions of petstore. After the fourth sprint is over, the focus of our fifth sprint is mainly to improve the report of the project and to check leaks and fill the vacancy in the function of the project. The duration of sprint 5 is one week. The following are the details of our work during the sprint:

### Sprint 1  (7.27-7.29)
Targets
- Find the best project management methodology and tools for team project work
- Assign tasks according to members’ abilities and determine the responsibilities of members
- Each member creates his or her own working environment to facilitate the work
- Discuss the functions that petstore needs to develop on sprint planning

Outcomes
- After discussion, our team decided to follow agile management in the way of work, using the scrum agile development framework
- Members successfully assigned group tasks
- Members have established their own accounts and created their own branches on github
- Create a product backlog of user requirements list based on user stories and discuss what functions need to be added to petstore

### Sprint 2  (7.30-8.1)
Targets
- Start writing the content of the report
- Conduct user surveys and establish a sprint backlog
- Realize most of the features of the user creation and authentication system

Outcomes
- Initially complete the background content of the GitHub document
- Establish a user questionnaire and conduct a survey. Members believe that it is clear that pet management, classification and user order functions will be added to the next sprint 
- In terms of realizing the functions of user creation and authentication system, the following aspects are mainly realized:

  Add user registration, login, and logout functions
  
  Add international plugin content
  
  Realize the logout function of the user account
  
  Add the name of the account and login button on the homepage
  
- Realized the preliminary layout design of the website

### Sprint 3  (8.2-8.3)
Targets
- Realize pet classification function
- Realize pet management function
- Preliminary realization of the user order feature
- Project report writing

Outcomes
- Realize the function of displaying pets by category and pet availability status on the website, mainly to achieve the following aspects:

  Add pet category, such as dog, cat, bird, fish, reptile, insect and so on

  Add the pet's availability status, including available, sold and pending

- In terms of pet management functions, the following aspects are mainly realized:

  Administrators can add new pets to store inventory

  Administrators can update various information about existing pets

  Administrators can delete existing pet items

- Allow registered users to implement the function of placing orders online, including:

  Users can click the button to buy now
  
  Add user's order interface
  
  Successfully implement the function of creating and canceling orders for registered users

- Report writing including ux process and other part
- It was discussed at the meeting that the next sprint should add user authentication function and make improvements in pet search and management.

### Sprint 4  (8.4-8.5)
Targets
- Realize user authentication function
- Improve the function of pet search
- Improve the function of pet management
- Improve the administrator's function of order processing

Outcomes
- In terms of user authentication function, realize the ability to add different users to some functions according to the three types of users
- In terms of pet search display, add a new function: complete the display of the number of pets that can be sold
- In terms of pet management, add a function that allows the administrator to add photos of pets
- In terms of order function, improve the function of administrators to set user orders
- Discuss the functions to be implemented in the next sprint. The team mainly discussed whether to add homepage flash cartoon and personality and perfect pet quiz to the petstore.

### Sprint 5  (8.6-8.13)
Targets
- Project report writing
- Check and improve various features 
- Perform user testing

Outcomes
- Write and improve the content of the report according to the implemented features
- For online orders, the following two aspects have been changed:

  Considering that petstore is a small pet shop, the number of pets of a single breed is very limited, so the purchase pet interface does not set the quantity window, that   is, clicking the button "buy" will default to an order

  Because the delivery range of pet shops is limited, in order to express more accurately, change "confirm shipping" to "confirm sending"

- In terms of user authentication, a function that allows users to update their information has been added.
- Further optimize the layout of the website homepage and add a carousel.

## 3. Daily Communication Methods and Tools
### Meeting Structure and Content
Microsoft teams is a tool for our team members to conduct meetings. Our team held a total of six meetings throughout the two-week project development phase.[The meeting log](https://github.com/Yj-nnie/web-softwaretools-plain/blob/YingDuan/meeting%20log/meeting%20log.pdf) recorded our attendance at each meeting and the content of the meeting in detail.

<p align="center">
  <img src="https://github.com/Yj-nnie/web-softwaretools-plain/blob/YingDuan/images/teams%209.gif" width="600"/>
</p>
<div align="center">
  <em>Figure 8: The group's activity on Teams.</em>
    <br/><br/>
</div>

According to the scrum framework, we conduct three types of meetings in a sprint:
- Sprint planning: members plan what goals should be accomplished in this sprint. Assign different tasks according to the abilities of the members.
- Daily scrum: members share their work problems with each other, and other members need help to solve the problems.
- Scrum retro requires members to review the entire sprint process and reflect on the mistakes made in this sprint.

But because our project preparation time is very short, and the duration of each sprint is very short, our meeting basically integrates the content of the above three kinds of meetings. And the structure of our meetings are always:
- Members update and display their work content in a timely manner, and members put forward work opinions among each other
- Develop project goals for the next sprint
- For difficult work problems, 2-3 people start a meeting in pairs and help each other complete tasks.

### Increased Transparency and Integrity of Communication
The daily meetings held in Microsoft teams cannot meet the frequent communication needs of members. In order to improve the transparency and integrity of communication between members, we daily use WeChat as the main communication tool outside of the meeting. We have established a five-person chat group called "petstore fighting". All communication (except for task-related small meetings) is conducted in our WeChat group, which includes:
- The exchange of project working documents between members is carried out in the WeChat group

<p align="center">
  <img src="https://github.com/Yj-nnie/web-softwaretools-plain/blob/YingDuan/images/Wechat.jpg" width="600"/>
</p>
<div align="center">
  <em>Figure 9: File exchange between members.</em>
    <br/><br/>
</div>

- Evaluation of the work of team members. When a member completes a job, other members will write feedback to give feedback to help the content of the work better improve

<p align="center">
  <img src="https://github.com/Yj-nnie/web-softwaretools-plain/blob/YingDuan/images/wechat2.png" width="600"/>
</p>
<div align="center">
  <em>Figure 10: Work feedback among members.</em>
    <br/><br/>
</div>

- When there are some minor changes in project decision-making, members will post messages via WeChat.

# Team Roles
Members choose what they are good at according to their areas of expertise. In the first group meeting, we successfully assign project tasks according to the requirements. Luming Liu is good at front-end and back-end, so he is mainly responsible for the functional construction of the project. At the same time, Ruiqing Du also assisted in the construction of part of the code. The other members are mainly responsible for writing project report. When some members encounter difficulties in their own work areas, other members will also help to complete this part of the work together. The following figure shows the contributions of various members in the project.

<p align="center">
  <img src="https://github.com/Yj-nnie/web-softwaretools-plain/blob/YingDuan/images/role.PNG" width="1000"/>
</p>
<div align="center">
  <em>Figure 11: Team Roles.</em>
    <br/><br/>
</div>

# Continuous Integration
Our team uses Git for daily work. Git has some working modes that can be used, including: centralized workflow, featured branch workflow, and gitflow workflow. In the development of project, developers can mix and match aspects from different workflows to meet the development needs of the project.

## 1. Centralized Workflow
The Centralized Workflow uses a central repository to serve as the single point-of-entry for all changes to the project. The only default development is called main, and all changes made by members are committed into this branch.

<p align="center">
  <img src="https://github.com/Yj-nnie/web-softwaretools-plain/blob/YingDuan/images/centralized.PNG" width="600"/>
</p>
<div align="center">
  <em>Figure 12: Centralized Workflow.</em>
    <br/><br/>
</div>

The advantage of Centralized Workflow is that it provides staff with their own local copy of the entire project, which gives each member a isolated working environment. However, a big flaw of Centralized Workflow is that it is the "maker of trouble and conflict" .Because if both developers make changes, the first developer who pushes the changes to the central database   can do so, but the second developer must merge the work of the first developer before pushing the changes up, so as not to overwrite the changes of the first developer. This mechanism leads to a bit of confusion in the whole system if there are too many developers, frequent submission of changes and merge conflicts. This is also the main reason why our team does not choose this workflow. 

## 2. Featured Branch Workflow
Feature Branch Workflow still uses a central repository. However, developers do not submit directly on the local branch, but create a corresponding new branch each time they start working on a new feature. This approach is to give each branch a clear and highly focused goal.

Feature Branch Workflow has two advantages for our members to refer to:
- Because all function development should be carried out in a dedicated branch instead of the main branch, this encapsulation allows multiple developers to easily handle specific functions without interfering with the central repository.

- In addition, Feature Branch Workflow can also use the pull request function, which is a way to initiate discussions among members around branches. They way gives members the opportunity to check the feature before it is integrated into the official project. Pull request make it easy for team to comment on each other's work. Once the pull request is accepted, the actual behavior of the publishing features is very similar to that in a centralized workflow. In short, the pull request function is a good way to encourage cooperation among members and simplify communication between members.

## 3. Gitflow Workflow
Gitflow Workflow is the same as other workflows. Developers work locally and push branches to the central repository. The only difference is the branch structure of the project. Git Workflow assigns very specific roles to different branches and defines how and when they should interact. In addition to establishing feature branches, it also uses separate branches to prepare, maintain, and document releases.

## 4. Our Git Working Style
The design time of our project is only two weeks. The main work content is to add some features to petstore and write project report. Therefore, we need to submit changes frequently in a short period of time. In order to prevent the system from becoming chaotic, as mentioned earlier, Centralized Workflow is not suitable for our working mode.

Our working style combines the characteristics of git workflow and feature branch workflow. Specifically, because our members have a clear division of labor, each member has its own project functions and parts, and the branching method of featured branch workflow provides us with a reference. But our branch is named after the role of the team member, not based on the function description, which is slightly different from the featured branch workflow. In addition, although our working model is not as complicated as git workflow, we have also adopted some features of this workflow method. For example, we have set up a test branch specifically for testing functions. The figure below shows the continuous integration using git of our team.

<p align="center">
  <img src="https://github.com/Yj-nnie/web-softwaretools-plain/blob/YingDuan/images/git.png" width="850"/>
</p>
<div align="center">
  <em>Figure 13: Continuous integration using git.</em>
    <br/><br/>
</div>

### 1. Create individual branches
We decomposed the project into a number of different work content, and each member is responsible for the corresponding part. We cloned the initial repository and create our own branch. In this way of branching, everyone can work independently and manage each other to check each other's progress, and will not confuse everyone's work content.

### 2. Create content
On Dairy scrum, we discuss the next stage goal and distribute tasks. Then we add our own work content under our respective branches. We use the standard Git commit process to make changes: edit, stage, and commit. In this process, we do not care too much about the changes in **dev** branch.

### 3. Pull request and review
After completing the development of a feature or the writing of a whole paragraph report, we all required to submit a **pull request** to merge the code of our respective branches into the **dev** branch. Then, the request content would be reviewed by the team’s manager (Jun) and other members. They mainly charged of the code and report quality and the conflicts resolving (Conflicts would be automatically displayed on GitHub when we submit a pull request, that is why we choose to do so). The code would be merged into the **dev** branch until the content was no need to modify.

### 4. Track of progress
After completing a stage of development, we usually used **git rebase** to pull the code from **dev** branch to our own branch. This is a good way of following up the progress of the project.

### 5. Testing
We set up a **test** branch specifically for testing functions. In the early stage of development, in order to use the **GitHub Pages** function to facilitate unit testing, we created a new repository to store the code of our developed functions, so that we can access our project online (https://luming-liu.github.io/) and every member can see it and test it. The only disadvantage is that we need to manually upload the code each time, which is very inconvenient and wastes time.

So we changed our testing way by using **docker**. The only thing the tester needs to do is switch to the **test** branch and type the command **docker-compose up -d** in the terminal. Then he can easily test functions by visiting http://localhost:8080/.

### 6. Release
When the work content does not need to be modified and all testing tasks have passed, we merged the **test** branch to the **main** branch and tagged it as 1.0.0 version for production environment.

## References
1.Agile Vs Waterfall: Know the Difference Between Methodologies - https://www.guru99.com/waterfall-vs-agile.html

2.Beginner's Guide to Agile with Scrum | Dennis Kayser - https://www.forecast.app/blog/beginners-guide-to-scrum

3.Comparing Workflows | Atlassian - https://www.atlassian.com/git/tutorials/comparing-workflows

4.Distributed Git - Distributed Workflows - https://git-scm.com/book/en/v2/Distributed-Git-Distributed-Workflows
