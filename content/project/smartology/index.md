+++
title = "Designing an internal admin system"
date = 2018-12-24T17:21:53Z
draft = false
weight = 3

# Project summary to display on homepage.
summary = "This is a project I did with my previous employer on designing an internal dashboard for campaign management."

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []
categories = []

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++

## Overview

This was a project I did whilst working at Smartology. The company has its own internal system for managing client campaigns.

The project had strict time constraints, so we did not fully utilise the UX processes to get the data we require.

I was the lead UX designer and with permission, I will describe the work I did for the company.

## Project Brief

To create a dashboard for improving workflow processes, increasing efficiency and to support a new business model.

The dashboard’s main target audience will be the operations team, who uses the system for their daily campaign management tasks.

## Planning

The company had little experience with UX so I used the UX framework to create an estimated project plan. The purpose was to show the different tasks for gathering different information and for managing progress of the project.

## Research

For research, I focused on gathering insights into the team's workflows with the current system. It was a small team, so I did interviews to gather qualitative data. The purpose was to find out what pain points and requirements these users may have for the system.

The current dashboard had the following user groups:

* Primary users  
  * Account managers
  * Front-end developers
  
* Secondary users  
  * Finance
  * Sales

My main role was a front-end developer and we work with the Account managers. I was already familiar with both teams' workflow, so I interviewed our Finance and Sales team for insights.

### Interviews

The interviews highlighted the major following points:

* The current dashboard not entirely suitable for Sales and Finance because they needed certain data which are not available for them to do their tasks.
* They have to do more manual tasks especially for Finance as they require campaign data for billing and for other tasks such as company forecasting.
* For Sales, there are no place for them to store client information within the internal dashboard. This suggests that different people will have different information on campaigns.

When I shared these insights with the team, automating manual tasks became one of the major focus for the new system e.g. any manual tasks that can be easily automated had high priority if the company had the objective to improve efficiency.

### Business goals and user requirements

I created a Google Sheet for the team to add any feedback they have for the new system. I realised that this was not the best approach because it allows users to provide solutions with no context of the new system. Some feedback was also vague and biased as they focused on the individual's experience. However, because of time constraints and limited resources, I had to create the list for the team to review. It helped the team to prioritise requirements and estimate complexity for the first phase of the project.

I wasn't able to gather feedback from all team members but the list contained duplicates or similar points. Since the team wasn't familiar with the UX process, it was interesting to observe different people's reaction on providing feedback. Some team members felt that their input wouldn't be relevant because they don't consider themselves to be the main target user. However, we encouraged everyone to give feedback as it can bring value to the company.

After voting, we grouped the list into categories based on the number of votes e.g. high votes means top priority, low votes mean low priority.

{{< figure class="course-photos text-center" src="imgs/grouping-requirements.jpg" title="Categorising requirements" >}}

### Personas

I have created personas that focused on the workflows for achieving the user's goal. The personas are different roles within the company that will use the new system at different stages of the campaign setup process. I had the personas reviewed by the team so they reflect the different roles as close as possible.

The personas may seem basic but we felt it provided sufficient information for us to progress to the next phase of the project.

{{< figure class="course-photos text-center" src="imgs/persona-primary.jpg" title="One of the primary persona of the system" >}}

{{< figure class="course-photos text-center" src="imgs/persona-secondary.jpg" title="One of the secondary persona of the system" >}}

## Flow diagrams

I have created flow diagrams that covers the whole campaign setup process. All the diagrams have received many iterations based on user feedback.

The flow diagrams have provided useful insights on the different processes each team has. Different teams found them useful as it allowed them to see the different tasks involved. This was also the first time I've used Lucid Charts for creating the flow diagrams.

We also felt we can use the diagrams to introduce new/existing team members on the whole campaign setup process. This helped individuals to better understand how different processes work e.g. we cannot bill clients unless we have the correct contact details.

It was also interesting to see current team members considering their own processes and whether they feel it make sense to them (and if they have been following the correct steps for their processes).

## Ideation

For this project, I ensured that our main users felt involved and have ownership of the project by encouraging feedback and updating the progress.

Instead of speaking to each individual, I organised a few group sessions for ideation. I wanted all participants to provide feedback, so I used the "How Might We..." and Brainwriting method I learnt from my course.

I felt that calling the sessions as "brainstorming" to be too formal and intimidating so [I researched alternative names](https://www.trainingzone.co.uk/community/discuss/is-there-an-alternative-word-phrase-for-brainstorm). We agreed to use "Suggest-fest" for the humour and meaning it creates for people i.e. a session where they share ideas for something. We also based the name change on using the "How might we..." method, where specific topics were used to create context to the multiple "How might we..." questions we planned.

{{< figure class="course-photos text-center" src="imgs/hmw-planning.jpg" title="Planning 'How might we...' questions" >}}

### HMW and Brainwriting

We had a big group, so [I used a variation of the Brainwriting method](www.andyeklund.com/brainstorm-technique-brainwriting/) that allowed me to collect feedback quickly.

We planned our sessions to be one hour with at least three questions to cover. Participants were given sheets of paper with a printed 3x3 table and the question to answer. Everyone was given two minutes to read the question and then three minutes to write their ideas on the sheet. After the time limit, everyone puts their sheet on the center of the table and takes another sheet from another participant. This process is repeated but the participant can now either feedback on the initial row of ideas or share new ideas on the new sheet. Once all the rows are completely filled in, the sheets are collected for review.

We summarised all feedback into a Google Document as a reference for the next phase of the project.

{{< figure class="course-photos text-center" src="imgs/ideation-feedback.jpg" title="Feedback from Ideation" >}}

## Wireframes

For wireframing, we researched competitor dashboards for inspirations. The purpose was to understand the user journey for creating campaigns and what information are required from the user.

This was a challenging exercise because we didn't have all the information to connect the different wireframes together.

{{< figure class="course-photos text-center" src="imgs/wireframes.jpg" title="Our wireframes with some feedback notes" >}}

## Conclusion