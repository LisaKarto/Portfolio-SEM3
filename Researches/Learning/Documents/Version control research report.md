<h1> Version control research report</h1>

<h1> Table of content </h1>

- [Introduction](#introduction)
- [The project](#the-project)
- [What version control methods best suit planpal?](#what-version-control-methods-best-suit-planpal)
  - [What is version control?](#what-is-version-control)
  - [What are the benefits of version control?](#what-are-the-benefits-of-version-control)
  - [Version control systems](#version-control-systems)
    - [**What is Bazaar**](#what-is-bazaar)
    - [**What is Mercurial**](#what-is-mercurial)
    - [**What is Git**](#what-is-git)
- [Version control platforms](#version-control-platforms)
    - [**What are version control platforms**](#what-are-version-control-platforms)
    - [**What version control platforms are available?**](#what-version-control-platforms-are-available)
    - [**What is BitBucket**](#what-is-bitbucket)
    - [**What is GitHub**](#what-is-github)
    - [**What is GitLab**](#what-is-gitlab)
- [Conclusion](#conclusion)
- [DOT framework](#dot-framework)
- [Sources](#sources)


# Introduction

Here you can find the documented version control research report for planpal.  
This research has been carried out to answer the following main question:  
* **What version control methods best suit planpal?**


To reach the answer to this main question the following questions must be answered: 

  - What is version control?
  - What are the benefits of version control?
  - What are version control systems?
    - What version control systems are available?
    - Which one of these version control systems best fit planpal?
  - What are version control platforms? 
    - What are the benefits of version control platforms?
    - What version control platforms are available?
    - Which one of these version control platforms best fit planpal?


At the end of this document I have written a conclusion where I revisit the questions once again and provide my final answer to the main question; "What version control methods suit planpal?".

This research has been carried out with the Design oriented Triangulation(DOT) framework in mind. For those interested I have written what DOT framework methods I've used during this research at the end of this document.


# The project

As the main question suggests, this research is aimed at a specefic project, namely "planpal".For this particular subject the project size and development team size have impact on the results, so I'd like to provide some information on the project the research is being done for.

**Project name:** Planpal  
**Size:** Medium   
**Development team:** 1 person, has to be open to expansion  
**Has stakeholders:** true  
**Open to outsourcing:** true  
**Application:** Distributed architecture, REST api  
    **Front-end:** Vuejs Javascript  
    **Back-end :** Springboot Java  
    **Database:** relational database SQL  


# What version control methods best suit planpal?
In the following section I will answer a few sub questions that will lead towards the answer to the main question. It's important to adress these sub questions as they lay the base to the main question.

## What is version control?
Version control, is the practice of tracking and managing changes to computer programs, documents and could also be applied to other software or digital files.

## What are the benefits of version control?

* Tracked work, meaning you can revert to history (backups)  
  
* Source code sharing, improves ability to cooperate (increased speed)  
   
* Increase code management  
   

## Version control systems
Managing version control manually has a lot of flaws as well as it is time consuming and honestly.. tedious. But it's a very essential practice, used in almost every development process from individual passion projects to large projects made in teams. So naturally the smart brains that roam around this planet have invented something that assists you in this process. Namely, Version control systems. 


**What type of version control system best suits my project?**     
Firstly there's 2 distinctive types of version control systems, namely a centralized version control system and a distributed version control system.

**Centralized version control systems**  
Centralized Version Control is a version control system using server/client model and server contains all the history of source code.

**distributed version control systems**  
Distributed Version Control is a version control where each client can have same copy of source code as server has and both server and client maintain history of source code.

**Which option suits Planpal?**    
Planpal is a project that should be eligable to be outsourced to parties all over the world, therefore the best option for Planpal is to use a distributed version control system. 

**What version control systems are available?**  
Below 3 popular distributed version control systems that have been compared to find the most suitable version control system to planpal.

### **What is Bazaar**

**Description:**  Bazaar is a version control system that helps you track project history over time and to collaborate easily with others. Whether you're a single developer, a co-located team or a community of developers scattered across the world, Bazaar scales and adapts to meet your needs.   

**original developer:** Canonical and community  
**Initial release:** 26 March 2005

**features:**   
* It has commands similar to SVN or CVS.
* It allows you to be working with or without a central server.
* Provides free hosting services through the websites Launchpad and Sourceforge.
* Supports file names from the entire Unicode set.
  
**pros:**  
* Directories tracking is supported very well in Bazaar (this feature is not there in  tools like Git, Mercurial)
* Its plugin system is fairly easy to use.
* High storage efficiency and speed. 
  
**cons:**  
* Does not support partial checkout/clone.
* Does not provide timestamp preservation.    
  
**open source:** Yes   
**Cost:** Free  
**Website:** http://bazaar.canonical.com/en/  
**Tutorial:** http://doc.bazaar.canonical.com/latest/en/mini-tutorial/

[^ Back to table of content](#table-of-content)
### **What is Mercurial**

**Description:**  Mercurial is a free, distributed source contrtol management tool. It offers you the power to efficiently handle projects of any size while using an intuitive interface. It is easy to use and hard to break, making it ideal for anyone working with versioned files.    

**original developer:** Olivia Mackall  
**Initial release:** 19 April 2005

**features:**   
* High performance and scalability.
* Advanced branching and merging capabilities.
* Fully distributed collaborative development.
* distributed
* Handles both plain text and binary files robustly.
* Possesses an integrated web interface.
  
**pros:**  
* Fast and powerful
* Easy to learn
* Lightweight and portable.
* Conceptually simple  
  
**cons:**  
* All the add-ons must be written in Python.
* Partial checkouts are not allowed.
* Quite problematic when used with additional extensions..    
  
**open source:** Yes   
**Cost:** Free  
**Website:** https://www.mercurial-scm.org/    
**Tutorial:** https://www.mercurial-scm.org/wiki/Tutorial

[^ Back to table of content](#table-of-content)
### **What is Git**

**Description:** Git is a version control management system that allows you to keep track of your source code history. Utilizing Git's features can make your project's development a lot more efficient, especially when developing in large groups. Git is mainly popular for it's efficiency and simplicity.   

**original developer:** Junio Hamano  
**Initial release:** 7 April 2005  

**features:**   
* Provides strong support for non-linear development.
* Distributed repository model.
* Compatible with existing systems and protocols like HTTP, FTP, ssh.
* Capable of efficiently handling small to large sized projects.
* Cryptographic authentication of history.
* Pluggable merge strategies.
* Toolkit-based design.
* Periodic explicit object packing.
* Garbage accumulates until collected.  
  
**pros:**  
* Super-fast and efficient performance.
* Cross-platform
* Code changes can be very easily and clearly tracked.
* Easily maintainable and robust.
* Offers an amazing command line utility known as git bash.
* Also offers GIT GUI where you can very quickly re-scan, state change, sign off, commit & push the code quickly with just a few clicks.  
  
**cons:**  
* Complex and bigger history log become difficult to understand.
* Does not support keyword expansion and timestamp preservation.     
  
**open source:** Yes   
**Cost:** Free  
**Website:** https://git-scm.com/  
**Tutorial:** https://git-scm.com/docs/gittutorial


**Which one of these version control systems best fit my project?**  
  
Out of these 3 version control systems, I conclude that [Git](#what-is-git) is the best suited for my project and it's requirements because; Git has a large community surrounding it and is very popular, because of that a lot of other tools are familiar with Git
And most developers will know Git, making outsourcing and cooperation easier as there's a bigger chance that theyre familiar with it's working.
Beginner friendliness. Optimized Guis
Fast and efficient
Supports most uses. So using Git best fits planpal's team standards

# Version control platforms

### **What are version control platforms**

Version control platforms offer softwre developers the ability to share and host their code. Nowadays these platforms come with additional features, such as project management features. Version control platforms boost collaborative working amongst developers. Together with version control systems developers can share, develop and track their projects.

**What are benefits of version control platforms?**

* Central Source code hosting
* Collaborative tools
* CI/CD functions (often offered)
* Project management functions (often offered)
* Additional backup

### **What version control platforms are available?**
Below 3 popular version control platforms that have been compared to planpal's needs.

### **What is BitBucket**

**Description:**   BitBucket is a source code hosting service that offers you to host an unlimited number of private repositories for teams up to 5 members. BitBucket also offers built-in CI/CD and has the best-in-class jira intergration. Which makes sense because both Jira and Bitbucket are owned by Atlassian.
**original developer:**  Jesper Noehr
**Initial release:** 2008

**features:**   
* Pipelines is a CI/CD service that displays the entire development life cycle of the product. On BitBucket, developers can track the deployment progress of the software. 
* Branch permissions: developers can allow specific people access to a repository;
* Integrations with Slack, Bamboo, Jenkins, HipChat, Crucible, and other tools;
* A Mac and Windows client, and an Android app, called Bit Beaker;
* BitBucket Snippets: the creation of snippets for the codebase;
* Documentation and wiki;
* Search panel for codebase navigation;
* A lot of add-ons on the Atlassian marketplace, most of which can be easily integrated within the entire ecosystem. 
  
**pros:**  
* Intergration with Jira, Asana and other
* High project visibility
* Cost-efficiency
* Intergration with Slack and other tools
  
**cons:**  
* Complex interface
* Slow performance
* Not enough free CI/CD functionality
* Not as many tutorials and guides
* Decreasing popularity

**Recommended use cases:** Small, medium businesses
 
**Website:** https://bitbucket.org/  

[^ Back to table of content](#table-of-content)
### **What is GitHub**

**Description:** Github biggest functionalities are repisotory branching and forking, pull and merge request and codebase cloning and shows fast performance during these. Github allows developers to quickly upload files and offers fast and useful collaborative features. As well as project management features.

**original developer(s):** Chris Wanstrath, P. J. Hyett, Tom Preston-Werner, and Scott Chacon  
**Initial release:** April 2008

**features:**   
* Issue tracker that detects problems within the codebase and alerts collaborators;
* Issue boards support Kanban and Scrum and allow structuring tasks;
* GitHub supports epics that allow tracking the progress of the team;
* Roadmaps help to plan team projects and pinpoint key milestones;
* Estimation and points: developers can estimate effort points for each issue and * share details with collaborators;
* Synchronizing merged versions, GitHub issues, and pull requests;
* Desktop applications for Windows and Mac, as well as a mobile app for Android
* The support of 200+ programming languages
* Integrations with Asana, AWS, Windows Azure, Google Cloud, Code Climate
* GitHub Pages is a built-in service for building and hosting sites with GitHub.
* Syntax highlighting (isn’t present in BitBucket)
* Popular open-source communities
  
**pros:**  
* Big community
* Open-source popularity
* Easy interface
* Fast performance
* A lot of information
  
**cons:**  
* Not enough CI/CD functionality
* Small storage in free version
  
 
**Website:** https://github.com/

[^ Back to table of content](#table-of-content)
### **What is GitLab**


**Description:** GitLab offers a lot of source code hosting features as well as project management features. But what mostly stands out are their many CI/CD features, which are supported in their free version.  

**original developer:**  Dmytro Zaporozhets
Sytse "Sid" Sijbrandi  
**Initial release:** 2011

**features:**   
* Subgroups, compliance management, and audit events: GitLab allows restricting access to projects and viewing the compliance status of each participant;
* Project planning: developers track code issues with built-in task lists, description templates, and issue management panels;
* Communication: developers can exchange attached files, create threads and participate in them, track changes, prioritize discussions with labels, set milestones, and finalize iterations;
* Source code management: GitLab is appreciated for its intuitive interface for branching, merging, file locking, reporting. GitLab also offers free source code templates and JIRA integrations;
* Continuous integration: the main selling points of the platform are free CI tools, including parent-child pipelines, horizontal autoscaling, visualization of HTML artifacts and protected variables, etc.;
* Package building: developers can use separate packages depending on their tech stack – there’s a package for PHP, Node.js, Java, and others;
* Security: GitLab provides security scans, allows dynamic security testing (however, only in the most expensive Gold and Ultimate plans);
* Configuration and DevOps: the Auto DevOps feature is available in the free plan, whereas the specialized add-ons are supported only by Gold and Ultimate plans.

  
**pros:**  
* Rich free CI/CD functionality
* Competitive pricing
* Rich add-ons
* Simple interface
* Rising popularity
  
**cons:**  
* small open-source community
* Relatively few users
* slow performance 
* not enough guides and tutorials
  
 
**Website:** https://about.gitlab.com/  

**What version control platform best suits planpal?**

Planpal's version control system will be Git so it's platform needs to be compatible with [Git](#what-is-git) preferably without having to do additional modding. Since it needs to be outsourced we want to make the experience for our fellow developers as smooth as possible. In the end [GitHub](#what-is-github) proves viable due to it's low prices, open source friendliness, big community, tutorials and project management options.

# Conclusion

**So what version control methods best suit planpal?**  
Like written in my [project description](#the-project) at the start of this report.
It's a project that should be suitable for expansion worked on by a small development team that has the possibility to increase in the future.

The project is prone to being outsourced to anyone across the world and
the project has to be accesible by third party developers therefore.

Because of those needs using a distributed version control tool is fatal as people should be able to work on the source code at every moment with minimal chance failure.
And Git would be a viable match for Planpal.

The project's architecture is distributed meaning the application is split into multiple projects, therefore multiple repositories need to be made.
And again given the need to be outsourced and open for collaboration planpal has need for a source code hosting platform that can host multiple public, collaborative repositories. And Github would be a viable match for Planpal.

So in conclusion making use of [Git](https://git-scm.com/) and [Github](https://github.com/) would be the best suited for during Planpal's development.

# DOT framework

* Library
  * [Available product analysis](https://ictresearchmethods.nl/Available_product_analysis); I've looked at what existing products relating to my goal are available.
* Field
  * [Survey](https://ictresearchmethods.nl/Survey); I've looked up various survey answers to deduce what the community thinks
  * [Document analysis](https://ictresearchmethods.nl/Document_analysis); I've visisted official documentation of tools/systems that I've researched
* Showroom
  * [Product review](https://ictresearchmethods.nl/Product_review); I've walked through some basic functions of the version control systems

[See DOT methods](https://ictresearchmethods.nl/Methods)

# Sources
https://en.wikipedia.org/wiki/Concurrent_Versions_System  
https://www.altamira.ai/blog/4-most-popular-source-code-hosting-services/  
https://www.softwaretestinghelp.com/version-control-software/  
https://sccs.sourceforge.net/sccs_vs_rcs.html  
https://www.geeksforgeeks.org/centralized-vs-distributed-version-control-which-one-should-we-choose/  
https://www.ryadel.com/en/using-github-with-mercurial-and-tortoisehg/  
https://jelvix.com/blog/bitbucket-vs-github-vs-gitlab  
https://ictresearchmethods.nl/Methods  
