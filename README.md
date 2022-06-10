# Joe Maurer
## About
  Hi there! I'm currently a student at Oregon State, while also working as a Administrative Technology Specialist at North Penn School District. Things you may find on my Github consist of random personal projects as well as a collection of school portfolio assignments that were immediately abandoned upon being graded that are filled with spaghetti (hopefully less so as time goes on). 
  
  My homelab setup consists of a Dell R720 and 2x Dell R210 II's, as well as an older repurposed desktop build. I run them in a cluster using the Proxmox VE virtualization platform. Some of the services I run or Pihole for adblocking & local DNS purposes, various web servers for projects, game servers for my friends, and many others. 
  
  The pièce de résistance is my LAN / routing setup. I run a virtualized instance of the pfSense firewall which is replicated across three of the servers in the cluster in a high-availabilty configuration. If the active machine drops off, one of the other two will take over near instantly. Unfortunately I'm limited to one dynamic IP address, so it really only protects against hardware failure but still an interesting experiment. I also have pfSense configured with a plugin that uses ACME to automatically renew the SSL certificates for my domains, and then I use HAProxy as the gateway for serving all content over SSL.
  
## Skills
  * Languages Used
    * Javascript (mainly within Node/ React) (also navigating Google Apps Script for automating tasks in Sheets/Forms)
    * Python
    * C
    * SQL
    * HTML / CSS
    * Java
    * PHP
  * Concepts
    * Request / response (HTTP pipelines / communication & working with APIs)
    * OOP
    * Application state management
    * Socket programming
    * Multi-threading
    * Networking (mainly at the network layer, with an understanding of the upper layer protocols and how they work together)  
  * General Technology
    * Active Directory and SCCM
    * Google Admin
    * Proxmox Virtual Environment platform
    * Linux (command line, multiple distributions)

## Work Experience
* ### North Penn School District
  * #### June 2022 - Present | Administrative Technology Specialist
    * Administer system user accounts and privileges
    * Identify and resolve system problems that occur during daily use
    * Log and follow-up on all open or pending service requests for the building to ensure resolution
    * Create user documentation for system use
    * Assist and train staff on administrative systems
    * Access and report on information from administrative systems
  * #### August 2019 - June 2022 | Technology Assistant
    * Work with Desktop & Device Specialist for installations of hardware and software in the building
    * Execute image refresh on all building devices
    * Identify, diagnose, and resolve hardware, software, and operating system problems and questions that occur during daily use
    * Log and follow up on all open or pending service requests for the building to ensure resolution and escalate issues requiring further intervention through proper channels
    * Plan for building technology supply needs, order, and distribute the supplies as designated by supervisor
    * ##### Accomplishments:
      * Developed Google Docs add-on to automatically convert "Smart Quotes" back into normal ones. Smart Quotes were causing another application to break when exporting data from Google Docs, and Tech staff had been correcting the bad characters by hand for end users.
      * Developed frontend app for the SnipeIt inventory system. It uses the API to allow tech staff to more efficiently process equipment by allowing for bulk updating of device status.

## Education
* ### 2021 - Present | Oregon State University
  in progress: Bachelors of Science in Computer Science (Cybersecurity focus)
  
  estimated completion: December 2023
  
  Current GPA: 3.9
  
  
* ### 2019 - 2020 | Bucks County Community College 
  Associate of Science in Computer Science
  
  GPA: 4.0
