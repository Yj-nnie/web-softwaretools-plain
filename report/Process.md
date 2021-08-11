# Group Working

# Team Roles

# Sprints

# Continuous Integration

Our team uses Git for the software project development. Specifically, we use The Centralized Workflow, which is a great Git workflow. The Centralized Workflow uses a central repository to serve as the single point-of-entry for all changes to the project. The main default development branch is called **dev**, and all changes made by members are committed into this branch.

The design time of our project is only two weeks. In order to improve efficiency, team members are required to work at the same time in a short period of time. Git can provide each team member with their own local copy of the entire project, which gives each team member a isolated working environment. We can add and modify any of our own work in the local repository without taking into account the content of other members’ work.

<p align="center">
  <img src="https://github.com/Yj-nnie/web-softwaretools-plain/blob/YingDuan/images/git.png" width="850"/>
</p>
<div align="center">
  <em>Figure 12: Continuous integration using git.</em>
    <br/><br/>
</div>


### 1. Create individual branches

We decomposed the project into a number of different work content, and each member is responsible for the corresponding part. We cloned the initial repository and create our own branch. In this way of branching, everyone can work independently and manage each other to check each other's progress, and will not confuse everyone's work content.

### 2. Create content

On Dairy scrum, we discuss the next stage goal and distribute tasks. Then we add our own work content under our respective branches. We use the standard Git commit process to make changes: edit, stage, and commit. In this process, we do not care too much about the changes in **dev** branch.

### 3. Pull request and review

After completing the development of a feature or the writing of a whole paragraph report, we all required to submit a **pull request** to merge the code of our respective branches into the **dev** branch. Then, the request content would be reviewed by the team’s manager (Jun) and other members. They mainly charged of the code and report quality and the conflicts resolving (Conflicts would be automatically displayed on GitHub when we submit a pull request, which is why we choose to do so). The code would be merged into the **dev** branch until the content was no need to modify.

### 4. Track of progress

After completing a stage of development, we usually used **git rebase** to pull the code from **dev** branch to our own branch. This is a good way of following up the progress of the project.

### 5. Testing

We set up a **test** branch specifically for testing functions. In the early stage of development, in order to use the **GitHub Pages** function to facilitate unit testing, we created a new repository to store the code of our developed functions, so that we can access our project online (https://luming-liu.github.io/) and every member can see it and test it. The only disadvantage is that we need to manually upload the code each time, which is very inconvenient and wastes time.

So we changed our testing way by using **docker**. The only thing the tester needs to do is switch to the **test** branch and type the command **docker-compose up -d** in the terminal. Then he can easily test functions by visiting http://localhost:8080/.

### 6. Release

When the work content does not need to be modified and all testing tasks have passed, we merged the **test** branch to the **main** branch and tagged it as 1.0.0 version for production environment.
