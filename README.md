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
    - [Wireframes](#wireframes)
- [Design](#design)
    - [Colour Scheme](#colour-scheme)
    - [Typography](#typography)
    - [Imagery](#imagery)
- [Website Features](#website-features)
    - [Nav Bar](#nav-bar)
    - [Hero Section](#hero-section)
    - [Bootstrap Accordions](#bootstrap-accordions)
    - [Bootstrap Cards](#bootstrap-cards)
    - [Video](#video)
    - [Bootstrap Carousel](#bootstrap-carousel)
    - [Footer](#footer)
- [Responsive Design](#responsive-design)
- [Future Features](#future-features)
- [Technologies Used](#technologies-used)
- [Deployment](#deployment)
- [Testing](#testing)
- [Credits](#credits)

[Back to top](#top)

## User Experience Design

### Project Brief
The site user's goal is to find "accessible, beginner-friendly information" on a mental health issue. The scope of mental health is very broad, so I have chosen to focus on anxiety in teenagers. The aim is to present information on common symptoms and how to manage stress using a "supportive and organised layout".

The "business" goal is to help users understand what anxiety is and learn coping strategies so that teens and their parents can get credible information quickly and get help fast.
The name Sereniteen comes from serenity - the peace and calm that every teen and their families strive for.

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

#### Persona 3: Anna, The Supportive Friend, Age: 17 Occupation: Sixth-form Student, Tech Comfort: Moderate
Background: Anna is a supportive friend who wants to help her best friend, who has recently opened up about their anxiety struggles. Anna is eager to find ways to be there for her friend.
Goals:
        * Learn about anxiety and how to support a friend dealing with it.
        * Find tips and advice on how to approach conversations about mental health.
        * Access resources that she can share with her friend.
Challenges:
        * Ensuring she provides accurate and helpful support without overstepping boundaries.

### User Stories
User Stories and the associated Acceptance Criteria and Tasks were generated using Microsoft Copilot. 

The aim is to produce a minimum viable product (MVP) in the 2.5 days given. The AI-generated user stories were reviewed and edited to be SMART and focused for the delivery of an MVP. A Project Board was set up in GitHub Projects to track project progress. The user stories were prioritised using MoSoCoW based of benefits to users and viability.

Here are the user stories that have been prioritised as "must have":

US1. As a teenager experiencing anxiety for the first time or their parent, I want to find clear, relatable information about what anxiety is, so that I can find out if I have symptoms of anxiety and better understand my feelings.

US2. As a parent or friend of a teenager, I want to understand the signs of anxiety in teens, so I can recognize when my child might be struggling.

US3. As someone seeking help to cope with anxiety, I want to access practical tips and strategies to manage my anxiety, so that I can cope better during stressful situations like exams or social events.

US4. As a teenager in the midst of an anxiety attack, I want to quickly find emergency contact information and resources, so that I can get immediate help and guidance to calm down.

US5. As a teenager struggling with anxiety or the parent of one, I want to read personal stories and experiences from other teens who have managed their anxiety, so that I can feel hopeful and motivated to work on my own mental health.

US6. As a first-time site-user, I want to find easy navigation and a user-friendly design, including a responsive layout for my device, so I can find information quickly and efficiently without frustration.

US7. As a site user, I want to understand the purpose of the Sereniteen website immediately upon arrival so that I can get a visual understanding of the site's purpose and whether it's useful to me.

The following user stories that have been prioritised as "should have" and have been fully are partly implemented:

US8. As a teenager or parent considering therapy for the teen, I want to find information about different types of mental health professionals and treatments, so that I can decide what kind of help might be right for me or my child and feel confident in seeking it.

US9. As a teenager whose anxiety is misunderstood by adults, I want to find resources that explain teenage anxiety to parents and teachers, so that I can help the adults in my life understand and support me better.

US10. As a parent, I want to access expert advice on how to talk to my teenager about their anxiety, so I can approach the topic in a supportive and understanding way.

US11. As a teenager undergoing stress or as a parent of one, I want to find activities and practices that can reduce anxiety in teens, so I can encourage my child to try new methods for relaxation and stress relief.

### Wireframes
![wf-mobile](https://github.com/user-attachments/assets/948fcc3b-2e8d-4c7d-93cd-90d72806eb5d)
![wf-browser](https://github.com/user-attachments/assets/84f15a5d-8d09-4f55-bb15-49d03aedbe05)

[Back to top](#top)

## Design
### Colour Scheme
The aim of the project is to provide a calm environment that would be suited to both teenage users and their parents. I took inspiration from the colours from my garden and used ColorSpace to derive a calm and subtle palette.

![ColourPalette](https://github.com/user-attachments/assets/ade7bbde-7ade-4a25-9307-709d9f75d11d)

After the initial Lighthouse audit, I checked some of the colour combinations on [WCAG Contrast Checker](https://webaim.org/resources/contrastchecker/), and they were adjusted for better contrast and readability:

![Contrast](https://github.com/user-attachments/assets/3cdb157d-19e3-470d-9462-34c21215ec3a)


### Typography
[Google Fonts](https://fonts.google.com/) have been used as these are convenient to embed into the CSS file as an @import. 

Because both teenagers and their parents are in the userbase, a more distinct and handwritten font ([Gloria Hallelujah](https://fonts.google.com/specimen/Gloria+Hallelujah)) was chosen as the primary font, which helps to keep the reader at ease and imply that this is a site about young adults without it looking too childlike. In addition, a calmer and more open typeface ([Open Sans](https://fonts.google.com/specimen/Open+Sans)) was chosen to complement it to convey credibility and warmth while being a sans-serif font makes it quicker and easier to read.

![Font](https://github.com/user-attachments/assets/5702b1b8-7a3f-425a-a2aa-6d7fd6a3fd6a)


### Imagery
Initially I experimented with using MS Copilot to generate most of the images. The results were not very reliable and the process of refining prompts was taking too long, so I went to Pexels and found all of the photos from their photo library. The search function did not work well to bring back too many results, but there are additional tags in the search results page which open up the search and direct you to more photos. I found a range of photos showing a diverse range of ages, race and background with teenagers. Most of these were reduced in filesize and optimised on Squoosh and save as WEBP format to reduce page loading time.

The use of higher quality and slightly more stylised photos in muted tones would compliment the site design and appeal to teenagers who are more accustomed to visual apps like Instagram and Snapchat.

![anxiousboy](https://github.com/user-attachments/assets/be3792c8-cb01-474a-9ff2-e65760a3f604)

![meditate](https://github.com/user-attachments/assets/3dd33d2a-7ad0-4c57-b968-717634a93b37)

![family](https://github.com/user-attachments/assets/2e5cd7e7-e49e-410b-9a4f-b9d0df3c07d7)

![breathe](https://github.com/user-attachments/assets/2ad21648-a56a-4007-acd3-50d9fff85b7e)


## Website Features
### Nav bar
The aim of the product is to provide users with beginner-friendly summary of anxiety and quick access to get help or resources from reputable, reliable organisations. The navigation therefore must be:
- prominent and consistent on every page
- easy to use
- lead users directly in fewer than 3 clicks to what they need.

The Bootstrap navbar has been used as it is responsive to different screen sizes, it has a dropdown to provide users with more options, and it shrinks down to a hamburger menu button on the smaller screens.

Adjustments:
- Background colour using #a22101;
- Dark Theme (data-bs-theme: dark) for better contrast on Navbar text

### Hero Section
The purpose of the hero section is to convey the purpose of Sereniteen and the site. The chosen image portrays a struggling teen feeling along and needing help, something that users of the site might be able to relate to. The tagline contrasts in colour and message with this image to drive home the purpose of the site, which a call to action button to "Get Help Now".
![Hero](https://github.com/user-attachments/assets/0102cb13-19be-4a8b-acdb-9ea292026f2f)


### Bootstrap Accordions
#### Basic Facts and Types of Professional Help
I chose to summarise the key facts in a Bootstrap Accordion above the fold. This gives a first-time visitor to the site a snapshot of what to expect from this site and the kind of information they would expect to find. The accordion contains the key questions a user might ask on the index page, and on the resources page another accordion is used to show different types of professional help users might consider getting. The accordion stays within its section and collapses when a new question button is chosen.


### Bootstrap Cards
#### Self-Help Activities
Cards are a great way to categorise different options and pathways for users to follow. Bootstrap Cards have been used to show the wide range of self-help activities and coping strategies that are available for teens to manage their anxiety and reduce stress. The call to action buttons on each card use the highlight orange colour and contain a positive message in the form of "Let's ..." to tell users that they are not doing this alone. These link to external online resources to open in a new tab.

### Video
A YouTube video has been embedded in the index page in the Shared Stories section. This video is from a TEDxYouth talk by a teenager describing his experience of anxiety and strategies he uses to cope with anxiety. The video provides a richer content experience for the user, and perhaps draw strength from watching someone describe similar symptoms and overcoming their struggles.

The video does not work so well on the page on screens smaller than 380px, so a media query applies so that it could be replaced by a link to the video on YouTube on smaller screens.

### Bootstrap Carousel
A Bootstrap Slide-only Carousel has been implemented to show the different success stories shared by users.

Adjustments:
- Background colour
- Dark Theme for better contrast on Navbar text

### Footer
The footer uses darker tones from the palette to ground the page. It includes the copyright information and links to social media like Facebook, Instagram and X. This was initially created using inline GitHub Copilot prompt, which provided code that fulfilled most of the requirements.

[Back to top](#top)

## Responsive Design
Most of the content is responsive to different screen sizes as it was built using components from the Bootstrap Library.
![responsive](https://github.com/user-attachments/assets/9106ac90-025b-465c-944e-69f8bdfede3e)


Video: Some elements such as the embedded YouTube video take up too much space on smaller devices. Media queries have been implemented to hide the video on smaller devices and provide an external link to the video on YouTube instead.

[Back to top](#top)

## Future Features
 
### Calm mode switch
A Bootstrap switch could be added to the navbar to switch between a vibrant colour theme that would appeal to teens and a calmer alternative scheme that would make it easier for the reader if the colours are too stimulating. The current colour scheme is set in CSS variables, which could be leveraged to reset the colours between the two themes, but a page refresh needs to be triggered by the click event of the switch.

### Share your Stories
A modal could be added to allow users to submit stories to be shared with others who are managing their anxiety. Testimonials and success stories can give hope to parents and teenagers to help them with their recovery.

[Back to top](#top)

## Technologies Used
### Languages and Technologies
![Static Badge](https://img.shields.io/badge/HTML5-Language-blue)
![Static Badge](https://img.shields.io/badge/CSS3-Language-blue)
![Static Badge](https://img.shields.io/badge/GitHub-RepoHosting-black)
![Static Badge](https://img.shields.io/badge/Gitpod-IDE-yellow)

### Libraries
![Static Badge](https://img.shields.io/badge/Bootstrap-5.3-purple)
![Static Badge](https://img.shields.io/badge/FontAwesome-icons-navy)
![Static Badge](https://img.shields.io/badge/GoogleFonts-Typography-blue)
### Tools and Programs
![Static Badge](https://img.shields.io/badge/LogoAI-LogoGenerator-red)
![Static Badge](https://img.shields.io/badge/Favicon.io-icons-navy)
![Static Badge](https://img.shields.io/badge/Balsamiq-Wireframes-green)
![Static Badge](https://img.shields.io/badge/Balsamiq-Wireframes-green)
![Static Badge](https://img.shields.io/badge/MSCopilot-AI-orange)
![Static Badge](https://img.shields.io/badge/GitHubCopilot-AI-orange)

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
#### HTML Validation
Some unclosed tags were found on the initial parse of HTML validation. These were resolved and subsequently no errors were found in either of the HTML files:
![HTMLValidation](https://github.com/user-attachments/assets/68bbd4ec-e6cb-465e-92f4-1879b37a36fa)

#### CSS Validation
No errors were found in the CSS file.
![CSSValidation](https://github.com/user-attachments/assets/d26b76c8-3436-4ab4-9aa3-0901fa36a5f3)

#### Lighthouse Audit
A Lighthouse audit was conducted using the tool on Chrome Devtools after the first skeleton of the index page was built and deployed to GitHub. It is important to disable all extensions on the browser to obtain the correct performance results on response time. This provided some initial findings on loading time of images and colour compatability which was resolved before any further development.

The final deployment was audited again on Lighthouse on both mobile devices and desktop.
Index.html on mobile devices:
![index_mobile](https://github.com/user-attachments/assets/a12b44c0-8a41-401c-9097-948e59ee8088)

Get Help (resources.html) on mobile devices:
![resources_mobile](https://github.com/user-attachments/assets/1d846b82-6c69-4d47-a009-9ba15f38cbed)

Similar scores were obtained on the audits for desktops. Aside from warnings about minor delays caused by the incorporation of links to Bootstrap, Google Fonts, etc., the main improvement that could be implemented is on the images, particularly on the tradeoff between quality and reduced filesize to reduce loading time.

### Bugs yet to be Fixed
* A gap appears on the right on the medium-sized devices
* A review of spacing, margins and padding to make sure each element has well-placed on the page with plenty of breathing space
* Scrolling can sometimes move the navbar up and down
* Add more content on how to cope with specific stressors, like exams, social media, peer pressure and bullying.
* Links to more activity guides, checklists and questionnaire could be added.
 

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
* Young Minds - [https://www.youngminds.org.uk/](https://www.youngminds.org.uk/)
* Stem 4 [https://stem4.org.uk/](https://stem4.org.uk/)
* Anxiety UK - [https://www.anxietyuk.org.uk/about-us/](https://www.anxietyuk.org.uk/about-us/)
* NHS - [https://www.england.nhs.uk/nhsidentity/identity-guidelines/nhs-logo/](https://www.england.nhs.uk/nhsidentity/identity-guidelines/nhs-logo/)
* NSPCC - [https://www.nspcc.org.uk/](https://www.nspcc.org.uk/)

#### Photos:
* Pexels - [https://www.pexels.com/](https://www.pexels.com/)

#### Acknowledgements
Many thanks to my three patient testers (also my husband and teenage children) for helping me test throughout development, 
Everyone in my WECA group who have been so helpful and supportive leading up to this project, and
Code Institute tutors (Dillon, Mark and Roo) for answering my endless questions

[Back to top](#top)
