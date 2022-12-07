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

# Table of content


# Introduction

During semester 3 of the Fontys HBO-ICT demand based programme, Fontys challenges it's students to complete 2 courses. Namely an individual course and a group project course. This document is written with focus on my group project course experience. If you want to read more about my experience and what I've been doing for the individual course you can find more information in the central portfolio document [here](https://github.com/LisaKarto/Portfolio-SEM3).  

The group project course enforces you to work alongside multiple other developers on a project at once for a partner in education, which helps you build your coding skills as well as your social skills all while giving you a sense of the "real world". In this document you'll find the information on topics such as, who the stakeholders for the project are, Our workflow during the project, what the project is and how it improves the current business process, what ethical decisions we've had to make and much more. You will also be able to find all of our work in this document.

# Stakeholders
 
## **Professors**
During the semesters you have designated professors that will grade your work, 
Some are more involved with the individual course and others are more involved with the group course. Here are listed the professors I've had related to the group project course and what roles they haad during this course.

**Name**: Thijs Naus  
**Role**: Group project course tutor  
**Actions**: Giving feedback, available for support/advice, grading overall process, observing over all process, lectures when necessary, pep talks

**Name**: John Wijnen   
**Role**: Semester coach  
**Actions**: Leading retrospectives, available for support/advice, giving feedback, grading overall process

* * *
## **Our team, Parkkings**

At the start of the course the class gets tasked to construct teams of about 7 members to work with for the following 4 months. And naturally everyone settles with whoever they've coincidently have been sitting at the same table with. And so the team Parkkings was made. I've worked with these people for several months and it's safe to say that I haven't the faintest idea of who they really are. 

### **Who are we**

Our team Parkkings consists out of Fontys HBO-ICT students that follow the demand based programme. We all share the same profile, software engineering. 

### **Our goal**
We hope to build a functional product to satisfy our product owners, teachers and pass the semester whilst learning new skills and building upon our already existing skills.

### **Members and roles**
To form a team you need members and each member usually holds some sort of role. Below are listed the members of Parkkings as well as some information on our the roles, we've had during this semester.

#### **Members:**
* Atalay, Gökay - student, software engineering
* Derks, Jaimy  - student, software engineering - (Start semester - December)
* Eijnde, Davey, van den - student, software engineering
* Kartodimedjo, Lisa - student, software engineering
* Meegdes, Lean - student, software engineering
* Peeters, Ramon - student, software engineering
* Walraven, Jordy - student, software engineering

#### **Roles**
We decided not to hold any static roles so everyone can get in touch with a little bit of everything at once. So roles switched during each sprint. So at the end we've all had some experience in various scrum roles as well as coding experiences in each field. Below I've listed the roles we've all shared.

**Technical roles:**
* Working on the back-end of the software product
* Working on the front-end of the software product
* Flexing between/assisting

**Scrum roles:**
* Scrum master
* Team member



* * *

## **Our assigned Partner in Education, Mediaan**
For this semester Fontys assigns it's groups with
These partners often come in and offer projects to work on for students. Partners and help students grow into their careers.

Want to see specific cases? go [here](https://mediaan.com/cases-index).
### **Who are they and what do they do?**
Mediaan is a international company in the field of business transofrmation and tech innovation.
They also offer consultancy for companies that would like their organization to become more data-driven. 
The mediaan team combines digital, business and organizational expertise to achieve their goals and/or help other companies achieve their goals.
Mediaan promises transparancy, skills and agility to their customers. 

read more about them, [here](https://mediaan.com/about-us).


### **Where to find them**
In case of interest I have listed Mediaan's socials underneath. 

**Official website:** https://mediaan.com/  
**Instagram:** https://www.instagram.com/mediaan.vibes/  
**LinkedIn:** https://www.linkedin.com/company/mediaan/  
**Faceboook:** https://nl-nl.facebook.com/MediaanABS  
**Youtube:** https://www.youtube.com/channel/UCbX3NvsTGNCc-XqJgH-4i6g  
**Twitter:** https://twitter.com/mediaan  

### **Product owners**
Product owners are the 
Their role during the development process is to 

Mediaan as a whole has a lot of employees, but the people that we've been fortunate enough to have as product owners are the following people: 

**Kaj Nellissen**, Product owner    
**Timothy Hamilton**, Product owner  
**Ramona Domen**, Product owner on occasion 

* * *
# The project

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

From that information we have set up a bunch of user stories based on each milestone, which you can find in our [Jira environment's backlog](https://s3-gp-groep2.atlassian.net/jira/software/projects/PAR/boards/1/backlog). The use stories are marked their milestone.

<!-- Business process -->
## How does our software support the parking garages?
For this chapter I want to focus on the parking reservations process of a parking space soley. Other processes may be described in the future. 

I believe our system will have impact during the parking reservations process by ensuring a parking space for visitors, because our system lets a visitor know in advance wether a parking space is available or not for the specified time at which the visitor want to park. However a visitor now needs to reserve a parking space in advance if they want their parking space to be ensured. So in order to keep the benefits in the visitor's favour the system's end to end journey for the reservation process needs to be non taxing. So our team has done it's best to ensure that more about that ux/ui listed below underneath the chapter [UI/UX]().

Below you can read/follow the analysis that has been done to have reached the above conclusion. if that's not what you're into feel free to [skip to the next chapter](#technicalities).

## The reservation business process analysis
I've analysed the business processes by comparing them to eachother, first you will find the parking space process without the aid of our software system alongsides it's flaws and why they're flaws. Then you will find the same process but this time aided by our software system, alongside will be the same list of flaws but with an explaination with why in this use case those same flaws are eliminated. Symbolistic diagrams of the processes will also be included to clearify. Lastly you can read the conclusion drawn from the evidence found during the analysis.


### **parking reservations process without our software system**
To accurately carry out our analysis we must first describe the situation without any aid of software. 

**current flow:** A visitor shows up at a parking garage and enters through the gate. A visitor will then look around to see if there's any parking spaces available. A visitor will then find a parking space and park their car there.
<!-- insert diagram here -->

current flow diagram, For ease you can refer to the below activity diagram that serves as a symbolistic illustration on the current process flow:  
 ![Activity diagram no software](/Projects/assets/AD%20no%20software.png)

**Exceptions:** 
* busy hours, during busy hours the visitor can have issue finding a spot if able to find a spot at all.
  * no spots, if the visitor then finds there's no spots at all. The visitor will then have to either wait around for a spot to be freed with incoming information or go home in defeat.
  
**Current flaws:** 
* **Parking space uncertainty:**
  Without reservations there is no certainty for visitors to actually be able to find a parking space during busy hours.
* **Not time efficient:**
  Driving around looking for a parking spot may cose a visitor a lot of time during busy hours.
* **Loss of customers/potential buyers:**
  Driving/waiting around for a spot is tedious, visitors might not want to revisit because of this reason. The parking space will be associated with a bad experience and so will their destinations. This causes a loss of potential customers and thus also a loss of money that could have been earned.

### **parking reservations process using our software system**
To accurately carry out our analysis we must now describe the situation with the aid of software. 

**software aided flow:** A visitor uses our web application to make a reservation, a visitor chooses a date and time to park. The system lets the visitor know wether or not the visitor can park at that time. If the visitor is able to park at that time the system will assign a designated parking space to the visitor. Now the visitor has a guaranteed spot for the day and time they arrive. On the reserved date a visitor simply drives up to the garage, identifies themselves at the gate and parks in their designated spot.  

software aided flow diagram, For ease you can refer to the below activity diagram that serves as a symbolistic illustration on the software aided process flow:  

![Activity diagram no software](/Projects/assets/AD%20software.png)  

**Eceptions:**
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

### **Conclusion**
I conclude out of the analysis I've carried out above that our software will have a positive impact on the finding a parking space process at parking garages. Yet a downside may be that visitors have to reserve a spot in advance. But I suspect it's better and cheaper than going out to a parking garage only to find out there's no available spaces and losing money on gasoline aimlessly driving around for a space whilst wating for a space to clear up. And thus would cause overall benefits for anyone making use of the parking garages and even for stores near parking spaces. Why not grab a quick red bull since we're close? :) ~~Red bull does not sponsor this portfolio~~

##### other business processes tackled by our software system may be described in the future
<!-- Web application -->
# Technicalities
Software consists out of a bunch of building blocks, building blocks like languages and frameworks and a lot more that's going on below that. But the way we software developers create it is by utilizing languages and frameworks. Now decisions need to be made, which languages and frameworks do you use for what project and why? In this chapter I will list what we have made use of during our building process and why. You will also find diagrams to help clearify these architectural structures.

For this semester Fontys has challenged it's software engineering students to set up a distributed architecture since this has many benefits and is commonly used in software development today. So we better get to learning. This is the reason that we've chosen to set up REST api's for the backend. Fontys also wanted us to use a javascript based framework for the front end and that pairs well with a REST api distributed architecture. 

## Architecture and infrastructure

### Languages and frameworks used:
Underneath I have listed the languages alongsides the frameworks we have decided to use for the project.

**Backend:** 
* **Main REST API:** C# - ASP.NET
* **CMS REST API:** C# - ASP.NET
* **DATABASE:** SQL server

**Frontend:**
* **MAIN UI:** Javascript, HTML, CSS - REACT
* **CMS UI:** Javascript, HTML, CSS - REACT

**External services:**
* Google Oauth 2.0

### Architecture diagram
<!-- cultural differences and ethics -->
# Cultural & Ethical Decisions we've had to make 
## Ethical decisions
## Cultural decisions

# Website design
<!-- UX/UI -->
## UI

### design
## UX 

### decisions
<!-- Agile method -->
# Our working process

## Agile Method
### scrum
#### kanban board
#### sprints
#### retrospectives

## Our environment
## Team excercises we've done

Hiring team members  
Miro board
<!-- Professional skills -->
# Reflection

## dificulties we've faced as a team and how we got over it 

## My take on all of it and what I've learnt


