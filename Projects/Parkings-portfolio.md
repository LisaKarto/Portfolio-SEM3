# S-DB-GPS-S3 Parking garage Project, Parkings - Mediaan 

**Institution of education:** Fontys university of applied sciences   
**Study:** HBO ICT  
**Profile:** Software engineering  
**Program:** Bachelor   
**Semester period:** September 8 2022 - January 26 2023   
**Courses:**  S-DB-GPS3-S3  
**Class:** DB04  
**Professors:** Thijs Naus (GP), John Wijnen (SC)  
**Project:** Parking system  
**Partner in Education:** Mediaan  
**Student:** Lisa Kartodimedjo  

GP = Group project,
SC = Semester coach

* * *

# Foreword
Huge thank you to everyone involved for all their guidence, help and knowledge.
* * * 
# Table of contents
- [S-DB-GPS-S3 Parking garage Project, Parkings - Mediaan](#s-db-gps-s3-parking-garage-project-parkings---mediaan)
- [Foreword](#foreword)
- [Table of contents](#table-of-contents)
- [1. Introduction](#1-introduction)
- [2. Stakeholders](#2-stakeholders)
  - [2.1. **Professors**](#21-professors)
  - [2.2. **Our team, Parkkings**](#22-our-team-parkkings)
    - [2.2.1. **Who are we**](#221-who-are-we)
    - [2.2.2. **Our goal**](#222-our-goal)
    - [2.2.3. **Members and roles**](#223-members-and-roles)
      - [2.2.3.1. **Members:**](#2231-members)
      - [2.2.3.2. **Roles**](#2232-roles)
  - [2.3. **Our assigned Partner in Education, Mediaan**](#23-our-assigned-partner-in-education-mediaan)
    - [2.3.1. **Who are they and what do they do?**](#231-who-are-they-and-what-do-they-do)
    - [2.3.2. **Where to find them**](#232-where-to-find-them)
    - [2.3.3. **Product owners**](#233-product-owners)
- [3. The project](#3-the-project)
  - [3.1. How does our software support the parking garages?](#31-how-does-our-software-support-the-parking-garages)
  - [3.2. The reservation business process analysis](#32-the-reservation-business-process-analysis)
    - [3.2.1. **parking reservations process without our software system**](#321-parking-reservations-process-without-our-software-system)
    - [3.2.2. **parking reservations process using our software system**](#322-parking-reservations-process-using-our-software-system)
    - [3.2.3. **Conclusion**](#323-conclusion)
- [4. Website design](#4-website-design)
  - [4.1. User Interface](#41-user-interface)
  - [4.2. User Experience](#42-user-experience)
  - [4.3. Screens](#43-screens)
    - [4.3.1. **Parking garage app reservations management screen**](#431-parking-garage-app-reservations-management-screen)
    - [4.3.2. **Parking garage app CMS Tarrif management screen**](#432-parking-garage-app-cms-tarrif-management-screen)
    - [4.3.3. **Bonus UI \& UX decision example**](#433-bonus-ui--ux-decision-example)
- [5. Project Technicalities](#5-project-technicalities)
  - [5.1. Architecture and infrastructure](#51-architecture-and-infrastructure)
    - [5.1.1. **Architecture**](#511-architecture)
    - [5.1.2. **Infrastructure**](#512-infrastructure)
- [6. Culture \& Ethics](#6-culture--ethics)
  - [6.1. Cultural differences during this project](#61-cultural-differences-during-this-project)
  - [6.2. Ethics in software](#62-ethics-in-software)
  - [6.3. Ethical decisions in our group project](#63-ethical-decisions-in-our-group-project)
- [7. Project working process](#7-project-working-process)
  - [7.1. Working and structure](#71-working-and-structure)
  - [7.2. Agile](#72-agile)
    - [7.2.1. **What is Agile**](#721-what-is-agile)
    - [7.2.2. **Working Agile**](#722-working-agile)
    - [7.2.3. **Agile benefits**](#723-agile-benefits)
      - [7.2.3.1. **Agile frameworks**](#7231-agile-frameworks)
    - [7.2.4. **scrum**](#724-scrum)
      - [7.2.4.1. **scrum roles**](#7241-scrum-roles)
      - [7.2.4.2. **Product backlog**](#7242-product-backlog)
      - [7.2.4.3. **scrum board**](#7243-scrum-board)
      - [7.2.4.4. **Daily stand-ups and stand-downs**](#7244-daily-stand-ups-and-stand-downs)
      - [7.2.4.5. **sprints**](#7245-sprints)
      - [7.2.4.6. **Sprint reviews**](#7246-sprint-reviews)
      - [7.2.4.7. **retrospectives**](#7247-retrospectives)
  - [7.3. Workflow parkkings](#73-workflow-parkkings)
    - [7.3.1. **Why we use Agile and scrum**](#731-why-we-use-agile-and-scrum)
    - [7.3.2. **How we, Parkkings used Agile**](#732-how-we-parkkings-used-agile)
    - [7.3.3. **How we, Parkkings used Scrum**](#733-how-we-parkkings-used-scrum)
    - [7.3.4. My experiences with Agile and scrum during this project](#734-my-experiences-with-agile-and-scrum-during-this-project)
      - [7.3.4.1. **My time as scrummaster**](#7341-my-time-as-scrummaster)
      - [7.3.4.2. **My time as a teammember/developer**](#7342-my-time-as-a-teammemberdeveloper)
      - [7.3.4.3. **My overal opinion on Agile and Scrum**](#7343-my-overal-opinion-on-agile-and-scrum)
  - [7.4. Our work environment](#74-our-work-environment)
- [8. Reflection](#8-reflection)
  - [8.1. Full project reflection](#81-full-project-reflection)
- [9. Appendix](#9-appendix)
  - [9.1. Agile Values](#91-agile-values)
  - [9.2. Agile principles](#92-agile-principles)
  - [9.3. Agile Benefits](#93-agile-benefits)
- [10. Sources](#10-sources)

#  1. Introduction

During semester 3 of the Fontys HBO-ICT demand based programme, Fontys challenges it's students to complete 2 courses. Namely an individual course and a group project course. This document is written with focus on my group project course experience. If you want to read more about my experience and what I've been doing for the individual course you can find more information in the central portfolio document [here](https://github.com/LisaKarto/Portfolio-SEM3).  

The group project course enforces you to work alongside multiple other developers on a project at once for a partner in education, which helps you build your coding skills as well as your social skills all while giving you a sense of the "real world". In this document you'll find the information on topics such as, who the stakeholders for the project are, Our workflow during the project, what the project is and how it improves the current business process, what ethical decisions we've had to make and much more. You will also be able to find all of our work in this document.

[Back to table of content ⬆](#table-of-contents)

# 2. Stakeholders
 
## 2.1. **Professors**
During the semesters you have designated professors that will grade your work, 
Some are more involved with the individual course and others are more involved with the group course. Here are listed the professors I've had related to the group project course and what roles they haad during this course.

**Name**: Thijs Naus  
**Role**: Group project course tutor  
**Actions**: Giving feedback, available for support/advice, grading overall process, observing over all process, lectures when necessary, pep talks

**Name**: John Wijnen   
**Role**: Semester coach  
**Actions**: Leading retrospectives, available for support/advice, giving feedback, grading overall process

[Back to table of content ⬆](#table-of-contents)

* * *
## 2.2. **Our team, Parkkings**

At the start of the course the class gets tasked to construct teams of about 7 members to work with for the following 4 months. And naturally everyone settles with whoever they've coincidently have been sitting at the same table with. And so the team Parkkings was made. I've worked with these people for several months and it's safe to say that I haven't the faintest idea of who they really are. 

### 2.2.1. **Who are we**

Our team Parkkings consists out of Fontys HBO-ICT students that follow the demand based programme. We all share the same profile, software engineering. 

### 2.2.2. **Our goal**
We hope to build a functional product to satisfy our product owners, teachers and pass the semester whilst learning new skills and building upon our already existing skills.

### 2.2.3. **Members and roles**
To form a team you need members and each member usually holds some sort of role. Below are listed the members of Parkkings as well as some information on our the roles, we've had during this semester.

#### 2.2.3.1. **Members:**
* Atalay, Gökay - student, software engineering
* Derks, Jaimy  - student, software engineering - (Start semester - December)
* Eijnde, Davey, van den - student, software engineering
* Kartodimedjo, Lisa - student, software engineering
* Meegdes, Lean - student, software engineering
* Peeters, Ramon - student, software engineering
* Walraven, Jordy - student, software engineering

#### 2.2.3.2. **Roles**
We decided not to hold any static roles so everyone can get in touch with a little bit of everything at once. So roles switched during each sprint. So at the end we've all had some experience in various scrum roles as well as coding experiences in each field. Below I've listed the roles we've all shared.

**Technical roles:**
* Working on the back-end of the software product
* Working on the front-end of the software product
* Flexing between/assisting

**Scrum roles:**
* Scrum master
* Team member


[Back to table of content ⬆](#table-of-contents)
* * *

## 2.3. **Our assigned Partner in Education, Mediaan**
For this semester Fontys assigns it's groups with
These partners often come in and offer projects to work on for students. Partners and help students grow into their careers.

Want to see specific cases? go [here](https://mediaan.com/cases-index).
### 2.3.1. **Who are they and what do they do?**
Mediaan is a international company in the field of business transofrmation and tech innovation.
They also offer consultancy for companies that would like their organization to become more data-driven. 
The mediaan team combines digital, business and organizational expertise to achieve their goals and/or help other companies achieve their goals.
Mediaan promises transparancy, skills and agility to their customers. 

read more about them, [here](https://mediaan.com/about-us).


### 2.3.2. **Where to find them**
In case of interest I have listed Mediaan's socials underneath. 

**Official website:** https://mediaan.com/  
**Instagram:** https://www.instagram.com/mediaan.vibes/  
**LinkedIn:** https://www.linkedin.com/company/mediaan/  
**Faceboook:** https://nl-nl.facebook.com/MediaanABS  
**Youtube:** https://www.youtube.com/channel/UCbX3NvsTGNCc-XqJgH-4i6g  
**Twitter:** https://twitter.com/mediaan  

### 2.3.3. **Product owners**
Product owners are the 
Their role during the development process is to 

Mediaan as a whole has a lot of employees, but the people that we've been fortunate enough to have as product owners are the following people: 

**Kaj Nellissen**, Product owner    
**Timothy Hamilton**, Product owner  
**Ramona Domen**, Product owner on occasion 

[Back to table of content ⬆](#table-of-contents)
* * *
# 3. The project

Mediaan has had for parking garages but don't currently have the resources to build a proof of concept for. And that's where we, Parkkings come in to play. Below you can read the information we have received from our Product owners to work with.


<!-- Requirements -->
>## **The parking garage case**
><!-- Is this allowed to be public? -->
>**Milestone 1, MVP(Minimal viable product):**  
>When a driver arrives at the gate of a garage, he/she can open the gate by identifying themselves and the system will register their license plate. They will park their car and can do whatever they need to do. When they want to drive out of the garage, they can pay for their ticket the gate will then open for the. People can also reserve a parking spot in the garage up-front, making sure a spot is free for them around the time they want to arrive.
>
>The amount of people need to pay depends on the length of their stay and the time of day. Parking staff can define specific tariffs for certain moments in the day or for certain days in a week. On their overview, they can see the daily revenue in real-time.
>
>**Milestone 2:**  
>The staff at the garage have a real-time overview of the state of the garage. They can see which lots are vacant occupied or reserved. Whenever they see something in the garage that blocks a parking spot, they have the option to disable this lot in the system. For example, it might be that someone parked a car across multiple spots or some construction is going on.
>
>**Milestone 3:**  
>All of the parking garages owned by the company lie in places where many businesses reside. Some of these businesses have a lack of parking space on their own grounds and want to hire some parking spots in the garage. Employees of such companies can park their company car for free on the hired spots during work hours. The parking staff can fine non-employees for parking on these spots. Outside of work hours, hired spots can be used  by anyone. Every month, the system sends all companies an invoice.
>
>**Bonus:**  
>Many parking garages have multple exists which lead to different areas of the city above. People always want to park their car as close as possible to their wanted destination. The company has decided to invest in projectors that can project arrows on the ground that drivers can see. By stating their destination (by reserving up-front or indicating it at the gate), the system will lead them to a free parking spot that is closest to the exit for their destination.

From that information we have set up a bunch of user stories based on each milestone, which you can find in our [Jira environment's backlog](https://s3-gp-groep2.atlassian.net/jira/software/projects/PAR/boards/1/backlog). The user stories are marked their milestone.

However for those who do not have the time to go through all those user stories I have listed a quick overview of the applications that are make the overall project and their requirements.

**Parking garage app**   
**Target:** Parking garage visitors

Requirements:
- Login to the app
- Manage cars
- Creating and managing parking reservations
- List parking information
- List reservation details
- Pay for parking
- Logout

**Parking garage app: Content management system**  
**Target:** Parking garage employees

Requirements:
- Login to the app
- Manage garages
- Change tarrifs
- Manage parking reservations
- Logout

<!-- Business process -->
## 3.1. How does our software support the parking garages?
For this chapter I want to focus on the parking reservations process of a parking space soley. Other processes may be described in the future. 

I believe our system will have impact during the parking reservations process by ensuring a parking space for visitors, because our system lets a visitor know in advance wether a parking space is available or not for the specified time at which the visitor want to park. However a visitor now needs to reserve a parking space in advance if they want their parking space to be ensured. So in order to keep the benefits in the visitor's favour the system's end to end journey for the reservation process needs to be non taxing. So our team has done it's best to ensure that more about that ux/ui listed below underneath the chapter [UI/UX](#4-website-design).

Below you can read/follow the analysis that has been done to have reached the above conclusion. if that's not what you're into feel free to [skip to the next chapter](#5-project-technicalities).

## 3.2. The reservation business process analysis
I've analysed the business processes by comparing them to eachother, first you will find the parking space process without the aid of our software system alongsides it's flaws and why they're flaws. Then you will find the same process but this time aided by our software system, alongside will be the same list of flaws but with an explaination with why in this use case those same flaws are eliminated. Symbolistic diagrams of the processes will also be included to clearify. Lastly you can read the conclusion drawn from the evidence found during the analysis.


### 3.2.1. **parking reservations process without our software system**
To accurately carry out our analysis we must first describe the situation without any aid of software. 

**current flow:** A visitor shows up at a parking garage and enters through the gate. A visitor will then look around to see if there's any parking spaces available. A visitor will then find a parking space and park their car there.
<!-- insert diagram here -->

current flow diagram, For ease you can refer to the figure 1 activity diagram that serves as a symbolistic illustration on the current process flow:  

figure 1: non software aided flow diagram.   
 ![Activity diagram no software](/Projects/assets/AD%20no%20software.png)

**Exceptions:** 
* busy hours, during busy hours the visitor can have issue finding a spot if able to enter the garage at all.
  * no spots, if the visitor then finds there's no spots at all. The visitor will then have to either wait around for a spot to be freed with incoming information or go home in defeat.
  
**Current flaws:** 
* **Parking space uncertainty:**
  Without reservations there is no certainty for visitors to actually be able to find a parking space during busy hours.
* **Not time efficient:**
  Driving around looking for a parking spot may cose a visitor a lot of time during busy hours.
* **Loss of customers/potential buyers:**
  Driving/waiting around for a spot is tedious, visitors might not want to revisit because of this reason. The parking space will be associated with a bad experience and so will their destinations. This causes a loss of potential customers and thus also a loss of money that could have been earned.

### 3.2.2. **parking reservations process using our software system**
To accurately carry out our analysis we must now describe the situation with the aid of software. 

**software aided flow:** A visitor uses our web application to make a reservation, a visitor chooses a date and time to park. The system lets the visitor know wether or not the visitor can park at that time. If the visitor is able to park at that time the system will assign a designated parking space to the visitor. Now the visitor has a guaranteed spot for the day and time they arrive. On the reserved date a visitor simply drives up to the garage, identifies themselves at the gate and parks in their designated spot.  

software aided flow diagram, For ease you can refer to the figure 2 activity diagram that serves as a symbolistic illustration on the software aided process flow:  

figure 2: software aided flow diagram.  
![Activity diagram no software](/Projects/assets/AD%20software.png)  

**Exceptions:**
* no spots available, during very busy days/hours what if there's absolutely no spots available. This exception could still occur yet is improved because the visitor is aided with the benefit of knowing this information before driving out to the parking space and thus has the time to come up or initialize their backup plan. The system could in the future also be optimized to notify a visitor when reservations for their desired date and time are canceled so they can reserve a spot after all.

How our software system eliminates these flaws:
* **Parking space uncertainty**
  With the use of our system parking space uncertainty is eliminated when you reserve a parking spot in advance. The system will let you know if there's any place available for your desired parking time or not.
* **Not time efficient:**
  With the use of our software system you won't have to drive around to find a spot, instead when you have made a reservation. There will be a designated parking spot for the visitor.
* **Loss of customers:**
Due to elimination of the above issues, the parking experience will have improved. And thus they'll feel more at ease going to park at the garages, which results in more regular visits/visitors, which results in more potential buyers, which means Ka-ching, more money.

Additional support:
* **Potential to carry out data analysis:**
  Through the system experts would be able to track the parking garages, with that data experts get the potential to draw useful conclusions. Such as whether there's enough parking spaces, or at what hour most customers arrive. This way the parking garage's owners will have more support/evidence when making new decisions. For example, data could conclude that much more people want to reserve spots throughout the week than is available in the garage. This new deiscovery can prompt the parking garage's owner to expand their garage or open a new garage nearby.

### 3.2.3. **Conclusion**
I conclude out of the analysis I've carried out above that our software will have a positive impact on the finding a parking space process at parking garages. Yet a downside may be that visitors have to reserve a spot in advance. But I suspect it's better and cheaper than going out to a parking garage only to find out there's no available spaces and losing money on gasoline aimlessly driving around for a space whilst wating for a space to clear up. And thus would cause overall benefits for anyone making use of the parking garages and even for stores near parking spaces. Why not grab a quick red bull since we're close? :) ~~Red bull does not sponsor this portfolio~~

other business processes tackled by our software system may be described in the future

[Back to table of content ⬆](#table-of-contents)
<!-- UI/UX -->
# 4. Website design

Now that we've done a bit of a dive into the requirements of the project, I'd like to give you more of an idea of what the app looks like. As a visual representation often helps our brains capture the idea a lot easier than a text description can. So in the next chapter I'll show you pictures of the design of our product. I'll also be writing a bit about our approach for these designs and our thoughts behind them.

## 4.1. User Interface 
The user interface is what your users get to see and really interact with and ultimately what really makes your software. User interface can make a huge impact in how a user perceives your product. And therefore it comes with it's own set of challenges and decisions. In this chapter I'd like to write about the UI decisions we've made.

To approach this I'm going over two different designs for two different apps that have different target demographics. By doing this I can make clear the differences of approach when a target audience changes.

**Parking garage app reservations management**  
>**Visability:** Public  
**Target:** Visitors/Customers  
**Function:** Viewing parking reservations  
**UI approach for the parking garage app for customers:**
We chose to develop our styles mobile first, which means we would first design the mobile version of the application and then scale outwards all up until we'd reach good designs for desktops in order for our application to be responsive on all devices. We plan for the application to be predominantly used on mobile phones so responsitivity was a great importance.   
[See Parking garage app view reservations screens ⬇](#431-parking-garage-app-reservations-management-screen)


**Parking garage app CMS Tarrif management**  
>**Visability:** Private  
**Target:** Admins/Employees  
**Function:** Viewing hourly tarrifs for a specified parking garage   
**UI approach for the parking garage app CMS for employees:**
As opposed to the public application the CMS hasn't been developed nor designed mobile first, as we plan for this application to mainly be used via desktop in the basement where Betty is being held captive.  
[See Parking garage app CMS Tarrif management screens ⬇](#432-parking-garage-app-cms-tarrif-management-screen)


**Conlusion user interface**   
So as you can see there's a clear difference between these 2 designs, this is caused by the different target groups. Public applications tend to want to stimulate satisfaction in users and extrude friendly energy. However the more private work related applications are often aimed to look more practical. Don't get mistaken private applications are still allowed to look slick, beautiful and friendly, it just often isn't the first thought when designing them as there are certain standards and requirements to be met.

## 4.2. User Experience 
While the previous segment focused on the visual representation of the app and how it impacts a user's experience visual appearance alone isn't enough 
User experience are things such as; how many clicks it takes a user to get somewhere, whether or not it's easy for a user to navigate around your application or if they get lost a lot. An application shouldn't be too puzzeling to use for users or it may cause a recession in how much a user would like to use your application.

To approach this I'm going over two different designs for two different apps that have different target demographics. By doing this I can make clear the differences of approach when a target audience changes.

**Parking garage app reservations management**
>**Visability:** Public  
**Target:** Visitors/Customers  
**Function:** Reserving a parking spot at specified parking garage  
**UX approach for the parking garage app for customers:** It's important to offer good user experience to your customers. Nothing should be confusing, it should be swift and easy to navigate through and it should provide enough user feedback. This is what we've aimed for. For each screen we thought about what a user may need on said screen and in case it needed a reference to another page it would be provided. We've made sure to include animations and or messages to provide user feedback.

 [See Parking garage app view reservations screens ⬇](#431-parking-garage-app-reservations-management-screen)

**Parking garage app CMS Tarrif management**
>**Visability:** Private  
**Target:** Admins/Employees  
**Function:** Managing hourly tarrifs for a specified parking garage   
**UX approach for the parking garage app CMS for employees:** The CMS is a work environment, it's made for employees their day to day use. So it should be easy to learn, easy to use and none taxing for ones mind as that could evoke stress within a person. This application has to be structured in a way to mitigate possible data confusion mistakes. So it needs to have very clear intentions on each page and warnings when risky features like deletion features are called.  
[See Parking garage app CMS Tarrif management screens ⬇](#432-parking-garage-app-cms-tarrif-management-screen)

**Conlusion user experience**  
The way your audience experiences your software is very important, as bad experiences drive your targets away into the hands of a competitor that offers a better experience. Thus it's important to think about what your user wants from your application and how you can offer it to your using in the least taxing form. For example; Content management systems are work related. So our audience want simplified designs that are quick to use for max efficiency (no confusing routes, not too many clicks) and stress reduction, without too much care about how it looks because it's all go go go in this environment.

## 4.3. Screens
For ease I chose to showcase the screens below with description for UI and UX decisions according to each screen. I've structured this chapter this way to avoid showcasing all the screens twice. I've split the screens based on their feature.

* [See Parking garage app view reservations screens ⬇](#431-parking-garage-app-reservations-management-screen)  
* [See Parking garage app CMS Tarrif management screens ⬇](#432-parking-garage-app-cms-tarrif-management-screen)

### 4.3.1. **Parking garage app reservations management screen**
<!-- Continue here; Include screens and small descriptions -->
**Screen viewing parking reservations:**   
![reservation-overview](/Projects/assets/reservation-overview.JPG)  
**Screen description:** On this page a customer can view reservation's that they've set.  

**UI decisions:** In this page we are conciously utilizing colours for the statuses of a reservation, this way a user can instantly see whether or not their reservation has been accepting,denied or is still pending. We've made sure to choose familiar colors; green, yellow and red, meanings of these colors are frequent in society with similar meanings. You can trace these meanings back to traffic lights for example.   
>
**UX decisions:** This page is aimed at reservations but what stands out is the "manage cars" option that is mounted at the top next to "new reservation". Cars have a relationship to reservations, when a user wants to make a reservation a user needs to think about what car they want to use for this reservation as the car is what identifies a user at the gate. Because of that thought proces the user might want to manage their cars and thus a quick navigation option to the car management page is provided so a user doesn't have to refer all the way back to the home screen to manage their cars.
>

[back to ui information ⬆](#41-user-interface)  
[back to ux information ⬆](#42-user-experience)

### 4.3.2. **Parking garage app CMS Tarrif management screen**
<!-- Continue here; Include screens and small descriptions -->
**Screen Viewing hourly tarrifs:**  
![tarrif-overview](/Projects/assets/tarrif-overview.JPG)  
**Screen description:** On this screen a employee can view and manage tarrifs for specific parking garages.  

**UI decisions:** As for the UI there's a huge difference in loudness on this screen. The most important components in this page are highlighted; Have a look at the blocks within the calendar, they have been granted outstanding colours whereas the rest of the page is very monotone and silent. What's also worth mentioning is that both blocks have different colours, because they serve different functions. 

This is a concious decision from the development team, this way a user can quickly see and associate traits with certain blocks. In this case the yellow blocks represents a one time change, whereas a purple block represents a repetitive rule.  

**UX decisions:** A user will navigate with the motivation to do something specific so
the concious decision has been made on this screen to not bombard a user with many different options. And keep the page to the point and practical.

[back to ui information ⬆](#41-user-interface)  
[back to ux information ⬆](#42-user-experience)


### 4.3.3. **Bonus UI & UX decision example**
<!-- Continue here; Include screens and small descriptions -->
**Space selection screen:**  
![bonus-ui-ux-overview](/Projects/assets/bonus-ui-example-space-choosing.JPG)  
**Screen description:** This is a bonus screen, the design for this screen has been made but it's never been implemented due to a change in the application's flow.
Screen description: On this page a visitor could choose a prefered space after selecting times for a reservation.    

**UX decision:** 
This has been removed due to increase of the end 2 end journey for a user so instead we have automated the space selection function in the backend without the user having to do any additional clicks. They just get a space assigned to them. 

**UI decision:** Visually what really stands out on this page is the icons next to spaces. These icons are an easy way to make quickly make clear to the user that the space has a certain trait. For example the wheelchair that signifies that it's a parking spot meant for people with disabilities. And the second icon signifying that the parking spot offers a charging station for electrical cars.  

[back to ui information ⬆](#41-user-interface)    
[back to ux information ⬆](#42-user-experience)  

**Overall conclusion**  
If you compare the above examples you can see that there's a clear difference in approach. For both applications the goal for the user experience was for it to be as pleasant, simple and easy to use as possible. However for the visual representation there's a clear difference, As for the more public application styling is a lot more welcoming and friendly. Whereas for the private content management application the visuals are aimed more towards practicality than aesthetic.

There's a lot more coming into play than meets the eye when it comes to application design. What a user sees are all a visual representation of thoughtful decisions, for example how we seperate and cluster information together visually. And different target groups call for different approaches.


**navigation**  
All designs were made using the designing tool Figma.
For those interested I have included links to our design work environment below;

**Figma design work environment:** https://www.figma.com/file/rKlcGcAKuvNdvQK8NnsnZq/Untitled?t=WOYUZzSKHsRF0ZgU-0  
**Figma design demo:** https://www.figma.com/proto/rKlcGcAKuvNdvQK8NnsnZq/Untitled?node-id=73%3A5&scaling=scale-down&page-id=0%3A1&starting-point-node-id=73%3A5&show-proto-sidebar=1  


[Back to table of content ⬆](#table-of-contents)
<!-- Web application -->
# 5. Project Technicalities
Software consists out of a bunch of building blocks, building blocks like languages, frameworks and a lot more that's going on below that. But the way we software developers create it is by utilizing languages and frameworks. So decisions need to be made, which languages and frameworks do you use for what project and why? In this chapter I will list what we have made use of during our building process and why. You will also find diagrams to help clearify these architectural structures.

For this semester Fontys has challenged it's software engineering students to set up a distributed architecture since this has many benefits and is commonly used in software development today. So we better get to learning. This is the reason that we've chosen to set up REST api's for the backend. Fontys also wanted us to use a javascript based framework for the front end and that pairs well with a REST api distributed architecture. 

## 5.1. Architecture and infrastructure
In this section you will find the architecture and infrastructure of the product, listed followed with compact substantiations where needed.
### 5.1.1. **Architecture**
In this section you can read about the architecture of our product.  

**Languages and frameworks used:**  
Underneath I have listed the languages alongsides the frameworks we have decided to use for the project.

**Backend:** 
* **Main REST API:** C# - ASP.NET - Swagger
  * Substantiation:  The main API is written in C#, we find c# and ASP.Net core is more than capable for the functionalities we need to make for this project. We have made use of the swagger framework to make this process easier and thus save us some time.
* **CMS REST API:** C# - ASP.NET
  * Substantiation: Again c# ASP.NET is fully capable for the functionalities needed in the CMS rest api.
  * Note: This API, may be removed in the future. It is currently up for discussion within our team.
* **DATABASE:** Relational SQL database - Microsoft SQL server
  * Substantiation: For this project we have deduced that we need a relational database for it's functions. And since we all have SQL experience we decided that MSSQL is more than viable for the job. MSSQL also cooperates  well with C# - ASP.Net.

**Frontend:**
* **MAIN UI:** Javascript, HTML, CSS - REACT - Material UI
  * Substantiation: We found that REACT is fully capable of carrying out and looks very slick. Additionally we had variations in experiences in react so we figured this could work well for us as some students could further their current skill on it and others could learn whilst always having various helpers available.
* **CMS UI:** Javascript, HTML, CSS - REACT - Material UI
  * Substantiation: We found that REACT is fully capable of carrying out and looks very slick. Additionally we had variations in experiences in react so we figured this could work well for us as some students could further their current skill on it and others could learn whilst always having various helpers available.

**External services:**
* Google Oauth 2.0
  * Substantiation: Google's Oauth 2.0 protocol is very strong and easy for developers to use. Google is wildly popular so the chances that an adult today has a car but not a google account are very slim so we found Google's Oauth the perfect solution to having a safe authentication feature. Fontys also challenged us to make use of a microservice and by calling Google's Oauth we do exactly that.
* Mollie payment service
  * Substantiation: offers   
  * 
**Languages and frameworks used architectural diagram:**  
Below you can view a diagram that symbolizes the interaction/flow between these languages and frameworks.
![Languages and frameworks diagram](/Projects/assets/Languages_and_frameworks_architecture_diagram.png)


### 5.1.2. **Infrastructure**
Now that we know what languages and frameworks are used in the project, it may be nice to go over how these applications interact with eachother. You can find such information here. First I will list what applications make the whole Parkkings application.

The Parkkings application consists out of: 

**Front end:**  
* Guest User interface (used by visitors/customers)   
* Content Management system (used by admins)  

**Back end:**  
* REST API  
* MSSQL database
    
**Infrastructure diagram**
![Parkkigs infrastructure](/Projects/assets/architectuur_parkkings.drawio.png)  
**ERD database**  
![ERD](/Projects/assets/ClassDiagram_Proftaak.drawio_4.png)  
[Back to table of content ⬆](#table-of-contents)  
<!-- cultural differences and ethics -->
# 6. Culture & Ethics
In this chapter you can find information on the culture & ethics within our group.


## 6.1. Cultural differences during this project

**In our team**
As for culture we didn't have many hinders if any at all, we are all Dutch students experienced at Fontys with an interest in Software technology. Therefore our values and principles were all relatively streamlined. Within the team there were no cultural actions needed like switching up the language. 

**Our Product owners**
Mediaan is an international company, however our product owners were experienced Dutch software engineers. Because of their shared software engineering backgrounds there weren't any language barriers caused by termonology, which can be a thing when developers work with companies. For example a Business or art major may not understand or be familiar with most software technologies.

**The software**
As for the software, like mentioned above our Product owners come from an international business. Therefore the software has been written to be consumed internationally. And because of that the application's text for the user to consume has all been written in English as it is our world's international language. Another example would be the colour pallete utilizes colors familiar in all countries. Green is universially known as "Good/Safe", Yellow is universionally known as "Mediocre/Warning". And red is universially known as "Bad/Danger".

## 6.2. Ethics in software

Software today is incredibly impactful in society, In the world today software plays a role in how people work, live, act and even think. Which makes software engineers a rather powerful influential group. We, as software engineers need to be careful with what we put out into the world as our product can have big impact onto people their lives this impact can be good as well as it can be bad.

## 6.3. Ethical decisions in our group project
Our webapp mostly consists of seemingly safe features, We aren't setting strangers up together for a date without supervision or anything like that. However there are still potential dangers to our application. In 9 out of 10 software products there are hidden ethical decisions that need to be made. In our project this was mostly centered around handling user data. Our product owners brought data safety to the surface very early on in our development life cycle.

**Making use of third-party components**  
As we are 2nd year students with little to no experience in creating secure enough software to fend of the advanced hackers in the world, we decided to turn to third-party solutions. For example for authentication, we turned to google as they are on of the most popular leading software companies and we handle user data through/from them. So we don't have to store any user data in a insecure place instead it's handled by google one of the most reliable companies today. 

**Google Oauth**
As mentioned above we make use of Google as Oauth it's a reliable secure service set up by professionals. We figure this is a lot more secure than if we'd make our own system for this feature. This was a decision we've made based of ethical beliefs.

**Mollie payment system**
Similarily to the authentication feature, the payment feature also handles sensitive user data. And thus must be very secure and uninterceptable. As we are not experienced with creating secure enough software we were recommended by our product owners to use this third party service.

In conclusion it is ethically our duty to care for due diligence and thus carry out enough research around the third party components we choose to make use of.

**Letting a user know what they're getting into**
When an app is produced and you want to make use of it, it's mainly initialized with a terms of service of some sort to make sure a user knows what they're getting into. We haven't established any during this team but if it were up to me and the legal system, this would definitely be included in the future. This way we can also let users know ahead that we are in collaboration with Google services and other third party services.

[Back to table of content ⬆](#table-of-contents)
<!-- Agile method -->
# 7. Project working process
Underneath this chapter you can read more about how are working flow was during this project.

I've first written a bit of information on the methods (Agile, scrum) we've used to guide our workflow, if you are already familiar with these methods or want to skip this section for any reason. You can refer [here](#73-workflow-parkkings) to get directly into how we utilized Agile and scrum during our project time.

## 7.1. Working and structure
During this semester there's a big focus drawn to a developer's way of working, products can be made just like any passion project can be made in someone's backyard.
But me.. I never managed to finish the guillotine I'd tried to built from scratch in my backyard, why? Because I had no plan and no working structure. 


 And so I've learnt that; if you neglect structure during your working phases you may find yourself losing track of your project entirely. Which may lead to a decrease in productivity or even complete neglection of the project itself. Therefore to help prevent this from happening and ease things within one's own mind it is important to adopt a good, structured way of working. This is especially important while developing in a team.
A good working flow, with rules and structure can help to prevent misscommunication errors or other type of errors within a team. For we are all human after all, and working alongside eachother can be immensely challenging but with good structure we may work in complete cohorent unity. And if lucky, also harmony. If unlucky harmony without the "ony".


## 7.2. Agile 
Sadly, I wasn't the first person alive and yes, I do blame my parents. However out of tragedy comes something good and in this case, this good something is the fact that other people have done important work for me. Such as creating the Agile way of workings. But because of that I also had no idea of it's existence, let alone it's working. However it is important to know considering it's commonly used in development teams today. But how does it work? And why do we use it? You can find the answers to that question in the following section where I've established a small research on Agile and it's most frequently used framework; Scrum.

### 7.2.1. **What is Agile**
> Agile is an approach to software development that seeks the continuous delivery of working software created in rapid iterations. - Red hat

As the name Agile suggests, Agile designs it's teams to be able to pivot quickly and adapt to change without much difficulty. This way of working has gained a lot of popularity over the past 2 decades. When working according to the agile methodology you work by breaking your project into several phases, staying in constant collaboration with stakeholders and continuesly imrpove your product at every stage. Agile guides teams by enforcing them to engage in project planning, executing and evaluating. 

Agile puts focus upon the way of thinking about collaboration and workflows with a set of values to guides a team's choices.  

### 7.2.2. **Working Agile** 

Working Agile is working according to the agile values and principles. But for those who prefer consuming knowledge in paragraphs over lists here are a few actions that Agile teams take; When working Agile teams break large projects down into short timelines and deliver regularly. As for requirement documentation the development team won't spend too much time writing exhaustive documentation. Instead the team will set up a backlog with user stories that have been agreed upon by the customer. User stories are descriptive and relatively quick to write and easy to understand.
Delivering regularly helps to make sure that stakeholders are involved during the development cycle as much as possible. Agile teams must have a flexible mindset. If during a delivery meetup with the stakeholders changes are made to requirements, the Agile team should be able to implement this change without suffering too much of a delay. When working Agile you are required to think innovatively and strive to improve by participating in frequent reflections.

Below I have listed a simple overview of these values and principles. For more information on these values and principles you can refer to the appendix. (The appendix has anchors back to this part of this document, so you don't have to fear getting lost.)  Or you can redirect to wrike's documentation on agile, which I've used as a source [here](https://www.wrike.com/agile-guide/agile-manifesto/).

quick navigation:  
[Check out valeus in the appendix](#91-agile-values).  
[Check out principles in the appendix](#92-agile-principles). 

Below a list of the 4 Agile values:
>**4 Agile values** 
>1. Individuals and interactions over processes and tools
>
>2. Working software over comprehensive documentation
>3. Customer collaboration over contract negotiation
>4. Responding to change over following a plan

Below a list of the 12 Agile principles values:
>**12 Agile principles:**
>1. Our highest priority is to satisfy the customer through early and continuous delivery of valuable software.
>
>2. Welcome changing requirements, even late in development. Agile processes harness change for the customer's competitive advantage.
>3.  Deliver working software frequently, from a couple of weeks to a couple of months, with a preference to the shorter timescale.
>4. Business people and developers must work together daily throughout the project.
>5. Build projects around motivated individuals. Give them the environment and support they need, and trust them to get the job done.
>6. The most efficient and effective method of conveying information to and within a development team is face-to-face conversation.
>7. Working software is the primary measure of progress.
>8. Agile processes promote sustainable development. The sponsors, developers, and users should be able to maintain a constant pace indefinitely.
>9. Continuous attention to technical excellence and good design enhances agility.
>10. Simplicity — the art of maximizing the amount of work not done — is essential.
>11. The best architectures, requirements, and designs emerge from self-organizing teams.
>12. At regular intervals, the team reflects on how to become more effective, then tunes and adjusts its behavior accordingly.

When staying faithful to these values and principles Agile rewards you with a few benefits. 

### 7.2.3. **Agile benefits**

When staying faithful to these values and principles Agile rewards you with many benefits of which 6 core benefits. I have listed these benefits underneath. These benefits are also listed in the appendix with more detailed descriptions of how they come to be. 

quick navigation:  
[Check out Agile benefits in the appendix](#93-agile-benefits).  

Below a list of the 6 core Agile benefits:

>**6 Agile benefits** 
>1. Satisfied customers
>2. Improved quality
>3. Adaptability
>4. Predictability 
>5. Reduced risk
>6. Better communication

#### 7.2.3.1. **Agile frameworks**
Agile doesn't come with a singular approach and is not a set of prescriptions listing exactly what actions to take. But then how do you really work with it? You can develop your own way of working and still abide to Agile. However to save teams some time, they have the option to choose out of various Agile frameworks and follow accordingly. To list a few of the popular ones: Scrum, Kanban and Extreme programming(XP). However our team Parkkings have made use of the Scrum Agile development framework, therefore in this document I'll only focus on that framework in particular and you can learn more about the others on your own.

If you are interested in the other frameworks listed, you can find more information here:

* Kanban: https://www.agilealliance.org/glossary/kanban/  
* Extreme programming(XP): https://www.agilealliance.org/glossary/xp/  

For our project we decided to make use of the scrum framework within Agile. Scrum is a framework for managing work designed best working for teams of 5-9 members. (Not all scrum is Agile)


### 7.2.4. **scrum**
Scrum is an Agile framwork that provides structure for Agile teams to abide to. Scrum can be used for complex projects done by a development team of about 5 - 9 team members. 


#### 7.2.4.1. **scrum roles**
Scrum makes use of different roles, each of which hold specific accountabilities. 
Below I have listed these roles and what their accountabilities are. The amount of each role in scrum teams can vary. For example a team could have 2 scrummasters at once. 

Disclaimer: These are the most common practices, teams may customize these roles within their organization as they like.

A scrum team consists out of the following roles:
- Product owner: Makes sure that the scrum team is creating the most valuable product possible.

accountabilities:
- Communicating the product goal.
- Clearly communicating Product Backlog items.
- Ordering Product Backlog items.
- Ensuring that the Product Backlog is understood.

Scrum Master: Makes sure the scrum team is as effective as possible. Scrum masters have to be good at steering their developers and they need to have a good overview of what is being done. They also tend to manage/take lead in stand-ups, stand-downs and sprint reviews.

accountabilities:
-  Coaching team members in self management.
-  Helping the team focus on creating high-value increments that meet the definition of done.
-  Helping find techniques for effective Product Backlog management.
-  Leading, training and coaching organizations through scrum adoptions.
-  Helping others through their scrum knowledge and making sure rules are clear to everyone.

Developer: Works to create the product.

accountabilities:
 -  Instilling quality by staying faithful to the Definition of Done.
 -  Holding themselves and others accountable as professionals
 -  Adapting their plan each day to meet the sprint goal
  
#### 7.2.4.2. **Product backlog**
As for documentation in Agile, software gets valued more. As stated in Scrum value 2, and scrum principle 7. But there has to be some kind of minimal written down contract. In Agile/scrum the requirements documentation consists out of user stories. User stories are a clear, concise, compact and less taxing form of requirement documentation. These user stories together form a product backlog. This product backlog containing all of the user stories is later used to pick tasks from for sprints. The backlog is never definitive, meaning it is flexible to change and changes may occur throughout the whole development life cycle if demanded. 

>**scrum value 2:** Working software over comprehensive documentation

>**scrum principle 7:** Working software is the primary measure of progress.

#### 7.2.4.3. **scrum board**
These user stories and tasks can be put in a scrum board. A scrum board offers a clear overview of; what needs to be done, is being done and what is done. Teams can also customize this board to other statusses, a custom example additional status would be: "In testing". The scrum board helps the developers and stakeholders know what the state of the project is at all times in real time. (if utilized properly) You can view an example scrumboard in the image below.

Figure 3. Example scrumboard
![example scrum board](https://www.visualworkplace.nl/static/upload/full/c6927be1-f3aa-4448-ab6d-5d611745896d/Folens-Scrum+board-%28120x90cm%29-MvJ-v1-13-10-2015.jpg)


#### 7.2.4.4. **Daily stand-ups and stand-downs**
Teams participate in daily stand-ups and stand-downs. These activities ensure good communication within a scrum team and are often steered by the scrum master. During the daily stand-up, often the first thing in the morning the scrumteam comes together to share their ideas and goals for the day. Then the team goes to work and at the end of the workday the team comes together once more to hold their daily stand-down. In which they do a status update to eachother.

#### 7.2.4.5. **sprints**
As mentioned in the previous segment about Agile, part of Agile is to break up a project in smaller timelines. In scrum we call these shorter timelines "Sprints". Sprints usually consists out of 1-5 weeks of work. At the start of a sprint, the product owners and the team sit down together to decide which tasks need to be worked on. Then the development team goes to work, at the end of the sprint a review/delivery takes place. During said review/delivery the product owners and the development team can discuess what's happend this sprint and what the wishes are for the following sprint. These review/delivery meetings are usually lead by the team's scrummaster.

#### 7.2.4.6. **Sprint reviews**
At the end of each sprint, the sprint team sits down with the stakeholders of the project and does a status update on the project. These sprint reviews ensure good communication with the stakeholders and also open a oppertunity for discussions, new ideas and or changes.

#### 7.2.4.7. **retrospectives**
According to Agile, reflection is important in a team during the development lifecycle. Scrum does a great job supporting this by making teams do frequent retrospectives (Most commonly done at the end of each sprint) where developers can face themselves and eachother honestly and think about how to improve their productivity. There's all sorts of approaches a team can utilize to do these retrospectives. There's even tools designed for these retrospectives that enforce teams to really get to the important pressure points that would otherwise be forgotten or overlooked.

[Back to table of content ⬆](#table-of-contents)
## 7.3. Workflow parkkings

### 7.3.1. **Why we use Agile and scrum**
First and foremost, Using Agile is one of our learning outcomes for this course. So us using Agile is a given as it is forced upon us. However that doesn't mean that is the only reason. If I were to choose what methodology we could pick from, I would still choose Agile as opposed to the Waterfall approach. I have written more about that below. Using scrum was also encouraged by our stakeholders so naturally we gravitated towards the scrum framework. Agile in addition the scrum framework are commonly used practices.

**Why I would choose Agile for this project**   
Personally for me the Agile [Benefits](#93-agile-benefits) are it's main selling point. Throughout my developer career I've always been warned of the following situation, the situation where you've worked on a product for 6 months without seeying your customer and delivering it to them. And then the customer looks at you confused and says "This isn't what I asked for?". And 6 months go down the drain, Agile mitigates the risk of this happening as you take your customer with you throughout the entire development cycle.  

**Why I would choose Scrum for this project**
Agile is nice but without framework I wouldn't entirely know where to start or how to keep going. Scrum has helped a lot by providing some structure. Scrum's daily stand-up and stand-down idealogy has proved very well for in team communication, and I value it just as much as Agile does. I personally struggle with communication at times so the guidelines/structure proves very beneficial for a person like me.


### 7.3.2. **How we, Parkkings used Agile**
As mentioned up above, We use the Agile methodology together with it's scrum framework.
As suggested by Agile we started by breaking the project down into smaller pieces and
we've made sure to abide to most of it's values and principles if not all. For example the way Value 2 is utilized within our project, We haven't made extra documentation other than user stories so we could start developing swiftly. And throughout the entire development cycle we have included our customers. We did all of this by abiding to Agile's notorious framework; Scrum.

### 7.3.3. **How we, Parkkings used Scrum**
In order to work Agile and get lost due to lack of structure we've decided to make use of Agile's framework: Scrum. We took actions from Scrum such as, assigning scrum roles, working in sprints, keeping a scrumboard and holding frequent retrospectives. You can read more about these things specifically below.


**Scrum roles:**  
As far as the Product owner role went it always stayed the same. The employees from Mediaan would be our Product owners and this never changed. As for Scrum masters however this was different. We've decided to rotate this role around after sprints.

**Product Backlog:**
At the start of the intial sprint, we had been given a case by our product owners which we then took and converted into a cluster of user stories. Those user stories were then verified by our product owners and those stories became our Product backlog.

**StoryPoints:**
User stories have storypoints, storypoints are estimates that indicate how long a team suspect a user story or task takes. I wanted to document this because of the way we as a team decided on what storypoint a task should get. In order to define storypoints for task we all sat together and used a third party user point voting tool. After voting we'd discuss for each member why they submitted the number they voted for. And together we'd reach a conclusion on what it should be. 

Personally I liked this process because more often than not it was rapid and it sparked discussion on user stories and got us all talking about what comes to play when developing certain user stories. Sometimes other developers are able to spot functionalities or checks that you hadn't yet thought of.

The tool we used to vote for storypoints: https://www.planitpoker.com/

**Scrumboard:**   
To keep a clear overview during our work for us as well as the product owners, we kept a scrumboard. Our product owners were very encouraging and fond of this because it helped them see what we are working on at all times. Below I have included a screenshot of our sprintboard during sprint 5. So you get an idea of what our stages of development included.

figure 4: Parkkings sprint 5 scrumboard.
![parkkings sprint 5 scrumboard](/Projects/assets/scrumboardparkkings.JPG)

**Daily stand-ups:**  
We made an agreement to hold Daily stand-ups each workday as soon as every member arrived. These went smoothly, The scrum master would call out someone's name and that person would then get the oppertunity to talk. Everyone gave eachother room to speak and if needed for additional information this was always done respectfully.

**Daily stand-downs:**  
Just like Daily stand-ups we made an agreement to hold Daily stand-downs. However this was less smooth as some members would sometimes have to leave earlier than others. For this the suggestion had been made to send a message in our discord environment with what you would have wanted to say during the stand-down.

**Sprints:**  
During our development we worked in sprints of 3 weeks. Each sprint we'd have a number of tasks to work on and thus a goal to meet. Our official workdays would be on Thursdays and Fridays. However later in the semester our team made an agreement to work on Thursdays and Wednesday in order to merge/do checkups before sprint reviews. On Thursdays we'd meet face to face and on the other day, thus either Friday or Wednesday we'd meet online.

**Sprint reviews:**  
At the end of each sprint we scheduled sprint reviews with our product owners to discuss last sprint and also establish tasks for the following sprint.


**Retrospectives:**  
Throughout our development phase we've done a few retrospective after sprints with our team, sometimes lead by our semestercoach and sometimes even lead by our product owners.

* Excel list:  
  For this retrospective, we sat down with our semestercoach and went down a list of statements to which each team member then gave a 1-5 number signifying whether they agreed with the statement or not. This proved to be rather interesting as certain points did spark, laughter or slight conversation. However this was rather early into the development and our team seemed rather streamlined on most things at the time.
* Hiring team members exercise:  
  For this retrospective excercise Mediaan (POs) challenged us to sit with the whole team look them straight in the eye and tell them whether you would hire them for your hypothetical business or not. This was right after a sprint in which we've had our best perormance thus far. (I am writing this during sprint 4 so not all sprints have been ended yet) So happily for us, everyone hired eachother on the spot.
* Miro board exercise:  
  For this retrospective excercise Mediaan (POs) gave us a board with various types of blanks to fill in below statements. This proved to be challenging as the statements really made you think in certain directions. An example statement would be "The sharks that could bite us". This enforced us to really think about what kind of challenges we could come to face, which we otherwise would have maybe overlooked during a retrospective. 

### 7.3.4. My experiences with Agile and scrum during this project
Here I'd like to lay the focus back a little bit on me, as this is my portfolio and so far what I've written about our workflow has been very teambased or generic.
And that generic,team based information doesn't really make much clear about what I've learnt and have experienced personally. So in order to make my experiences clear I've written some of my experiences and things I've learnt from them below. 

#### 7.3.4.1. **My time as scrummaster**

I find that as scrummaster my team seemed to be asking me a lot more questions. 
And the questions I was being asked were more decision based than technical. As to when I am a fellow developer I am approached with more technical question. I also find that Daily stand-ups and stand-downs aren't as nervewrecking to do as I thought it would be. I was lucky to have been in a team with good morale, We usually had good laughs as I look them all in the eyes and ask them if they needed anything for during their workdays. I'm not sure why it was funny as I think it's a necessary question to ask according to Agile's value number one that prompts teams to value their people. But it made them laugh which raised morale so that's good.

During my time as scrum master I also had to lead a scrum review. This means, setting up a powerpoint and present previous sprint to the stakeholders. To do this it is important you prepare yourself well as you don't want to have any slip ups in front of your stakeholders. As much as I had tried to prepare myself I wasn't quite prepared for just how bad my laptop would handle the application, I usually develop on my PC and it has a lot more power than my laptop. So I did have a bit of a panick realizing that my laptop wasn't taking it well during the review.
However in moments like these it is important to not forget that when a situation like that occurs you do still have your team to back you up. And fortunately I had a very nice team for this course who backed me up during my struggles by taking over the presentation to their laptop so I could present without laptop performance issues. Over all I found my time as scrum master to be informative and positive.

**Feedback I received/What I've learnt while leading a scrum review:**

* Rather than adding a table of contents add a Agenda
* Ask if anyone wants to add anything to the agenda
* You have the option to take a video of a demo  
* Deligate responsibilities, example: one person presents another person carries out the demo

**Do I agree with the feedback/tips I received?**

Overall I do agree with this feedback, in my mind events went terribly because of this laptop performance issue. Perhaps I am being hard on myself, it's just that I had envisioned it to go a completely different route. At fact I had told myself to take lead in the review as best as possible. But instead I stuttered as the application failed to load and the product owners started lagging on my end. 

So the tips they gave are very handy as I will probably continue on with the same setup. I am definitely taking these tips with me for the future.

So in conclusion.. I agree with the feedback, at fact there was more positive feedback than I had expected. :) So Thank you to the product owners, my GP-teacher and Semestercoach for being so kind about the review. 

#### 7.3.4.2. **My time as a teammember/developer**
Because we rotated the scrum master role you spent most of the time working as just a regular developer. You won't hear me complaining about that, I was very fond of being a teammember as it gives you the luxury to mostly focus on yourself and knock out tasks. And because of Stand-ups and Stand-downs you don't risk being completely isolated from your team. As stand-ups and stand-downs enforce oppertunities to communicate with your team. During stand-ups and stand-downs you get a moment where you are free to speak and everyone listens. It makes sure that if you're in need of anything you are heard. The scrum board also is a very nice tool when you are a developer. Being able to accurately establish what you've done and what others are doing. Makes it a lot harder to have misunderstandings within the team. It also helps when handing out tasks as you can easily tell who seemingly has got time to spare.

#### 7.3.4.3. **My overal opinion on Agile and Scrum**
Would I use these methodologies again in the future? 

Yes I would, I really like the structures that this combination of methodologies offer. I think the benefits are very much worth it, And I've had good experiences using this way of working this far. I think adaptability is one of the strongest skills you can possess of in life and this way of working supports that. I also do think communication in teams is very important and this is supported as well. Therefore I am very satisfied.

[Back to table of content ⬆](#table-of-contents)
## 7.4. Our work environment
Here I have listed our work environment platforms and what we used them for.

**Jira:** https://s3-gp-groep2.atlassian.net/jira/software/projects/PAR/boards/1   
used for: Scrum environment, Scrum board, scrum features and backlog  

**Github:** https://github.com/ParKings-inc   
used for: source code hosting, CI/CD pipelines   

<!-- For those interested the repositories are listed underneath the chapter "Technicalities".  
Quick navigation:  
[See repository list](#repositories) -->

**Discord:** not public  
used for: Communication

[Back to table of content ⬆](#table-of-contents)
<!-- Professional skills -->
# 8. Reflection
It's been a long period of time working on this group project. 
And it's always good to look back at things so you can give your brain the oppertunity to pause amidst the chaos. To really think about the observations and experiences you've had in order to find the true meaning in what the !@#$@!$ just happend. With that being said, here you can read my self reflection; 

To keep things clear for myself and not just create one big clustered self reflection, I decided to approach this reflection by dividing them into sprints. By answering the same set of questions for each sprint I hope to create a clear overview of how I've felt during this project and what I've done. This way my end result should cover each timeframe thoroughly. And in the end (in consideration of those who don't like to read so much) I will compactly conclude my reflections into one.


**Sprint 1 reflection**  

**What I've worked on during this sprint**    
During this sprint, we mainly worked on setting up our Product backlog. I found myself as lead of writing user stories. So I took the case delivered to us by our product owners and started disecting it into 1 central, compact google docs file filled with user stories. Writing user stories for each milestone, included: Writing the userstory, writing the according acceptance criterea, deciding the definition of ready and the definition of done. We also all agreed to study up a bit of REACT as we had decided that was the framework we would be using for the front end of the application.

**Did I accomplish my work during this sprint?**    
Yes, mostly. However, I think I should have asked for more reviews/confirmations on the user stories as it is rather hard to write them in advance. As you kind of instantly need to visualize the application. And our application is rather intricate to just be able to write user stories for without forgetting or overlooking anything.

**What I've learnt during this sprint**  
Writing acceptance critereas, Writing definitions of ready and definitions of done.

**How do I look back to this sprint?**  
This sprint wasn't yet very taxing as for me it was mostly still writing user stories. As well as doing a little bit of studying ahead on REACT.

**Difficulties we've faced during this sprint and how we got over it.**  
I think during this sprint there weren't many difficulties if any at all.  
* * *  
**Sprint 2 reflection**

What I've worked on during this sprint

Did I accomplish my work during this sprint?

What I've learnt during this sprint

How do I look back to this sprint?

Difficulties we've faced during this sprint and how we got over it.

* * *
**Sprint 3 reflection**

What I've worked on during this sprint

Did I accomplish my work during this sprint?

What I've learnt during this sprint

How do I look back to this sprint?

Difficulties we've faced during this sprint and how we got over it.
* * * 
**Sprint 4 reflection**
What I've worked on during this sprint

Did I accomplish my work during this sprint?

What I've learnt during this sprint

How do I look back to this sprint?

Difficulties we've faced during this sprint and how we got over it.
* * * 
**Sprint 5 reflection**
Hasn't finished.
* * * 
## 8.1. Full project reflection
Project hasn't yet finished.

And that concludes my portfolio for the S-DB-GPS3-S3 course.  

<span style="font-family:Papyrus; font-size:0.8em;">Thank you for reading  
 Justice for Betty ✊
 </span>

[Back to table of content ⬆](#table-of-contents)
* * *
# 9. Appendix 

## 9.1. Agile Values

**1. Individuals and interactions over processes and tools** [🔙](#722-working-agile)
>
>The first value gets straight to the core of Agile methodology: the focus is on the people. You can use the best processes and tools available to support your projects, but they will only work if your people are doing their best work. Your team is your most valuable resource. Communication plays a key role here — when people interact with each other regularly and share their ideas, they build better products.  
> 
>Jim Highsmith, one of the authors of the Agile Manifesto, wrote about the importance of the “mushy stuff,” meaning prioritizing people over processes. Rather than simply proclaiming that people are the most important factor, he advises that software developers actually act as if people are the most important factor.


 **2. Working software over comprehensive documentation**
>
>Before Agile practices were fully implemented, teams would spend hours creating exhaustive documents with technical specifications, requirements, and more. These lists would be prepared before developers started to write the code, meaning the whole process was delayed as the documentation took so long to compile.
>
>The Agile philosophy is to streamline these documents and condense the information into user stories. These stories equip the developer with all the details they need to start working on the software and get it ready for release. The idea is to accelerate the launch process and make product tweaks in the early stages, improving the software in future iterations.

**3. Customer collaboration over contract negotiation**
>The third value of the Agile Manifesto highlights the importance of customer collaboration. This is viewed as superior to contract negotiation, which involves outlining product requirements with the customer before commencing the project and then renegotiating these deliverables at a later stage. The issue here is that the customer is not engaged throughout the development cycle, so teams lose out on user feedback that could enhance the product.  
>
>When you bring your customers into the development process, you can ask for their opinions regularly and take their suggestions on board. By delving into their specific needs while the software is still being built, developers can gain valuable insights to create the ultimate user experience.

**4. Responding to change over following a plan**
>Traditional methodologies advocated for as little change as possible, recognizing that significant alterations could cost time and money. The aim was to create a comprehensive plan that followed a structured, linear path and avoided obstacles where possible.  
>
>The Agile mentality turns this rigid method on its head, arguing that change can benefit the software development process. When you embrace change, you open yourself up to new possibilities and ways to improve. Agile teams work in short, iterative cycles, meaning they can react quickly and implement changes on a continuous basis. This ultimately leads to better products.
>
>These four values form the basis of Agile software development, highlighting key priority areas for teams to focus their energies on. The core values are supported by the 12 Agile Manifesto principles.  
  
[Back to table of content ⬆](#table-of-contents)  
* * * 
## 9.2. Agile principles 
**1. Our highest priority is to satisfy the customer through early and continuous delivery of valuable software.**[🔙](#722-working-agile)
>What is the number one rule in software development? Keep your customer happy. Aim to deliver software to your users at regular intervals throughout the project life cycle, rather than keep them waiting for one final deliverable.

**2. Welcome changing requirements, even late in development. Agile processes harness change for the customer's competitive advantage.**
>Software developers should be capable of handling last-minute changes to a project. They should be flexible enough to turn these changes into improvements quickly, minimizing delays and ensuring an uninterrupted flow of work. 

**3. Deliver working software frequently, from a couple of weeks to a couple of months, with a preference to the shorter timescale.**
>Agile teams break large projects down into short timelines to guarantee regular delivery. In the Scrum methodology, these timelines are known as sprints, which often run between one and four weeks long.

**4. Business people and developers must work together daily throughout the project.**
>As mentioned, collaboration is key to Agile project management. When the project stakeholders communicate on a daily basis, it minimizes the risk of confusion and ensures that everyone’s goals remain aligned.

**5. Build projects around motivated individuals. Give them the environment and support they need, and trust them to get the job done.**
>When you have the right people for the task, the project is more likely to be successful. Spend time choosing the perfect team, equip them with the resources they need, and trust them to deliver exceptional results.

**6. The most efficient and effective method of conveying information to and within a development team is face-to-face conversation.**
>Barriers are broken easily when teams can converse in person. Co-locate teams where possible to promote good communication and boost the flow of information. In a remote working situation, Zoom is a great alternative to phone or email, enabling people to interact more effectively via camera.

**7. Working software is the primary measure of progress.**
>To keep your customers satisfied, you must deliver high-quality software. That is your ultimate priority and your metric for success — everything else is a secondary consideration.

**8. Agile processes promote sustainable development. The sponsors, developers, and users should be able to maintain a constant pace indefinitely.**
>Agile teams must be consistent throughout their project life cycle, maintaining their speed throughout. This means they can sustain a constantly evolving environment without succumbing to delays.

**9. Continuous attention to technical excellence and good design enhances agility.**
>In Agile, you don’t just deliver one good product and call it a day — your focus should be on continuous improvement and innovation. Each iteration should bring with it a new update, feature, or advancement of some kind.

**10. Simplicity — the art of maximizing the amount of work not done — is essential.**
>The Agile approach is to not overcomplicate things: meet your requirements and do just enough to complete the task. Don’t waste time with additional steps that don’t add any real value to your product.

**11. The best architectures, requirements, and designs emerge from self-organizing teams.**
>Why micromanage teams when they are skilled enough to work on their own? By allowing them to work within their own structures, you create more room for ideas to flourish, ultimately delivering better results.

**12. At regular intervals, the team reflects on how to become more effective, then tunes and adjusts its behavior accordingly.**
>When you review team performance regularly, you can spot issues before they escalate, as well as potential areas for improvement. A healthy Agile team is one that self-reflects in order to eliminate unhelpful practices and advance skills.


[Back to table of content ⬆](#table-of-contents)
* * * 

## 9.3. Agile Benefits 

**1. Satisfied customers** [🔙](#93-agile-benefits)
>By involving customers in the development process, Agile teams keep them in the loop and show that they value their opinion. Stakeholders want to be engaged throughout the project life cycle so they can offer feedback and ensure that the final product will be suited to their needs. These tailor-made deliverables will likely improve the overall user experience and boost customer retention.

**2. Improved quality**
>Agile methodologies use an iterative approach to project management, meaning processes are improved upon each time an interval is repeated. This consistent focus on improvement and quality control is one of the core principles of Agile, and it helps to create superior products.

**3. Adaptability**
>The central theme of Agile is flexibility. Agile teams are responsive to change, even at the last minute, and can adapt to it without much disruption. Project deliverables are not set in stone, so teams can easily reassess their plans and adjust their priorities to align with updated goals. Being adaptable means teams can deliver consistently and manage clients’ changing requirements effectively.

**4. Predictability**
>Agile teams work in short time periods, sometimes referred to as sprints. These fixed durations (e.g., two weeks) make it easier for project managers to measure team performance and assign resources accordingly. It is also easier to predict costs for shorter time periods than for a long-term project, simplifying the estimation process. 

**5. Reduced risk**
>Developers regularly assess progress during sprints, meaning they have better visibility into the project and can spot potential obstacles quickly. These minor issues can be tackled before they escalate, creating an effective risk mitigation process and giving the project a greater chance of success.

**6. Better communication**
>Agile teams prioritize face-to-face communication and continuous interaction. They will usually conduct daily meetings to ensure everyone is on the same page and working towards the same objectives. By regularly communicating with each other, they eliminate potential confusion to successfully achieve their objectives. 


>**source 4 Agile values, 12 Agile princples and 6 Agile benefits:** https://www.wrike.com/agile-guide/agile-manifesto/  
* * * 

[Back to table of content ⬆](#table-of-contents)
# 10. Sources

https://www.wrike.com/project-management-guide/faq/what-is-agile-methodology-in-project-management/
https://thedigitalprojectmanager.com/projects/pm-methodology/project-management-methodologies-made-simple/  
https://hubstaff.com/tasks/state-of-remote-project-management  
https://www.redhat.com/en/topics/devops/what-is-agile-methodology  
https://www.mendix.com/agile-framework/#:~:text=Scrum%20is%20the%20most%20common,%2DDriven%20Development%20(FDD).
https://www.wrike.com/agile-guide/agile-manifesto/  
https://www.scrum.org/resources/what-is-scrum

[Back to table of content ⬆](#table-of-contents)