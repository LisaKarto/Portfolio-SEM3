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
# Table of content

#  Introduction

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
* busy hours, during busy hours the visitor can have issue finding a spot if able to enter the garage at all.
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

other business processes tackled by our software system may be described in the future
<!-- Agile method -->
# Project working process
Before really diving into the technical details of the project, 
I'd like describe our team's way of working first. For those who would like to skip this chapter and jump ahead to the technical details please refere [here](#project-technicalities). 

I've first written a bit of information on the methods we've used to guide our workflow, if you want to skip that and get directly into how we utilized them during our project time, go [here](#workflow-parkkings). 

## Working and structure
During this semester there's a big focus drawn to a developer's way of working, products can be made just like any passion project can be made in someone's backyard.
But me.. I never managed to finish the guillotine I'd tried to built from scratch in my backyard, why? Because I had no plan and no working structure. 


 And so I've learnt that; if you neglect structure during your working phases you may find yourself losing track of your project entirely. Which may lead to a decrease in productivity or even complete neglection of the project itself. Therefore to help prevent this from happening and ease things within one's own mind it is important to adopt a good, structured way of working. This is especially important while developing in a team.
A good working flow, with rules and structure can help to prevent misscommunication errors or other type of errors within a team. For we are all human after all, and working alongside eachother can be immensely challenging but with good structure we may work in complete cohorent unity. And if lucky, also harmony. If unlucky harmony without the "ony".


## Agile 
Sadly, I wasn't the first person alive and yes, I do blame my parents. However out of tragedy comes something good and in this case, this good something is the fact that other people have done important work for me. Such as creating the Agile way of workings. But because of that I also had no idea of it's existence, let alone it's working. However it is important to know considering it's commonly used in development teams today. But how does it work? And why do we use it? You can find the answers to that question in the following section where I've established a small research on Agile and it's most frequently used framework; Scrum.

### **What is Agile**
> Agile is an approach to software development that seeks the continuous delivery of working software created in rapid iterations. - Red hat

As the name Agile suggests, Agile designs it's teams to be able to pivot quickly and adapt to change without much difficulty. This way of working has gained a lot of popularity over the past 2 decades. When working according to the agile methodology you work by breaking your project into several phases, staying in constant collaboration with stakeholders and continuesly imrpove your product at every stage. Agile guides teams by enforcing them to engage in project planning, executing and evaluating. 

Agile puts focus upon the way of thinking about collaboration and workflows with a set of values to guides a team's choices.  

### **How do you work Agile** 
Working Agile is working according to the agile values and principles. Below I have listed a simple overview of these values and principles. For more information on these values and principles you can refer to the appendix. (The appendix has anchors back to this part of this document, so you don't have to fear getting lost.)  Or you can redirect to wrike's documentation on agile, which I've used as a source [here](https://www.wrike.com/agile-guide/agile-manifesto/).

quick navigation:  
[Check out valeus in the appendix](#agile-values).  
[Check out principles in the appendix](#agile-principles). 

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

#### **Agile frameworks**
Agile doesn't come with a singular approach and is not a set of prescriptions listing exactly what actions to take. But then how do you really work with it? You can develop your own way of working and still abide to Agile. However to save teams some time, they have the option to choose out of various Agile frameworks and follow accordingly. To list a few of the popular ones: Scrum, Kanban and Extreme programming(XP). However our team Parkkings have made use of the Scrum Agile development framework, therefore in this document I'll only focus on that framework in particular and you can learn more about the others on your own.

If you are interested in the other frameworks listed, you can find more information here:

* Kanban: https://www.agilealliance.org/glossary/kanban/  
* Extreme programming(XP): https://www.agilealliance.org/glossary/xp/  

For our project we decided to make use of the scrum framework within Agile. Scrum is a framework for managing work designed best working for teams of 5-9 members. (Not all scrum is Agile)


### scrum
#### scrum board
#### sprints
#### retrospectives

 
## Workflow parkkings
### **Why we use Agile**
First and foremost, obviously
### How we, Parkkings used Agile

### How we, Parkkings used Scrum

*  Hiring team members exercise  
  For this excercise Mediaan challenged us to sit with the whole team look them straight in the eye and tell them whether you would hire them for your hypothetical business or not. 
* Miro board exercise  
  For this excercise Mediaan gave us a board with various types of blanks to fill in. 

### My experiences 

#### My time as scrummaster

##### Leading scrum reviews

Feedback I received/What I've learnt: 
#### My time as a teammember
#### My overal opinion
Would I do it again? ..

Yes. 
## Our work environment

**Jira:**  
**Github:**  
**Discord:**


# Website design
<!-- UX/UI -->
## UI

### design
## UX 

### decisions

<!-- Web application -->
# Project Technicalities
Software consists out of a bunch of building blocks, building blocks like languages, frameworks and a lot more that's going on below that. But the way we software developers create it is by utilizing languages and frameworks. So decisions need to be made, which languages and frameworks do you use for what project and why? In this chapter I will list what we have made use of during our building process and why. You will also find diagrams to help clearify these architectural structures.

For this semester Fontys has challenged it's software engineering students to set up a distributed architecture since this has many benefits and is commonly used in software development today. So we better get to learning. This is the reason that we've chosen to set up REST api's for the backend. Fontys also wanted us to use a javascript based framework for the front end and that pairs well with a REST api distributed architecture. 

## Architecture and infrastructure
In this section you will find the architecture and infrastructure of the product, listed followed with compact substantiations where needed.
### **Architecture**
In this section you can read about the architecture of our product.
### Languages and frameworks used:
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
### Languages and frameworks used architectural diagram:
Below you can view a diagram that symbolizes the interaction/flow between these languages and frameworks.
![Languages and frameworks diagram](/Projects/assets/Languages_and_frameworks_architecture_diagram.png)


### **Infrastructure**
Now that we know what languages and frameworks are used in the project, it may be nice to go over how these applications interact with eachother. You can find such information here. First I will list what applications make the whole Parkkings application.

The Parkkings application consists out of: 

**Clients:**  
Guest User interface (used by visitors/customers):   
Content Management system (used by admins):  

**Developers:**  
REST API:  
MSSQL database:
### Infrastructure diagram
![Parkkigs infrastructure](/Projects/assets/architectuur_parkkings.drawio.png)
<!-- cultural differences and ethics -->
# Cultural & Ethical Decisions we've had to make 
## Ethical decisions
## Cultural decisions


<!-- Professional skills -->
# Reflection
It's been a long period of time working on this group project. 
And it's always good to look back at things so you can give your brain the oppertunity to pause amidst the chaos. To really think about the observations and experiences you've had in order to find the true meaning in what the !@#$@!$ just happend. With that being said, here you can read my self reflection; 

To keep things clear for myself and not just create one big clustered self reflection, I decided to approach this reflection by dividing them into sprints. By answering the same set of questions for each sprint I hope to create a clear overview of how I've felt during this project and what I've done. This way my end result should cover each timeframe thoroughly. And in the end (in consideration of those who don't like to read so much) I will compactly conclude my reflections into one.


## Sprint 1 reflection

What I've worked on during this sprint

Did I accomplish my work during this sprint?

What I've learnt during this sprint

How do I look back to this sprint?

Difficulties we've faced during this sprint and how we got over it.

## Sprint 2 reflection

What I've worked on during this sprint

Did I accomplish my work during this sprint?

What I've learnt during this sprint

How do I look back to this sprint?

Difficulties we've faced during this sprint and how we got over it.

## Sprint 3 reflection

What I've worked on during this sprint

Did I accomplish my work during this sprint?

What I've learnt during this sprint

How do I look back to this sprint?

Difficulties we've faced during this sprint and how we got over it.

## Sprint 4 reflection
What I've worked on during this sprint

Did I accomplish my work during this sprint?

What I've learnt during this sprint

How do I look back to this sprint?

Difficulties we've faced during this sprint and how we got over it.

## Sprint 5 reflection
Hasn't finished.

## Overall project reflection
Project hasn't yet finished.

And that concludes my portfolio for the S-DB-GPS3-S3 course.  

<span style="font-family:Papyrus; font-size:0.8em;">Thank you for reading  
 Justice for Betty ✊
 </span>

* * *
# Appendix 

## Agile Values

**1. Individuals and interactions over processes and tools** [🔙](#how-do-you-work-agile)
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
  
* * * 
## Agile principles 
**1. Our highest priority is to satisfy the customer through early and continuous delivery of valuable software.**[🔙](#how-do-you-work-agile)
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

>**source four Agile values and 12 Agile princples:** https://www.wrike.com/agile-guide/agile-manifesto/  
* * * 
# Sources

https://www.wrike.com/project-management-guide/faq/what-is-agile-methodology-in-project-management/
https://thedigitalprojectmanager.com/projects/pm-methodology/project-management-methodologies-made-simple/  
https://hubstaff.com/tasks/state-of-remote-project-management  
https://www.redhat.com/en/topics/devops/what-is-agile-methodology  
https://www.mendix.com/agile-framework/#:~:text=Scrum%20is%20the%20most%20common,%2DDriven%20Development%20(FDD).
https://www.wrike.com/agile-guide/agile-manifesto/