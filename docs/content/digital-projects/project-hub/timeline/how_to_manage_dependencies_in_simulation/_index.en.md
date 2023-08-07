---
title: "How to manage dependencies in Simulation?"
date: 2021-05-23T11:02:05+06:00
lastmod: 2021-05-23T11:02:05+06:00
weight: 27
draft: false
# search related keywords
keywords: ["induct", "instate"]
---


To add dependencies for a work item, follow the steps mentioned below:

1. Click on “Hamburger” icon.

![1_clcik_on_hamburger_icon](https://storage.googleapis.com/ktern-public-files/product-documentation/Simulation/1_clcik_on_hamburger_icon.png)

2.  Click on Digital projects and click on Timeline.

![2_clickon_DigitalProjects_Timeline](https://storage.googleapis.com/ktern-public-files/product-documentation/Simulation/2_clickon_DigitalProjects_Timeline.png)

3. In timeline, click on Simulation.

![3_click_simulation](https://storage.googleapis.com/ktern-public-files/product-documentation/Simulation/3_click_simulation.png)

4. Now, under dependencies, click over a desired task to add a suitable dependency

![4_add_dependiencies](https://storage.googleapis.com/ktern-public-files/product-documentation/Simulation/4_add_dependiencies.png)


### Note

Simulation allows link items to create dependencies for a task. The following are 
the dependencies in KTern.

1. <b>Finish - to – Start (FS) (default) -</b> Task 1 must finish before Task 2 can start. 
    E.g., 1.1.1FS
2. <b>Start - to – Start (SS)-</b> Task 1 and Task 2 must start at the same time.
    Eg.1.1.1SS
3. <b>Finish - to – Finish (FF)-</b> Task 1 and Task 2 must finish at the same time. 
    Eg.1.1.1FF
4. <b>Start - to – Finish (SF) -</b> Task 2 cannot finish until the start of Task 1. 
    Eg.1.1.1SF
<br>
<b>Multiple Dependencies -</b> You can add multiple dependencies to a task item by comma 
separated values. Eg.1.1.1SS,1.1.2FS
<br>
<b>Add Lead / Lag -</b> You can add lead / lag by specifying the day count.
    1. <b>Lead -</b> Lead time is the amount of time whereby a successor activity can be 
        advanced with respect to a predecessor activity. <br>
        E.g., 1.1.1FS-1
    2. <b>Lag -</b> A lag time is the amount of time whereby a successor activity is required 
    to be delayed with respect to a predecessor activity. <br>
        Eg.1.1.1FS+1
<br>
<br>
To visually see the relation among tasks, use Gantt View.

![5_Gantt_View](https://storage.googleapis.com/ktern-public-files/product-documentation/Simulation/5_Gantt_View.png)