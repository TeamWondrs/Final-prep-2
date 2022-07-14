# Final-prep-2

Final preparatory work for Java 401d12

## Requirements
-- -
### Pitch #1

_**LeChef**_  

**Summary of idea:** 
- An app that reveals closest location of foods and recipes based ingredients

**What problem or pain point does it solve? People love food! and so does this app.**  
  - It reveals nutrition, and places with types of food. for example chicken breast is a priority 
to stay lean and app finder finds places with those ingredients chosen.  

**Minimum Viable Product (MVP) definition.**
- Main activity - has buttons that hae on click.
- RecipeFinder - finds an ingredients based on saved data.
- RestaurantFinderActivity - finds the nearest location using maps or satellite app.


-- -
### Pitch #2

**BetterMe**  

**Summary of idea:**  

**What Problem or pain point does it solve?**  
- BetterMe gives new and regular gym users a place to record their BMI and display a history log that shows a workout streak Mon-Fri.  
- Provide its users with motivational quotes to keep them fired up and ready to train.


**Minimum Viable Product (MVP)**

**Feature Task 1:**
- Fitness App record the day's workout with body weight (BMI POSSIBLY, measurements)

**Feature Task 2:**
- History log that shows all workouts(calendar)

-- -

### Stretch Goals

**Feature Tasks:**

1. Encouraging quotes API

2. Provide Workout Routines Mon-Fri. (Ex: 3x135);

3. Shows which muscle groups are fatigued/worked out. 

4. Show Recommended rest days

5. Show the nearest location of gym

6. QR code scan foods and give foods information via API(recommended protein intake based on users height and weight)

7. Implement share to social media that compare streaks and toasts the results to facebook(accountability feature).

8. Facebook SignON

9. Sample videos of workouts of how to do the workouts (API). properly do squats, etc. hard code the videos

10. Automate these Feature Tasks.

11. Provide a selection of customized workout based on training goal(Mass gain/Weight Loss/Build Lean Muscle)

12. GPS feature that shows distance travelled/location travelled/speed travelled.

13. Encouraging quotes API

14. Shows which muscle groups are fatigued/worked out.

15. Show Recommended rest days

### Cooperation Plan

What are the key strengths of each person on the team?

Michael:

1. Project management.
1. Self motivated.
1. Availability.

Chuck:

1. UI Design, layout, and styling.
1. Teamwork.
1. Paired programming.

Abdulahi:

1. Collaborative design and development.
1. Availability.
1. Developing skills of others (paired programming, code review, etc).

Jon:

1. Git and GitHub management and support.
1. Project management.
1. Developing skills of others (paired programming, code review, etc).

### How can you best utilize these strengths in the execution of your project?

Michael:

- Manage tasks and project flow.

Chuck:

- Drive design and overall look-and-feel of the App.

Abdulahi:

- Java SME. Every effort will be made to assist with code issues or complexities.
- Help drive design and overall look and feel.

Jon:

- Set up and manage GitHub project and act as the Git SME.
- Drive unittest planning, development, and execution.

### In which professional competencies do you each want to develop greater strength?

Michael:

1. Communication.
1. Skill-oriented programming e.g. write more code to gain deeper knowledge.

Abdulahi:

1. Communication.
1. Creativity.

Chuck:

1. Implementing Java code.
1. Software / unit testing.

Jon:

1. Implementing Java code.

### What platforms will you use to communicate (ie. Slack, phone …)?

Slack
Remo
Email

### How often will you take breaks?

We will shoot for a maximum 2 hours between breaks.

Of course, breaks will be taken as needed, and at natural stop/pause points in each of our individual work.

### What is your plan if you start to fall behind?

1. Meet as a team.
1. Evaluate current tasks and upcomming tasks.
1. Evaluate MVP and trim or adjust as appropriate.

### How will you communicate after hours and on the weekend?

Slack

### What is your strategy for ensuring everyone’s voice is heard?

Everyone agrees that when they feel that one of us has not spoken up, or had a fair chance to pitch in on the conversation, we will call on that person and ask them specifically for what they think, so they are prompted to contribute to the conversation.

### How will you ensure that you are creating a safe environment where everyone feels comfortable speaking up?

We fully agree that a safe working and conversational environment is key to a successful project, and team experience. We agree to be thoughtful, courteous, and engaged.

## Work Plan

Explain your work plan to track whether everyone is contributing equally to all parts of the project, and that each person is working on “meaty” problems. This should prevent “lone wolf” efforts and “siloed” efforts.

NOTE: While researching and experimentation is always encouraged, writing and/or committing code to the project on your own during non-working hours or over the weekend is never acceptable. This puts the entire project at risk. Be explicit in calling out your work hours and the distribution of tasks.

### How you will identify tasks, assign tasks, know when they are complete, and manage work in general?

We we have meetings to determine who wants to work on what tasks, decide what tasks need to be worked on, etc.

From there, everyone agrees to keep the tasks that they are working in (individually and with others, as assigned), so that the entire team can look at the task board at any time and have a good idea as to what everyone is doing, and what work still needs to be assigned and or complete (abandoned, etc).

### What project management tool will be used?

We will use Trello for task tracking.

## Presentation Deck

Make a single copy of the Presentation Deck Template. Share your copy will all team members, so everyone is working from the same file.

(TBD)

## Schedule your practice session

Work with your instructor to pre-schedule an date and time for your “practice run” of your presentation. This should either be an exact time, or a short window of time designated by your instructor. Plan for a 30-45 minute meeting during the class session before your actual presentation to allow time for both your practice run and feedback from the instructional team.

## Git Process

Plan out what your team’s Git workflow looks like for coding tasks.

### What components of your project will live on GitHub?

Everything will live on GitHub.

### How will you share the repository with your teammates?

We will create a GitHub Team/Organization with a managed repository to restrict PR's and PUSH operations to main and a working branch (to be named later).

### What is your Git flow?

1. If the branch already exists in GitHub: PULL to your local.
1. Every time a PR is merged with the working branch: PULL to your dev branch.
1. Every time *your* PR is merged with working branch: PULL to *your local* working branch before you create a new dev branch.
1. If you create a PR and GitHub shows there will be merge conflicts *it is your job to fix these conflicts*. However, you are not expected to do this alone. Ask the team or the person whose code yours conflicts with to determine what should be kept, then *commit the changes*, and push to the PR to update it, then Approvals and PR Merge should be done.

### How many people must review a PR?

At least 2, although more than 2 is helpful to the entire team so we all stay synch'd with our project.

### Who merges PRs?

Any *other* team member than the one who owns the PR.

### How often will you merge?

PRs will be merged as necessary, as a team effort of at least 3 members.

In the past we've tried to set a time for merging PRs, however it usually came about that there were times that a PR needed to be merged to unblock other development work, so the team would handle these on an as-needed basis.

The one thing we *will not do* is try to do a "merge party" right before we sign-off for the night. Instead, we agree to continue development in areas that would not otherwise be blocked. This way, we will not be "up all night, wanting to go home" while sorting out merge conflicts, bugs, or other issues related to the late-night PR.

### How will you communicate that it’s time to merge?

The team member that has work that is "ready for PR" will contact other team members indicating a mege is requested. The team members can then decide, along with the PR "caller" when and how to do the review and "merge party".
