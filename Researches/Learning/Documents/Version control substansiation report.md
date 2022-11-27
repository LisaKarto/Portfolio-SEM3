<h1> Version Control substansiation report</h1>
Applicable to my individual project.  

<br>

# Table of content
- [Table of content](#table-of-content)
- [Introduction](#introduction)
- [My background](#my-background)
- [Version control systems](#version-control-systems)
    - [**Version control and version control software**](#version-control-and-version-control-software)
    - [**Comparing version control software**](#comparing-version-control-software)
    - [**What is Bazaar**](#what-is-bazaar)
    - [**What is Mercurial**](#what-is-mercurial)
    - [**What is Git**](#what-is-git)
    - [**My final choice in version control system**](#my-final-choice-in-version-control-system)
- [Version control platforms](#version-control-platforms)
    - [**What are version control platforms**](#what-are-version-control-platforms)
    - [**Comparing Version control platforms**](#comparing-version-control-platforms)
    - [**What is BitBucket**](#what-is-bitbucket)
    - [**What is GitHub**](#what-is-github)
    - [**What is GitLab**](#what-is-gitlab)
    - [**My final choice in version control platform**](#my-final-choice-in-version-control-platform)
- [Related topics](#related-topics)
- [Sources](#sources)



# Introduction

This document serves as a substansiation report to my version control tools choices, In this report I hope to make my decision to use the version control tools that I use (Git and GitHub) clear by exploring the basics of version control and comparing the chosen tools to other tools that are out there which offer similar functions. In the end I will draw a conclusion as to why I've decided to settle for Git and GitHub. 
  
  [^ Back to table of content](#table-of-content)
# My background

Although I am fairly familiar with Git and GitHub for version control and quick code publishing solely. I haven't got that much *proper* version control experience. I've done the tedious manual nooby version control and then quickly got hooked to using Git's basic functions. However since everyone in my experience seems to use and recommend Git without question, I have never really done any research on whatever else is out there. So I want to explore and document that now. 

I am familiar with the top leading source code hosting platforms however, namely GitHub and GitLab.  

[^ Back to table of content](#table-of-content)
# Version control systems

### **Version control and version control software**
Version control, is the practice of tracking and managing changes to computer programs, documents and could also be applied to other software or digital files.
However doing this manually has a lot of flaws as well as it is time consuming and honestly.. tedious. But since it's a very essential practice, used in almost every development process from individual passion projects to large projects made in teams. So naturally the smart brains that roam around this planet have invented something that assists you in this process. Namely, Version control systems. 

[^ Back to table of content](#table-of-content)
### **Comparing version control software**
Underneath I have listed a couple of version control software that are out there free to use. You can read the core of the software as well as some pros and cons. In the end I am giving a conclusion which states which version control software I have chosen for my current project and why.
note: I willl only be comparing distributed version control software.

[^ Back to table of content](#table-of-content)
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

[^ Back to table of content](#table-of-content)
### **What is Mercurial**

**Description:**  Mercurial is a free, distributed source contrtol management tool. It offers you the power to efficiently handle projects of any size while using an intuitive interface. It is easy to use and hard to break, making it ideal for anyone working with versioned files.    

**original developer:** Olivia Mackall  
**Initial release:** 19 April 2005

**features:**   
* High performance and scalability.
* Advanced branching and merging capabilities.
* Fully distributed collaborative development.
* Decentralized
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

[^ Back to table of content](#table-of-content)
### **My final choice in version control system**

I chose to use Git due to my prior experience, the many options to host with and the giant community. Git's very popular and strongly recommended from my experience. Using Git opens the door to many other tools that are collaborative to Git, for example GitHub (my choice of source code hosting platform) without having to any extra measures in order to make it work. Which you would have to do if you want to to collaborate GitHub with Mercurial for example. So since I'm just looking to get my footing, I figure I'll walk the most traveled path.

# Version control platforms

### **What are version control platforms**

Version control platforms offer softwre developers the ability to share and host their code. Nowadays these platforms come with additional features, such as project management features. These version control platforms boost collaborative working amongst developers. Together with version control systems developers can share, develop and track their projects.  

[^ Back to table of content](#table-of-content)
### **Comparing Version control platforms**
Next I have to find a source code hosting service that goes well with my prefered version control software. I've chosen to compare 3 services, namely "BitBucket", "GitHub" and "GitLab". Below I have listed what each one of these have to offer and in the end I'll build upon which one of these 3 I have chosen to use for my project and why.  
[^ Back to table of content](#table-of-content)
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

[^ Back to table of content](#table-of-content)
### **My final choice in version control platform**
I've prior experience using GitLab, namely in the last semesters so I wanted to try something new instead. For my IP project I'd like to keep all my information central which is why I opted to use GitHub, GitHub offers a lot of functionalities for project management and source code hosting. This way I can keep all my work central as opposed to BitBucket where you'd use it in collaboration with Jira. But I am definitely not eliminating BitBucket nor GitLab for future projects.

**Definitive version control system of choice:** Git  
**Definitive version control platform:** GitHub  

[^ Back to table of content](#table-of-content)
# Related topics 
* [Workflow within my project]()
  * [Agile]()
    * [Scrum]()
  * [Work environment]()
* [How I work with Git and GitHub]()
  * [GitHub repositories]()
  * [GitHub issues]()
  * [GitHub projects]()
  * [GitHub boards]()

* [Learning projects with GitHub]()
* [Learning Issues with GitHub]()
* [Learning GitHub workflow]()
* [Learning outcomes]() 
  
[^ Back to table of content](#table-of-content)  
# Sources
https://en.wikipedia.org/wiki/Concurrent_Versions_System  
https://www.altamira.ai/blog/4-most-popular-source-code-hosting-services/  
https://www.softwaretestinghelp.com/version-control-software/  
https://sccs.sourceforge.net/sccs_vs_rcs.html  
https://www.geeksforgeeks.org/centralized-vs-distributed-version-control-which-one-should-we-choose/  
https://www.ryadel.com/en/using-github-with-mercurial-and-tortoisehg/  
https://jelvix.com/blog/bitbucket-vs-github-vs-gitlab  

[^ Back to table of content](#table-of-content)