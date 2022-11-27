# Version Control substansiation report

# Introduction

This document serves as a substansiation report to my version control tools choices, In this report I hope to make my decision to use the version control tools that I use (Git and GitHub) clear by exploring the basics of version control and comparing the chosen tools to other tools that are out there which offer similar functions. In the end I will draw a conclusion as to why I've decided to settle for Git and GitHub. 

# My background

Although I am fairly familiar with Git and GitHub for version control and quick code publishing solely. I haven't got that much *proper* version control experience. I've done the tedious manual nooby version control and then quickly got hooked to using Git's basic functions. However since everyone in my experience seems to use and recommend Git without question, I have never really done any research on whatever else is out there. So I want to explore and document that now. 

I am familiar with the top leading source code hosting platforms however, namely GitHub and GitLab.

# Version control systems

### **Version control and version control software**
Version control, is the practice of tracking and managing changes to computer programs, documents and could also be applied to other software or digital files.
However doing this manually has a lot of flaws as well as it is time consuming and honestly.. tedious. But since it's a very essential practice, used in almost every development process from individual passion projects to large projects made in teams. So naturally the smart brains that roam around this planet have invented something that assists you in this process. Namely, Version control systems. 

### **Comparing version control software**
Underneath I have listed a couple of version control software that are out there free to use. You can read the core of the software as well as some pros and cons. In the end I am giving a conclusion which states which version control software I have chosen for my current project and why.
note: I willl only be comparing distributed version control software.


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


### **Why I chose to use Git**

I chose to use Git due to my prior experience, the many options to host with and the giant community. Git's very popular and strongly recommended from my experience. Using Git opens the door to many other tools that are collaborative to Git, for example GitHub and GitLab without having to install extensions or plugins to make it work. Which you would have to do in order to collaborate GitHub with Mercurial for example. Since I'm just looking to get my footing, I figure I'll run on the most traveled path.

# Source code hosting platforms

### **Comparing source code hosting platforms**

### **What is BitBucket**


### **What is GitHub**
Now you know Git and it's own fundamentals, we can visit "GitHub" and what it is. Because these 2 go hand in hand.

### **What is GitLab**

### **Why I chose to use GitHub**



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
# Sources
https://en.wikipedia.org/wiki/Concurrent_Versions_System  
https://www.altamira.ai/blog/4-most-popular-source-code-hosting-services/  
https://www.softwaretestinghelp.com/version-control-software/  
https://sccs.sourceforge.net/sccs_vs_rcs.html  
https://www.geeksforgeeks.org/centralized-vs-distributed-version-control-which-one-should-we-choose/  
https://www.ryadel.com/en/using-github-with-mercurial-and-tortoisehg/