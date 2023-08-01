---
title: "Creating Signoff Item"
date: 2021-01-15T11:02:05+06:00
lastmod: 2023-08-01T11:02:05+06:00
weight: 36
draft: false
# search related keywords
keywords: ["induct", "instate"]
---

Here are the steps you can follow to **create signoff item** using KTern:

**Step 1: Click on the "Add Signoff" button.**

![5-signoff-item-creation-1](https://storage.googleapis.com/ktern-public-files/product-documentation/Signoffs/5-signoff-item-creation-1.png)

**Step 2: This will open a drawer where you can specify the details of the signoff as mentioned below:**

#### i. Overview: 

In the overview tab, you will find the following fields:
<ul>
   <li>

   **Signoff Title:** Please enter the title for the signoff. This is a mandatory field. 
   </li>
   <li>

   **Description:** You can enter an optional description for the signoff. 
   </li>
   <li>

   **Criteria:** Enter the acceptance criteria for the respective signoff item. This field is mandatory. 
   </li>
   <li>

   **Condition:** This is an optional field where you can enter a conditional acceptance statement. 
   </li> 
   <li>

   **Status:** The default status of the signoff item is set to 'New'. 
   </li>
   <li>

   **Signoff Group:** Choose the appropriate signoff group from the provided options.
   </li> 
   <li>

   **Tags:** Add tags to the signoff item for easy filtering and organization.
   </li>
</ul>

![6-signoff-item-creation-2](https://storage.googleapis.com/ktern-public-files/product-documentation/Signoffs/6-signoff-item-creation-2.png)

#### ii. Stakeholders: 

In the Stakeholders tab, you will find the following fields:
<ul>
   <li>

   **Levels:** You can set up multiple levels of signoff approval. To create a new level, click on the 'Add New Level' button. Upon clicking, a new level will be added as shown below:
   </li>
</ul>

![7-signoff-item-creation-3](https://storage.googleapis.com/ktern-public-files/product-documentation/Signoffs/7-signoff-item-creation-3.png)

![8-signoff-item-creation-4](https://storage.googleapis.com/ktern-public-files/product-documentation/Signoffs/8-signoff-item-creation-4.png)
<ul>
   <li>

   **Approvers:** You can add one or more approvers for each level. To add an approver for a specific level, click on the 'Add Approver' button. Choose the Owner and Due Date for each approver field.
   </li>
</ul>

![9-signoff-item-creation-5](https://storage.googleapis.com/ktern-public-files/product-documentation/Signoffs/9-signoff-item-creation-5.png)
<ul>
   <li>

   **Approver Levels:** A signoff can be configured to have multiple levels of approvals, and each level of approval can have multiple parallel approvers.
   </li>
</ul>

![10-signoff-item-creation-6](https://storage.googleapis.com/ktern-public-files/product-documentation/Signoffs/10-signoff-item-creation-6.png)
   <ul>
      <li>
      For example, let's consider a signoff with the following approval levels: 
         (i). Level 1 – User 1, 
         (ii). Level 2 – User 2, User 3 
         (iii). Level 3 – User 4
      </li>
      <li>
      In the given example, "User 1" would be the first approver of the signoff. Once "User 1" approves the signoff, KTern will request the next level users for their approval.
      </li>
      <li>
      The signoff will continue to progress through all the configured levels until it reaches the last level, where the user in "Level n" (n being the last level) will be the final approver responsible for closing the signoff.
      </li>
      <li>
      If a user at any level rejects the signoff, all other users involved in the signoff will be notified accordingly.
      </li>
      <li>
      In the event that a user (part of the signoff) feels the need for re-approval from another user, they can request the other user for re-approval.
      </li>
   </ul>
</ul>

#### iii. References: 

You can link the signoff item to any task, issue, or test case. To add a reference, click on the 'Add New Reference' button.

![11-signoff-item-creation-7](https://storage.googleapis.com/ktern-public-files/product-documentation/Signoffs/11-signoff-item-creation-7.png)
<ul>
   <li>
   Choose the Type: Task, Issue, or Test case.
   </li>
   <li>
   Select the item that needs to be linked to the respective signoff item.
   </li>
</ul>

#### iv.	Files: 

In the files section, you can upload documents related to the signoff item. Approvers will be able to view all the uploaded files later.

![12-signoff-item-creation-8](https://storage.googleapis.com/ktern-public-files/product-documentation/Signoffs/12-signoff-item-creation-8.png)

**Step 3: After providing the required information mentioned above, click on the 'Create' button to successfully create a signoff item.**

![13-signoff-item-creation-9](https://storage.googleapis.com/ktern-public-files/product-documentation/Signoffs/13-signoff-item-creation-9.png)

**Step 4: It will now be visible on the process page and can be tracked and managed from there.**

![14-signoff-item-process-page](https://storage.googleapis.com/ktern-public-files/product-documentation/Signoffs/14-signoff-item-process-page.png)
