# [Mod 2] CIA Triad

<b>Prompt:</b> Oscorp is currently working on a Highly Confidential new medication. The project is still in its early stages of development, and it's lead by the Chief Scientist: Harry Osborn.

At the moment, the Chief Scientist has just compiled a list of ingredients that he needs to start experimenting with the drug.
The ingredients are written on a Microsoft word document.


<b>Problem:</b> You are tasked with conducting an early assessment on the project using the CIA triad to ensure that the confidentiality, integrity, and availability of the word document are held to an acceptable standard.

What questions will you ask Harry as they related to the CIA triad? What recommendations would you provide?

---

## 🔹 My Thoughts & Recommendations
Considering the high-profile nature of this project there are several security parameters that need to be addressed. Even in the early stages, this project needs to be kept secret to protect the interests of the business in the long and short term.  

Let’s start with a few questions:  

  -What specific laboratory is the project being developed in? 

  -Secondly, who has access to said lab and files? 

  -Currently, only Chief Scientist Harry Osborn has access to the working files for this project so how do we go about structuring and maintaining security going forward?

---

### 🔹 Consider the following measures:

[Confidentiality]

  •	The team working on the project needs to be established and proper access given to each member. What level of access each team member has to the files needs     to be assessed and authentication credentials given to pertinent members only within the lab environment.  
  •	This project is top-secret, so it needs to only be worked on within the lab.  
  •	Digital access should only be limited to the intranet designated for top projects hosted locally within the lab.  
  •	Outside storage devices should be restricted from connecting to internal consoles to keep data from leaking out into public hands.  
  •	Working consoles need to be protected from access by MFA (Biometrics strong passwords, or badge)  
  •	There also should be a log of who accesses the lab easily integrated be using a biometric lock. This will keep the lab secure and provide a system of            accountability to all project participants.

[Integrity]  

  •	Document changes will need to be signed off by Harry Osborn  
  •	A backlog of document versions kept for the sake of records and project development according to the CMDB  
  •	A backup of current and future files ought to be set up to make new copies of files as they’re updated.  
  •	Is the lab protected by CCTV?  
  •	Do associates need to use multiple authentication methods to enter the lab?

[Availability]

  •	What redundancy methods are in place? Have backup systems been tested for accessibility during a power outage or breach situation?  
  •	Record the cost of power outages, backup power sources, and connecting them to critical data systems. We don’t want to lose access to critical information at the wrong time. The disruption of business workflow is the first thing we want to prevent as the financial ramifications in the mid- This will have financial implications down the road by delaying development of products or disrupting overall workflows across the business  
    •	Backup systems need to be regularly tested for proper function every 3 to 6 months
    

### Security measures are often overlooked and taken for granted in many smaller tech companies with data to protect. This leaves an open door for threat actors not only to access their data but also to practice methodologies to use elsewhere. In this exercise Oscorp is not small by any means, but their security is being treated as an afterthought...

