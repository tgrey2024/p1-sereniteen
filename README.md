# Project 1: Individual Project: Sereniteen - Teenage Anxiety Guide <a id="top"/>
![logo](https://github.com/user-attachments/assets/8c012545-402a-447f-a8b8-ba7bd7dc000d)

## Introduction
Sereniteen is the first HTML/CSS/Bootstrap website that I built as part of my first individual project on the AI-Augmented Full-Stack Bootcamp course at the Code Institute. Its aim is to help site users to understand what anxiety is, how it may affect teenagers, and provide basic guidance and links to resources and professional help.

Live site: [Sereniteen](https://tgrey2024.github.io/p1-sereniteen/) 

## Table of Contents
- [User Experience Design](#user-experience-design)
- [Project Brief](#project-brief)
- [Users](#users)
    - [User Stories](#user-stories)
    - [Colour Scheme](#colour-scheme)
    - [Typography](#typography)
    - [Typography](#typography)
    - [Wireframes](#wireframes)
- [Design](#design)
    - [Colour Scheme](#colour-scheme) 
    - [Typography](#typography)
    - [Imagery](#imagery)
- [Website Features](#website-features)
    - [Nav Bar](#nav-bar)
    - [Hero Section](#hero-section)
    - [Bootstrap Cards](#bootstrap-cards)
    - [Bootstrap Carousel](#bootstrap-carousel)
    - [Video](#video)
    - [Footer](#footer)
- [Responsive Design](#responsive-design)
- [Future Features](#future-features)
- [Technologies Used](#technologies-used)
- [Deployment](#deployment)
- [Testing](#testing)
- [credits](#credits)

Content References
Media References
Acknowledgements

[Back to top](#top)

## User Experience Design
Content of the subheading 3
Content of the subheading 3

### Project Brief
The site user's goal is to find "accessible, beginner-friendly information" on a mental health issue. The scope of mental health is very broad, so I have chosen to focus on anxiety in teenagers. The aim is to present information on common symptoms and how to manage stress using a "supportive and organised layout".

### Users
Potential users of the site are:
- teenagers who may be worried about themselves
- parents of teens who may be concerned about their children.
- friends of teenagers who may be worried about their friends having anxiety

Co-pilot was used to generate some personas, which were then reviewed and refined to enrich the analysis of users and their requirements:

##### Persona 1: Jake, The Anxious Teenager, Age: 16, Occupation: Year 11 Student, Tech Comfort: High

Background: Jake is a secondary school student who excels academically but struggles with social anxiety. He often feels overwhelmed and is looking for ways to manage his stress and anxiety.

Goals:
        * Learn effective coping mechanisms for anxiety.
        * Access resources and tools specifically designed for teenagers.
        * Find relatable stories and experiences from other teens dealing with anxiety.

Challenges:
        * Feeling embarrassed or reluctant to seek help from adults.
        * Difficulty concentrating on long articles or technical content.


#### Persona 2: Sarah, The Concerned Parent, Age: 42, Occupation: Full-Time Working Mum, Tech Comfort: Moderate

Background: Sarah is a dedicated mother of two teenagers. She has noticed that her 16-year-old daughter has been more anxious lately and wants to find reliable resources to help her cope.

Goals:
        * Find practical tips and strategies to help her daughter manage anxiety.
        * Access easy-to-understand information on the causes and symptoms of anxiety.
        * Locate support groups and professional help in her area.
Challenges:
        * Limited time due to her teaching job and family responsibilities.
        * Overwhelmed by the vast amount of information online and unsure of its credibility.


#### Persona 4: Anna, The Supportive Friend, Age: 17 Occupation: Sixth-form Student, Tech Comfort: Moderate

Background: Anna is a supportive friend who wants to help her best friend, who has recently opened up about their anxiety struggles. Anna is eager to find ways to be there for her friend.

Goals:
        * Learn about anxiety and how to support a friend dealing with it.
        * Find tips and advice on how to approach conversations about mental health.
        * Access resources that she can share with her friend.

Challenges:
        * Ensuring she provides accurate and helpful support without overstepping boundaries.

### User Stories
User Stories and the associated Acceptance Criteria and Tasks were generated using Microsoft Copilot. These were then reviewed and edited to be SMART and focused for the delivery of an MVP. A Project Board was set up in GitHub Projects to track project progress, and the user stories were prioritised using MoSoCoW.

US1. As a teenager experiencing anxiety for the first time or their parent, I want to find clear, relatable information about what anxiety is, so that I can find out if I have symptoms of anxiety and better understand my feelings.

US2. As a parent or friend of a teenager, I want to understand the signs of anxiety in teens, so I can recognize when my child might be struggling.

US3. 
### Wireframes
![wf-mobile](https://github.com/user-attachments/assets/948fcc3b-2e8d-4c7d-93cd-90d72806eb5d)
![wf-browser](https://github.com/user-attachments/assets/84f15a5d-8d09-4f55-bb15-49d03aedbe05)

[Back to top](#top)
## Design
### Colour Scheme
Content of the subheading 3

### Typography
Content of the subheading 3

### Imagery
Content of the subheading 3

## Website Features
### Nav bar
Home, Getting Help, Resources, Contact Us
### Hero Section
### Bootstrap Accordion
- what is Anxiety, Common Symptoms, Common Triggers: Social Media, Exams, Peer Pressure
### Bootstrap Cards
- Coping Strategies, Activities
- Online Resources, Self-Help Apps, Organisation
### Video
### Bootstrap Carousel
short stories
### Bootstrap Toggle button
To switch between the two colour schemes

### Getting Help
#### Types of Professional Help

### Footer
links to socials

[Back to top](#top)
## Responsive Design
Most of the content is responsive to different screen sizes as it was built using components from the Bootstrap Library.
![image](https://github.com/user-attachments/assets/0c076c56-37c8-45e0-a790-a9484876ee5e)

Video: Some elements such as the embedded YouTube video take up too much space on smaller devices. Media queries have been implemented to hide the video on smaller devices and provide an external link to the video on YouTube instead.

[Back to top](#top)
## Future Features
### Bugs to be Fixed
* A gap appears on the right on the medium-sized devices
* Scrolling can sometimes move the navbar up and down
* Links to more activity guides, checklists and questionnaire could be added.
### Calm mode switch
A Bootstrap switch could be added to the navbar to switch between a vibrant colour theme that would appeal to teens and a calmer alternative scheme that would make it easier for the reader if the colours are too stimulating. The current colour scheme is set in CSS variables, which could be leveraged to reset the colours between the two themes, but a page refresh needs to be triggered by the click event of the switch.
### Share your Stories
A modal could be added to allow users to submit stories to be shared with others who are managing their anxiety. Testimonials and success stories can give hope to parents and teenagers to help them with their recovery.

[Back to top](#top)

## Technologies Used
### Languages and Technologies
HTML5
CSS3
GitHub
Gitpod
### Libraries
Bootstrap 5.3.3
Font Awesome
Google Fonts
### Tools and Programs
LogoAI
Favicon.io

Balsamiq
Squoosh
MS CoPilot
GitHub CoPilot

[Back to top](#top)

## Deployment
The [Code Institute Template] (https://github.com/Code-Institute-Org/ci-full-template) was used to create the GitHub repository, so that the website could be developed in the correct setup of Gitpod IDE.

The GitHub Copilot extension was also installed in my local client version of MS VS Code, which was also connected with the same GitHub repository and linked to Gitpod via SSH. This allows for AI pair programming in the initial stages of development to create certain sections faster.

The process is as follows:
1. Login to your GitHub profile.
2. Go to the [Code Institute Template] (https://github.com/Code-Institute-Org/ci-full-template).
3. Click **Use this template** and then **Create a new repository**.
4. Enter the repo name and choose to create from template
5. Click **Open** with the Gitpod logo to open the Code Institute IDE workspace.
6. Open VS Code locally and click on Gitpod logo on the left. Click on right arrow next to the workspace you want to work on.
 
Once the MVP has been created in Gitpod, go to GitHub Pages to make an early deployment of the project, so that testing can be done in Dev Tools to highlight key issues that need to be resolve early on in the project.

[Back to top](#top)

## Testing
Validation of HTML/CSS, Lighthouse Audits, Bugs

[Back to top](#top)

## Credits
### Content References
Anxiety and How to Manage it: Pre-teens and Teens - Raisingchildren.net
[https://raisingchildren.net.au/pre-teens/mental-health-physical-health/stress-anxiety-depression/anxiety](https://raisingchildren.net.au/pre-teens/mental-health-physical-health/stress-anxiety-depression/anxiety)

Parents A-z Mental Health Guide on Anxiety - Young Minds
[https://www.youngminds.org.uk/parent/parents-a-z-mental-health-guide/anxiety/](https://www.youngminds.org.uk/parent/parents-a-z-mental-health-guide/anxiety/)

MS Copilot was used to generate much of the content on coping strategies and online resources, which was then reviewed and edited before including into the site.

### Media References

#### Organisation logos:
Young Minds - [https://www.youngminds.org.uk/](https://www.youngminds.org.uk/)
Stem 4 [https://stem4.org.uk/](https://stem4.org.uk/)
Anxiety UK - [https://www.anxietyuk.org.uk/about-us/](https://www.anxietyuk.org.uk/about-us/)
NHS - [https://www.england.nhs.uk/nhsidentity/identity-guidelines/nhs-logo/](https://www.england.nhs.uk/nhsidentity/identity-guidelines/nhs-logo/)
NSPCC - [https://www.nspcc.org.uk/](https://www.nspcc.org.uk/)

#### Photos:
Pexels

#### Acknowledgements
Many thanks to my three patient testers (also my husband and teenage children) for helping me test throughout development, and
Code Institute tutors (Dillon, Mark and Roo) for answering my endless questions

[Back to top](#top)
