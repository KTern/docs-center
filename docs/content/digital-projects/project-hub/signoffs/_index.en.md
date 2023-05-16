---
title: "Signoffs"
date: 2021-01-15T11:02:05+06:00
lastmod: 2021-01-15T11:02:05+06:00
weight: 16
draft: false
# search related keywords
keywords: ["induct", "instate"]
---

## Overview

In KTern, signoffs refer to the process of reviewing and approving assets such as documents, procedures, policies and other types of content. Signoffs are used to ensure that the content is accurate, up-to-date, and compliant with organizational standards and requirements. 

1.	A project sign-off is a crucial step in formally closing a project or acknowledging the delivery of a key deliverable. 
2. A sign-off sheet is a document that is signed by all stakeholders involved in the project. It includes: 
   a. The project's intended goals and whether they were met or not. 
   b. The project's key deliverables and whether they were actually delivered. 
   c. Any comments and observations from stakeholders, if any. 
   d. The project start and end dates.
3. All involved parties sign the document, formally and legally closing the project.
4.	For complex projects, the sign-off sheet may run into dozens or even hundreds of pages. In some cases, such as government contracts, "sign-off books" may be used instead of sheets.

## Steps involved in signoff process

![1-steps-involved-in-signoff-process](https://storage.googleapis.com/ktern-public-files/product-documentation/Signoffs/1-steps-involved-in-signoff-process.png)

### Signoff Hierarchy

The signoff hierarchy in KTern ensures successful project or task completion by requiring approvals at increasing levels of the organizational hierarchy. This guarantees that relevant stakeholders review and sign off on the work before considering it complete.

In addition to the Signoff Hierarchy, there are two components to be considered in Signoff Management in KTern.

![2-signoff-hierarchy](https://storage.googleapis.com/ktern-public-files/product-documentation/Signoffs/2-signoff-hierarchy.png)

### How to create signoff group

Here are the steps you can follow to **create signoff groups** using KTern:

a. To create a signoff item, it is necessary to have at least one existing signoff group. You have the option to assign the signoff item to either a newly created signoff group or an existing one.

b.	To create a new signoff group, click on the signoff section of your project, and then click the “+” icon to add a new group. You can then customize the group's name and add the relevant stakeholders who will be responsible for reviewing and approving the signoff.

![3-signoff-group1](https://storage.googleapis.com/ktern-public-files/product-documentation/Signoffs/3-signoff-group1.png)

c.	Name the signoff group, and then select the “Add signoff group” button.

![4-signoff-group2](https://storage.googleapis.com/ktern-public-files/product-documentation/Signoffs/4-signoff-group2.png)

d.	The signoff group will be displayed in the list of signoffs now. 

![4-signoff-group3](https://storage.googleapis.com/ktern-public-files/product-documentation/Signoffs/4-signoff-group3.png)

### How to create signoff item

Here are the steps you can follow to **create sign-off items** using KTern:

**a. Click on the "Add Signoff" button.**

![5-signoff-item-creation-1](https://storage.googleapis.com/ktern-public-files/product-documentation/Signoffs/5-signoff-item-creation-1.png)

**b. This will open a drawer where you can specify the details of the signoff as mentioned below:**

#### i. Overview: 

In the overview tab, you will find the following fields:
<ul>
   <li>

   **Sign-off Title:** Please enter the title for the sign-off. This is a mandatory field. 
   </li>
   <li>

   **Description:** You can enter an optional description for the sign-off. 
   **Criteria:** Enter the acceptance criteria for the respective sign-off item. This field is mandatory. 
   </li>
   <li>

   **Condition:** This is an optional field where you can enter a conditional acceptance statement. 
   </li> 
   <li>

   **Status:** The default status of the sign-off item is set to 'New'. 
   </li>
   <li>

   **Sign-off Group:** Choose the appropriate sign-off group from the provided options.
   </li> 
   <li>

   **Tags:** Add tags to the sign-off item for easy filtering and organization.
   </li>
</ul>

![6-signoff-item-creation-2](https://storage.googleapis.com/ktern-public-files/product-documentation/Signoffs/6-signoff-item-creation-2.png)

#### ii. Stakeholders: 

In the Stakeholders tab, you will find the following fields:
<ul>
   <li>

   **Levels:** You can set up multiple levels of sign-off approval. To create a new level, click on the 'Add New Level' button. Upon clicking, a new level will be added as shown below:
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
         -> Level 1 – User 1, 
         -> Level 2 – User 2, User 3 
         -> Level 3 – User 4
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

You can link the sign-off item to any task, issue, or test case. To add a reference, click on the 'Add New Reference' button.

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

In the files section, you can upload documents related to the sign-off item. Approvers will be able to view all the uploaded files later.

![12-signoff-item-creation-8](https://storage.googleapis.com/ktern-public-files/product-documentation/Signoffs/12-signoff-item-creation-8.png)

**c. After providing the required information mentioned above, click on the 'Create' button to successfully create a sign-off item.**

![13-signoff-item-creation-9](https://storage.googleapis.com/ktern-public-files/product-documentation/Signoffs/13-signoff-item-creation-9.png)

**d. It will now be visible on the process page and can be tracked and managed from there.**

![14-signoff-item-process-page](https://storage.googleapis.com/ktern-public-files/product-documentation/Signoffs/14-signoff-item-process-page.png)

### Navigating to different icons of signoff page

Below are some icons that can be beneficial:

![15-signoff-item-filters](https://storage.googleapis.com/ktern-public-files/product-documentation/Signoffs/15-signoff-item-filters.png)
<ul>
   <li>

   **(1) & (2)** - These are the types of views namely List view and Explorer view.
   </li>
   <li>

   **(3) - Quick Filters:** Quick filter options are available at the top left corner of the Signoff header. You can easily filter scenarios such as:
         •	My Sign-offs
         •	Approved by me
         •	Rejected by me
         •	Pending actions for me
         •	My Overdue Sign-offs
         •	All Sign-offs
         •	All overdue Sign-offs
   </li>
   <li>

   **(4) - Export as XLSX:** You can export all Signoff items and their meta information in the form of a spreadsheet.
   </li>
   <li>

   **(5) - Filter by:** You can filter the Signoff items by Signoff group, Signoff status, Locked Signoffs, My Actions, Created by, Overdue Status, Stakeholder, and Pending with, as shown below.
   </li>

   ![15-signoff-item-navigating-icons](https://storage.googleapis.com/ktern-public-files/product-documentation/Signoffs/15-signoff-item-navigating-icons.png)
   <li>

   **(6) - Group by:** You can group signoffs by Signoff Group, Status, Due Date, and Tags. The following image displays how the signoff items are categorized by due dates.
   </li>
</ul>

   ![16-signoff-item-groupby](https://storage.googleapis.com/ktern-public-files/product-documentation/Signoffs/16-signoff-item-groupby.png)

### How to approve or reject signoffs

#### METHOD 1:

After the signoff process is finished, you can indicate its outcome by marking it as either "approved" or "rejected."

![17-signoff-item-approve-or-reject-1](https://storage.googleapis.com/ktern-public-files/product-documentation/Signoffs/17-signoff-item-approve-or-reject-1.png)

![18-signoff-item-approve-or-reject-discussion](https://storage.googleapis.com/ktern-public-files/product-documentation/Signoffs/18-signoff-item-approve-or-reject-discussion.png)

#### METHOD 2:

<ul>
   <li>
   Navigating to the signoffs screen of My Workspace, here also you could directly approve or reject the signoff items.
   </li>

   ![19-signoff-item-approve-or-reject-my-workspace1](https://storage.googleapis.com/ktern-public-files/product-documentation/Signoffs/19-signoff-item-approve-or-reject-my-workspace1.png)

   <li>
   Once you approve or reject the signoff, KTern will automatically update the status of the linked task to reflect the approval or rejection and then notify the relevant stakeholders accordingly.
   </li>
</ul>

   ![20-signoff-item-approve-or-reject-my-workspace2](https://storage.googleapis.com/ktern-public-files/product-documentation/Signoffs/20-signoff-item-approve-or-reject-my-workspace2.png)

### Request for re-approval
<ul>
   <li>
      To approve/reject a signoff, navigate to the signoff list view using the following menu navigation: Project Hub -> Signoffs. Click on the (i) icon.
   
      Once the users are selected, click on "Request Re-approval" to initiate the re-approval request.

   ![21-signoff-item-request-for-approval1](https://storage.googleapis.com/ktern-public-files/product-documentation/Signoffs/21-signoff-item-request-for-approval1.png)

      Enter the reason for the re-approval request and submit it. The approval status of the respective users will be re-tracked, and they will be notified of the new request. 
   </li>
</ul>

   ![22-signoff-item-request-for-approval2](https://storage.googleapis.com/ktern-public-files/product-documentation/Signoffs/22-signoff-item-request-for-approval2.png)


### Benefits
<ul>
   <li>
      Ensuring accountability and responsibility for business objects or any assets.
   </li>
   <li>
      Promoting consistency by ensuring all team members follow the same standards and procedures.
   </li>
   <li>   
      Facilitating knowledge transfer and reducing knowledge gaps.
   </li>
   <li>
      Improving the quality of documents by providing a mechanism for feedback and review.
   </li>
   <li>
      Streamlining workflows and reducing administrative burden on team members.
   </li>
   <li>   
      Providing a clear record of who has reviewed and approved a particular document or asset.
   </li>
   <li>
      Helping to comply with regulations and industry standards.
   </li>
   <li>
      Encouraging collaboration and communication among team members.
   </li>
   <li>
      Reducing errors, omissions, and other issues before they become bigger problems.
   </li>
   <li>
      Enhancing transparency and traceability of files or assets. 
   </li>
</ul>
