---
layout: page
title: UCloud
parent: Access
has_children: false
nav_order: 2
hide:
  - footer
  - toc
---

# Accessing the Sandbox on UCloud

User accounts on UCloud are enabled by university login credentials using WAYF (Where Are You From). Access the WAYF login portal [here](https://cloud.sdu.dk/), and then find your affiliated Danish university using the search bar. After login, we suggest setting up Two Factor Authentication by clicking on the icon in the top-right corner of the screen. Once you are an approved user of UCloud, you can access the Sandbox environment via different 'Sandbox' apps linked to topical modules that you deploy using your own storage and computing resources - just go to Apps once you have signed into UCloud and search 'Sandbox' to find what we have deployed. Each app page has its own Documentation link that will direct you to Sandbox-based usage guidelines which may be customized to the app's particular tools and scope. Apps will have different 'courses' that you can initially choose which make a personal copy of training materials in your workspace for you to edit.  

Each Danish university has its own usage relationship with UCloud as governed by their local front office of [DeiC](https://www.deic.dk/en) - check with your university IT support / DeiC representatives about requesting computational resources. For example, the University of Copenhagen has previously allotted an initial chunk of free UCloud compute hours to staff (from PhD students to professors as well as non-academic staff). If you have further questions about getting compute resources, please [contact](https://hds-sandbox.github.io/contact) Sandbox staff.

Extensive documentation on general use of UCloud (how to use apps and run jobs, etc.) is available in the UCloud [user guide](https://docs.cloud.sdu.dk/).

## Example: accessing course materials using JupyterLab

**Step 1**  Log onto UCloud at the address [http://cloud.sdu.dk](http://cloud.sdu.dk) using university credentials.

**Step 2**  When you are logged in, be sure to choose the project from which you'd like to use compute resources (red circle). If you've joined one of our courses or workshops, your instructor will let you know which to choose. For this example, we select Sandbox_workshop.
![](../assets/images/workspace.png)

**Step 3**  Then click on Apps in the left panel to investigate what tools and environments you can use (green circle). The easiest way to find Sandbox resources is to search via the toolbar (red circle). In this example, we'll choose the Genomics Sandbox.
![](../assets/images/apps.png)


**Step 4**  Click on the app button. You will get into the settings window. You can configure the app as shown below, or you may receive custom instructions in a workshop on how to load a configuration file made available in the project folders which will take care of everything for you. 
![](../assets/images/configure_NGS.png)
In this example, we configure our session by:

  1. entering a job name
    
  2. selecting hours of time we want to use a node
    
  3. selecting a 4 CPU standard node with 24 GB memory.
    
  4. choosing the course "Introduction to NGS Data Analysis" 
    
  5. hitting submit (there may be a wait).

The first 3 steps set up our compute resources for the period we want to work and can be customized as needed.


**Step 5**  Wait to go through the queue. When the session starts, the timer begins to count down. In a couple of minutes you should be able to open the interface through the button (green circle).

![](../assets/images/running_NGS.png)

This page will remain open while you work (or you can return to it via 'Runs' in the left panel). You can end your session early by pressing and holding 'Stop application' (pink circle), you can see how much time you have left (red circle) and you can add hours to your session as you go (buttons in blue circle).