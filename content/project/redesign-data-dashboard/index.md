+++
title = "Redesigning a data dashboard"
date = 2018-12-24T17:21:53Z
draft = false
weight = 3

# Project summary to display on homepage.
summary = "A team project I did whilst working at Smartology. The focus was to redesign a data dashboard for campaign management."

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
  focal_point = "Bottom"
+++

## Overview

This was a project I did whilst working at Smartology. The company has a data dashboard for managing client campaigns.

We did the project in an agile environment with strict time constraints. Under these conditions, we could not fully utilise the applied UX methods to get all the data we require.

I was the lead UX designer and with permission, this project describes the work I did with the company.

<span class="text-emphasis">Images with sensitive information are not shown in this project.</span>

## Project Brief

To develop a new data dashboard for improving team workflow, increasing efficiency and to support a new business model. 

## Planning

The company had little experience with UX, so I created a project plan based on the UX framework I learnt from the [UX Playground project]({{< ref "/project/designing-interface-smart-devices/index.md" >}}). This has helped the team to have an overview of each process and for monitoring progress.

{{< figure class="course-photos text-center" src="imgs/ux-framework.jpg" title="UX Framework I learnt from the UX Playground project" >}}

Our focus was to improve the workflow and efficiency on campaign management, so the Operations team will be our main users of the system.

## Research

For research, I focused on the team's workflows with the current system. Our team was small, so I did interviews to gather qualitative data. This will help us discover what pain points and requirements users may have with their current workflow. 

The current system had the following user groups: 

* Primary users
  * Account Managers  
    Responsible for managing clients and their campaigns such as communication and reporting.

  * Front-End Developers  
    Deals with technical tasks in relation to campaigns such as designing and building ad creatives.

Both combined to be the Operations team and responsible for campaign launches.

* Secondary users 
  * Sales  
    Communicates and secure client contracts. 

  * Finance  
    Manages the billing of clients.

My main role was a Front-End Developer and we work closely with the Account Managers. I was already familiar with both teams' workflow, so I interviewed our Finance and Sales team for insights.

### Interviews

The interviews involved me talking to a representative from the Sales and Finance team about their daily job process. It has highlighted the following major points: 

* Not all data in the current system are available for both teams to do their tasks e.g. start and end dates of campaigns not available for billing or forecasting.

* There are more manual tasks for the Finance team, which requires them to create custom reports in Excel e.g. gathering and organising the required data for billing. 

* For the Sales team, they cannot store client information within the current system. This suggests that different people will have different information on campaigns e.g. from emails and meetings. Therefore, data in the system are potentially not up-to-date.

When I shared these insights with the team, automating manual tasks became one of the major focus for the new system. This means any manual tasks that can be automated had high priority as it relates to the company objective on improving efficiency. 

### Business goals and user requirements

I used Google Sheet for collecting feedback on the current system. I realised this was not the best approach because the team had no context of the new system i.e. what features it would have. 

Some feedback was also vague and biased because they focused on the individual’s experience. However, because of time constraints and limited resources, I had to create the list for the team to review. It has helped the team to prioritise requirements and estimate complexity for the first phase of the project. 

After voting, we grouped the list into categories based on the number of votes e.g. high votes means top priority, low votes mean low priority.

{{< figure class="course-photos text-center" src="imgs/grouping-requirements.jpg" title="Categorising requirements" >}}

With the team having no familiarity with the UX process, it was interesting to observe people’s reaction on providing feedback. Some team members felt that their input may not be relevant because they are not the main target user. However, we encouraged everyone to give feedback as it can help bring value to the company. 

### Personas

I have created personas based on the different roles within the company. They showcased how different users use the current system. I had the personas reviewed by the team to ensure they reflect the job roles as close as possible.

The personas may seem basic but we felt it provided sufficient information for us to progress to the next phase of the project.

{{< figure class="course-photos text-center" src="imgs/persona-primary.jpg" title="One of the primary persona of the system" >}}

{{< figure class="course-photos text-center" src="imgs/persona-secondary.jpg" title="One of the secondary persona of the system" >}}

## Flow diagrams

I have created flow diagrams covering the whole campaign setup process. All the diagrams have received many iterations based on user feedback.

Team members have found them useful for understanding other team’s workflow and as an introductory resource for new employees. This was also my first experience in using Lucid Charts for creating flow diagrams.

It was also interesting to observe how the current team members consider their own workflow, and whether they feel it make sense to them.

## Ideation

For this project, I ensured that the main users felt involved by encouraging them to give feedback. I organised a few group sessions for ideation and used the "How Might We..." and Brainwriting method. 

I felt that calling the sessions as "Brainstorming" to be too formal and intimidating so [I researched alternative names](https://www.trainingzone.co.uk/community/discuss/is-there-an-alternative-word-phrase-for-brainstorm). We agreed to use "Suggest-fest" for the humour and based on using the "How might we..." method.

{{< figure class="course-photos text-center" src="imgs/hmw-planning.jpg" title="Planning 'How might we...' questions" >}}

### HMW and Brainwriting

We had a big group, so [I used a variation of the Brainwriting method](http://www.andyeklund.com/brainstorm-technique-brainwriting/) for collecting feedback quickly. I planned our sessions to be one hour with three/four questions to cover. 

Process:

1. I handed out sheets of paper with a printed 3x3 table with the question to answer. 
2. I gave everyone two minutes to read the question and then three minutes to write their ideas on the sheet.
3. After the time limit, everyone puts their sheet on the center of the table and takes another sheet from the pile.
4. We repeated this process but the participant can now either feedback on the initial row of ideas or share new ideas on a new row.
5. Once the table is complete, I collected the sheets for review. 

We summarised all feedback into a Google Document as a reference for the next phase of the project.

{{< figure class="course-photos text-center" src="imgs/ideation-feedback.jpg" title="Feedback from Ideation" >}}

## Wireframes

For wireframing, we researched competitor dashboards for inspirations. The purpose was to understand the user journey for creating campaigns and what information the user may require. 

This was a challenging exercise because we could not gather sufficient information to create wireframes for the whole new system.

{{< figure class="course-photos text-center" src="imgs/wireframes.jpg" title="Our wireframes with some feedback notes" >}}

## Other Processes: Minor Involvement with UX

With the pressure of the team aiming for MVP and limited resources, I eventually switched back to being a Front-End Developer working on the day job. However, as the only person with UX experience, I assist the team with any UX deliverables required.

### UI Design, User Flows and Prototyping

For this phase, I worked with a Freelance Designer for about one to two months. I cannot share screens of the design as I did not create them. However, my role was to collaborate and support the Freelance Designer on creating a new design of the dashboard. It needs to show the end to end process of creating campaigns.

Our collaboration involved:

* Communicating with the team on requirements and priority
* Analysing the current dashboard and how Account Managers/Front-end Developers use it
* Me sharing insights on the workflow of the current campaign setup process
* Attempt to create new screens that can simplify any user flows
* Speak to relevant users for further insights especially for verifying what important data should be on the dashboard
* Attempt to create a high fidelity prototype with Invision and did user testing
* Iterate and make changes based on feedback

It was an enjoyable experience as I get to learn the process of the Designer. Creating a design for a whole system was no easy task, so it was normal for the both of us to feel mentally exhausted by the end of the day. Unfortunately, we could not create screens for some parts of the system because of insufficient research. However, we created designs for areas with high priority and the development team used them as a blueprint for starting their sprint.

Although the design was incomplete, it allowed the developers to have a reference on what they will create visually. It was also useful for the rest of the team to have an idea on what the future dashboard would look like.

### User Testing

I helped organise user testing sessions when the development team required feedback on features they are working on. I also offered advice to team members involved in interviewing or note taking for the sessions.

My process typically involved:

* Find out what needs to be tested and why
* Create tasks and user scenarios with relevant members
* Help simplify tasks if they were complex
* Create a test plan for interviewer and note taker with notes to aid their session
* Create a test plan for the user describing the scenario and instructions on the tasks they need to perform 
* Emphasise with the interviewer that they should always ask questions that does not prompt a "Yes" or "No" answer

This was quite a challenging process to teach to my team because there will always be unexpected situations e.g. broken equipment, internet not available, busy schedules etc. Personally, the most difficult part was advising the interviewer to not ask closed questions especially if they never did user testing.

## Conclusion

The main challenges for this project was to manage the communication and expectations of users. As the only UX Designer in the team, it was difficult to judge whether my decisions are correct for the project. However, I expressed that I am open to feedback and being flexible with my process.

It was interesting to observe the change in behaviour of my team members. The UX process allowed the team to experience the advantages of involving the main users. It has highlighted problems/solutions that the development team did not expect or consider e.g. missing form field or adding labels for context. The user feedback also helped the development team with their sprint planning and prioritising features.

For the users, they were open to providing honest feedback or to ask questions on features in development. Since they know what is being worked on, it showed that they have more ownership of the project. I noticed the users are more enthusiastic and positive when the development team share updates on their work.

Overall, introducing the UX framework to my team have positively changed their approach to internal projects. With users giving feedback and the development team sharing progress, both sides could see a clearer roadmap (both long and short term) of the project and how it changes the workflow of the company.