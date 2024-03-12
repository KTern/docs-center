---
title: "DocuSign - KTern.AI Integration Guide"
date: 2024-03-06T11:02:05+06:00
lastmod: 2024-03-07T11:02:05+06:00
weight: 4
draft: false
# search related keywords
keywords: ["induct", "instate"]
---
<div style='text-align: justify;'>

### About DocuSign Integration and KTern.AI

DocuSign Integration within KTern.AI enhances document management and approval processes, streamlining workflow and improving collaboration within teams. By seamlessly integrating with DocuSign, KTern.AI optimizes the signing process and facilitates efficient document handling.

KTern.AI is dedicated to democratizing digital transformation, providing organizations with powerful data-driven automation and intelligent insights. KTern.AI harnesses the power of automation and tribal knowledge intelligence to excel in projects centered around DocuSign for both enterprise customers and partners.

### Pre-requisites

</br>1. Before you begin with this guide, make sure you have a DocuSign developer account. If you don't already have one, you can sign up for free by visiting the following URL: https://developers.docusign.com/

</br>2. For the latest information on API pricing, please consult this page: https://ecom.docusign.com/en-GB/plans-and-pricing/developer

### Steps to Integrate DocuSign and KTern.AI

</br>**I. DocuSign Configuration Steps:**
<ul>

</br>1. Log in to the DocuSign Developer portal by providing your email ID, password, and then entering a verification code when prompted. Click the "Verify" button to proceed.

![](https://storage.googleapis.com/ktern-public-files/Integrations/1_docusign_integration.png)

![](https://storage.googleapis.com/ktern-public-files/Integrations/2_email_docusign_integration.png)

![](https://storage.googleapis.com/ktern-public-files/Integrations/3_password_docusign_integration.png)

![](https://storage.googleapis.com/ktern-public-files/Integrations/4_verification_code_docusign_integration.png)

</br>2. Once logged in, click on your profile and select "My Apps & Keys."

![](https://storage.googleapis.com/ktern-public-files/Integrations/5_my_apps_and_keys_docusign_integration.png)

</br>3. To create an Integration key, you need to create an App. Click on the "Add App and Integration Key" button.

![](https://storage.googleapis.com/ktern-public-files/Integrations/6_add_app_and_integration_key_button_docusign_integration.png)

</br>4. A dialog box will appear asking for the "App Name." Fill in the required information and click the "Create App" button.

![](https://storage.googleapis.com/ktern-public-files/Integrations/7_create_app_docusign_integration.png)

**Note:** You can provide any name for the "App Name" as per your preference.

</br>5. You will be redirected to the "Apps and Keys" screen, where you can view the General Info, Authentication Settings, Service Integration, and Additional Settings of the app you created.

![](https://storage.googleapis.com/ktern-public-files/Integrations/8_authentication_settings_docusign_integration.png)

</br>6. In the General Info section, you can copy the Integration Key, which will be required during the integration with KTern. Under Authentication, select "Yes" to securely store a client secret.

</br>7. Scroll down and click on the "Generate RSA" button to acquire your RSA public and private keys. Ensure to securely store these keys, as they cannot be viewed again once the dialog box is closed, and they will be required during the integration with KTern.

![](https://storage.googleapis.com/ktern-public-files/Integrations/9_generate_rsa_docusign_integration.png)

![](https://storage.googleapis.com/ktern-public-files/Integrations/10_rsa_key_pair_docusign_integration.png)

</br>8. In the Additional Settings section, add the following URL in the "Redirect URLs" field by clicking the "Add URL" button: https://app.ktern.com/*

![](https://storage.googleapis.com/ktern-public-files/Integrations/11_add_redirect_url_docusign_integration.png)

![](https://storage.googleapis.com/ktern-public-files/Integrations/12_added_redirect_url_docusign_integration.png)


**Note:** Ensure there are no spelling mistakes or additional blank spaces in the copied Redirect URL.

</br>9. Click the save button to update all the changes made.

![](https://storage.googleapis.com/ktern-public-files/Integrations/13_save_the_configurations_docusign_integration.png)

</br>10. Copy your User ID, API Account ID, and Integration Key, which are present under the app name. Ensure to store all of these securely, as they will be required during the integration with KTern.
</ul>

![](https://storage.googleapis.com/ktern-public-files/Integrations/14_copy_the_credentials_and_integrations_docusign_integration.png)

</br>**II. KTern Configuration Steps:**
<ul>

</br>1. Log in to the KTern.AI application using your KTern.AI credentials and navigate to the specific project where you want to integrate DocuSign. Click on your profile avatar and navigate to the project settings page.

![](https://storage.googleapis.com/ktern-public-files/Integrations/13_save_the_configurations_docusign_integration.png)

</br>2. Go to the "Integrations" tab, click on the DocuSign Banner, and then click the "+ Setup Integration" button.

![](https://storage.googleapis.com/ktern-public-files/Integrations/16_integrations_and_choose docusign_and_click_setup_integration_docusign_integration.png)

</br>3. Under "Basic Setup," fill in the required credentials obtained from the DocuSign portal, such as Title of the Integration, Scenario (auto-filled by KTern.AI), API Account ID, RSA Private Key, User ID, and Integration Key. Click the "Consent" button.

![](https://storage.googleapis.com/ktern-public-files/Integrations/17_setup_integration_docusign_integration.png)

![](https://storage.googleapis.com/ktern-public-files/Integrations/18_fill_in_setup_integration_docusign_integration.png)

![](https://storage.googleapis.com/ktern-public-files/Integrations/19_fill_in_userid_and_integration_key_setup_integration_docusign_integration.png)

</br>4. Provide access to KTern.AI by clicking the "Allow Access" button.

![](https://storage.googleapis.com/ktern-public-files/Integrations/20_grant_access_docusign_integration.png)

</br>5. You will be prompted to log in to DocuSign again in a new tab. After logging in, you will see a notification message stating, "User Consent Provided."

![](https://storage.googleapis.com/ktern-public-files/Integrations/21_user_concent_provided_docusign_integration.png)

</br>6. Click "Next" to navigate to the "Project Selection" screen. Select the DocuSign Default Project from the dropdown menu and click the "Setup Integration" button.

![](https://storage.googleapis.com/ktern-public-files/Integrations/22_project_selection_docusign_integration.png)

</br>7. The DocuSign integration with KTern.AI has been successfully configured.

</br>8. You can check or update the credentials later by visiting the "Active Integrations" Tab. By clicking the ">" symbol, you can view detailed information about the integration you created. You also have the option to delete unwanted integrations.

![](https://storage.googleapis.com/ktern-public-files/Integrations/23_active_integrations_docusign_integration.png)

![](https://storage.googleapis.com/ktern-public-files/Integrations/24_view_update_delete_active_integrations_docusign_integration.png)

</br>9. Whenever you create signoffs via KTern.AI, the DocuSign email will be triggered along with the KTern's signoff notification email.

</br>10. Create a signoff item by providing the signoff title and choose the signoff group, which are mandatory fields under the "Overview" tab. If needed, fill in other fields too.

![](https://storage.googleapis.com/ktern-public-files/Integrations/25_create_signoff_docusign_integration.png)

</br>11. Then, go to the "Stakeholders" tab and provide the names of the approvers. You can add multiple stakeholders under the same level and also add multiple levels if needed.

![](https://storage.googleapis.com/ktern-public-files/Integrations/26_assign_stakeholder_create_signoff_docusign_integration.png)

</br>12. To trigger the DocuSign email, you must add attachments under the "Files" tab and then click the "Create" button.

![](https://storage.googleapis.com/ktern-public-files/Integrations/27_upload_files_and_create_signoff_docusign_integration.png)

</br>13. If you are among the levels of approvers, you will receive an email with a "REVIEW DOCUMENTS" button. Click on it to be redirected to the DocuSign page, where you can review the document. Click "Continue" to proceed with the review.

![](https://storage.googleapis.com/ktern-public-files/Integrations/28_view_the_mail_and_review_documents_docusign_integration.png)

![](https://storage.googleapis.com/ktern-public-files/Integrations/29_review_documents_docusign_integration.png)

</br>14. After reviewing the document, click on "Signature" from the toolbar on the left. Choose a readymade signature and place it at the end of the documentation. Click the "FINISH" button to complete the review.

![](https://storage.googleapis.com/ktern-public-files/Integrations/30_signature_docusign_integration.png)

![](https://storage.googleapis.com/ktern-public-files/Integrations/31_finish_signature_docusign_integration.png)

</br>15. In KTern.AI, go to the "Discussions" tab of the created signoff item to view the discussion history and the recording of the date and time of the approval.

![](https://storage.googleapis.com/ktern-public-files/Integrations/32_view_the_approved_signoff_in_discussions_docusign_integration.png)

</br>16. After all approvals are done by the approvers for the respective signoff item, a mail will be triggered from DocuSign with a "VIEW COMPLETED DOCUMENTS" button, allowing you to view the document without being able to edit it. 

![](https://storage.googleapis.com/ktern-public-files/Integrations/33_view_the_approved_documents_docusign_integration.png)

</br>17. This feature enables higher-level officials to approve items from outside of KTern.

</div>