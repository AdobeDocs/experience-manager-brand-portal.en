---
title: Frequently Asked Questions
description: Get an insight into the frequently asked questions in the Adobe Experience Manager Assets Brand Portal.
content-type: reference
contentOwner: Vishabh Gupta
topic-tags: frequently-asked-questions
products: SG_EXPERIENCEMANAGER/Brand_Portal
discoiquuid:
exl-id: 4a8f7fbd-7485-421d-a8db-755324d2dbef
---
# Frequently Asked Questions {#frequently-asked-questions}

The Brand Portal FAQs focuses on the end-users queries and issues that they might encounter while working with the latest Experience Manager Assets Brand Portal 6.4.6 release or earlier versions.


## Brand Portal 6.4.6 FAQs {#faqs-bp646}

**Question: The existing legacy OAuth endpoint (`https://legacy-oauth.cloud.adobe.io/login`) is not working. What could be the possible reason?**

**Answer:** Legacy OAuth configuration is deprecated. Upgrade Experience Manager Assets author instances to the latest service pack and configure it by way of Adobe Developer Console. See [Configure Experience Manager Assets with Brand Portal](configure-aem-assets-with-brand-portal.md) for details. However, for Legacy OAuth configuration to work until you upgrade, update the Legacy OAuth endpoint to `https://hypnosisprod.ethos11-prod-or1.ethos.adobe.net/`.   

**Question: I am not able to publish the contribution folder's assets from Brand Portal to Experience Manager Assets after upgrading to Adobe Developer Console. My author instance is on Experience Manager Assets 6.5.4. What could be the possible reason?**

**Answer:** Yes, there is a known issue while publishing contribution folder's assets to Experience Manager Assets 6.5.4 by way of the Adobe Developer Console. 

The issue is fixed in Experience Manager Assets 6.5.5. You can upgrade your Experience Manager Assets instance to the latest service pack and [upgrade your configurations](https://experienceleague.adobe.com/en/docs/experience-manager-65/content/assets/brandportal/configure-aem-assets-with-brand-portal#upgrade-integration-65) on Adobe Developer Console. 


**Question: I do not see the contribution folder's content published from Brand Portal in Experience Manager Assets. What could be the possible reason?**

**Answer:** Contact your Experience Manager Assets administrator to verify the configurations and ensure that your Brand Portal tenant is configured with only one Experience Manager Assets author instance.   

This issue possibly occurs when you have configured a Brand Portal tenant on multiple Experience Manager Assets author instances. For example, the administrator configures the same Brand Portal tenant on the Experience Manager Assets author instance of a staging and production environment. In this case, the asset publishing triggers in Brand Portal, but the Experience Manager Assets author instance fails to import the asset because the replication agent does not receive the requesting token.  


**Question: I am unable to publish assets from Experience Manager Assets to Brand Portal. The replication log states that the connection timed out. Is there a quick fix?**

**Answer:** Usually the publishing fails with a timeout error if there are multiple pending requests in the replication queue. To resolve this issue, ensure that the replication agents are configured to avoid timeout. 

Perform the following steps to configure the replication agent:

1. Log in to your Experience Manager Assets author instance.
1. From the **Tools** panel, navigate to **[!UICONTROL Deployment]** > **[!UICONTROL Replication]**.
1. In the Replication page, click **[!UICONTROL `Agents on author`]**. You can see the four replication agents for your Brand Portal tenant. 
1. Click the replication agent URL to open the agent details.
1. Click **[!UICONTROL Edit]** to edit the replication agent settings.
1. In agent settings, click the **[!UICONTROL Extended]** tab. 
1. Select the **[!UICONTROL Close Connection]** check box.
1. Repeat steps 4 through 7 to configure all the four replication agents. 
1. Restart the server and verify the connection.


## Brand Portal 6.4.5 FAQs {#faqs-bp645}

**Question: What is the major change in Brand Portal 6.4.5 release?**

**Answer:** Experience Manager Assets Brand Portal 6.4.5 lets users upload content and publish the Contribution folder back to Experience Manager Assets directly from Brand Portal, without requiring administrator rights. For more information, see [Asset Sourcing in Brand Portal](brand-portal-asset-sourcing.md).



**Question: Have I lost access to any existing assets, features, or configurations I have created?**

**Answer:** All of your existing features and configurations remain intact. Your end-users are not impacted, and your content remains intact.



**Question: When am I moving to the new version of Brand Portal?**

**Answer:** Brand Portal 6.4.5 was released to production in October 2019. And the next Brand Portal version is expected for March 2020. 
For updates and version change, Adobe recommends you track the [Release Notes](brand-portal-release-notes.md) and [What's New in Brand Portal](whats-new.md).



**Question: Are my users impacted?**

**Answer:** The Brand Portal 6.4.5 release is exclusively within Brand Portal, so there is no impact to your end-users.



**Question: Is there any action required on my part as a Brand Portal user?**

**Answer:** Brand Portal 6.4.5 release comes with a new feature named Asset Sourcing. The administrator has to configure the Asset Sourcing feature in Experience Manager Assets to enable the feature for the Brand Portal users. For more information, refer to [Enable Asset Sourcing](brand-portal-asset-sourcing.md).



**Question: Who can create a Contribution folder?**

**Answer:** Any Experience Manager Assets user that has permissions to create a folder in Experience Manager Assets can create a **Contribution** folder. To create a **Contribution** folder, create a folder of type **Asset Contribution**. 
This folder is shared with the active Brand Portal users for contribution.  



**Question: What does a Contribution folder contain?**

**Answer:** **Contribution** folder contains two sub-folders **NEW** and **SHARED**. Initially, the NEW folder is blank and the SHARED folder contains the reference content (reusable assets) for the Brand Portal users. 
The Brand Portal users access the **Contribution** folder and upload content in the **NEW** folder.  



**Question: Can I modify the name of an existing Contribution folder?**

**Answer:** **No**, you cannot modify the name of an existing **Contribution** folder.  



**Question: What is asset requirements w.r.t contribution?**

**Answer:** The **Brief** document in the **Contribution** folder and the reference content in the **SHARED** folder help Brand Portal users understand the contribution needs and expectations. Together, they are known as the asset requirements.

**Question: Can I upload assets to any permitted folder?**

**Answer:** Not all the permitted folders. A Brand Portal user can upload content only to the **Contribution** folder that Experience Manager Assets or Brand Portal administrator shares.



**Question: How do I get access to a Contribution folder?**

**Answer:** You can access a **Contribution** folder only if it has been shared with you. You get an email/pulse notification whenever a Contribution folder is shared with you. You can access the Contribution folder by way of the link shared in the email. Or, you can log in to your Brand Portal instance and navigate to the bell icon for notifications to access the Contribution folder.  

>[!NOTE]
>
>If you are not a Brand Portal user, request the Experience Manager Assets administrator to create your user in the Admin Console. Then, add your profile to the user configuration file in Brand Portal users list. 


**Question: What is the Format of the CSV file for user import?**

**Answer:** The format matches what Admin Console supports for bulk user import. Email, first name, and last name are mandatory.



**Question: What populates the list of users (Brand Portal contributors) in the Asset Contribution user drop-down?**

**Answer:** The users in the drop-down are populated from the Brand Portal user configuration (.csv) file uploaded in Experience Manager Assets.



**Question: Where can I see the status of import and publish jobs?**

**Answer:** In Experience Manager Assets, you can see the status of an import in the **async** job page. In Brand Portal, you can see the status of a publish job in **[!UICONTROL Tools > Asset Contribution status]**.



**Question: What is the frequency of an import job that runs periodically in Experience Manager?**

**Answer:** In Experience Manager Assets, polling is run every five minutes.



**Question: Is there a threshold on the number of times a folder can be published from Brand Portal to Experience Manager Assets?**

**Answer:** No, all the assets in the **NEW** folder are published to Experience Manager Assets regardless of the fact they were published earlier. Each time a **Contribution** folder is published from Brand Portal to Experience Manager Assets, it replaces the content of the **NEW** folder.



**Question: How to upload new assets in a Contribution folder?**

**Answer:** Refer to the detailed documentation for [Uploading assets to the Contribution folder](brand-portal-publish-contribution-folder-to-brand-portal.md).



**Question: I cannot see thumbnails or previews for the assets uploaded to the NEW folder.**

**Answer:** It is as designed, because there is no workflow run at the Brand Portal end.



**Question: What happens if a folder is published from Experience Manager Assets to Brand Portal that is in flux?**

**Answer:** In Experience Manager Assets, logs are maintained for each time a folder is published to Brand Portal. At the time of publishing, all the assets that are not published to Brand Portal get added to a replication queue. Any asset added to the folder after the publishing job is triggered are not published to Brand Portal. When an Experience Manager Assets user publishes the folder again, only the assets that were not published earlier (existing in the replication queue) are published to Brand Portal. This process holds true for any folder published from Experience Manager Assets to Brand Portal, and SHARED folder within a Contribution folder.

**Question: Who do I contact with questions?**

**Answer:** Contact your Adobe Account Manager or Customer Support.

>[!NOTE]
>
>The release schedule is tentative and subject to change. Contact your Adobe Account Manager or Customer Support to get the updated release schedule.


## Product Access and Support (Restricted Sites) {#product-access-and-support-restricted-sites}

These sites are only available to customers. If you are a customer and require access, contact your Adobe Account Manager.

<!--
* [](https://daycare.day.com) [Product Access](https://login.marketing.adobe.com)

* [Adobe Customer Support]()
-->
