---
title: "How is project progress calculated in KTern.AI?"
date: 2023-05-09T11:02:05+06:00
lastmod: 22023-08-29T11:02:05+06:00
weight: 4
draft: false
# search related keywords
keywords: ["induct", "instate"]
---

## Overview
In KTern’s Transformation Hub, you can monitor the progress of your projects using dashboard. The dashboard features a progress bar that provides an overview of the project’s advancement from its inception. You can configure the progress calculated metrics in 3 different way: Task Completion, Task Weightage, and Task Milestones. By default, the progress bar calculates project progress based on task completion.

1. 
![1_Transformation_hub](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Projects/Dashboard/1_Transformation_hub.png)

2. 
![2_Dashboards](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Projects/Dashboard/2_Dashboards.png)

3. 
 ![3_dashboard_interface](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Projects/Dashboard/3_dashboard_interface.png)

# Progress Calculation Methods

## Task Completion

#### Method: - 
Total tasks count is determined. Total approved tasks count is determined. Project progress is calculated using the formula: 

<br>

(Total Approved Tasks / Total Tasks) * 100


## Task Weightage

#### Method: - 
For each task in the project plan workbook, users are asked to provide planned weightage. During the project, actual weightage is calculated for each task based on planned weightage and task completion. 
<br>

![4_weightage](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Projects/Dashboard/4_weightage.png)

Project progress is calculated by aggregating the actual weightage for all tasks and dividing it by the planned weightage: 
<br>

(Sum of Actual Weightage / Sum of Planned Weightage) * 100


## Task Milestones

#### Method: - 

For each task in the project plan workbook, users are asked to provide planned Milestone (%) values. During the project, actual Milestone (%) values are calculated for each task based on planned Milestone (%) and task completion. 
<br>

![5_Milestones](https://storage.googleapis.com/ktern-public-files/product-documentation/Digital%20Projects/Dashboard/5_Milestones.png)

Project progress is calculated by aggregating the actual Milestone (%) values for all tasks and dividing it by the sum of planned Milestone (%) values: 
<br>

(Sum of Actual Milestones / Sum of Planned Milestones) * 100
