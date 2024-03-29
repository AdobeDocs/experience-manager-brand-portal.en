---
title: Frequently Asked Questions
seo-title: 
description: Get an insight into the frequently asked questions in the Adobe Experience Manager Assets Brand Portal.
seo-description: 
uuid: 
content-type: reference
contentOwner: Vishabh Gupta
topic-tags: frequently-asked-questions
products: SG_EXPERIENCEMANAGER/Brand_Portal
discoiquuid:
exl-id: 4a8f7fbd-7485-421d-a8db-755324d2dbef
---
# Frequently Asked Questions {#frequently-asked-questions}

The Brand Portal FAQs focuses on the end-users queries and issues they might encounter while working with the latest Experience Manager Assets Brand Portal 6.4.6 release or earlier versions.


## Brand Portal 6.4.6 FAQs  {#faqs-bp646}

**Ques. The existing legacy OAuth endpoint (`https://legacy-oauth.cloud.adobe.io/login`) is not working. What could be the possible reason?**

**Ans.** Legacy OAuth configuration is deprecated. You must upgrade Experience Manager Assets author instances to the latest service pack and configure it via Adobe Developer Console. See [Configure Experience Manager Assets with Brand Portal](configure-aem-assets-with-brand-portal.md) for details. However, for Legacy OAuth configuration to work until you upgrade, update the Legacy OAuth endpoint to `https://hypnosisprod.ethos11-prod-or1.ethos.adobe.net/`.   

<!--
**Ques. I have created a collection using the asset link shared by the administrator. But I am unable to create a share link for my collection. Do I need special permissions to do this?**

**Ans.** The functionality is by design, the viewer users are not permitted to share link for collections as they have limited privileges due to which they cannot add users to create a share link. It is a known issue that the share link for collections is currently visible to the viewer users. This issue will be fixed in the upcoming release, the option to share link for the collections will not be available to the viewer users.    
-->

**Ques. I am not able to publish the contribution folder's assets from Brand Portal to Experience Manager Assets after upgrading to Adobe Developer Console. My author instance is on Experience Manager Assets 6.5.4. What could be the possible reason?**

**Ans.** Yes, there is a known issue while publishing contribution folder's assets to Experience Manager Assets 6.5.4 via Adobe Developer Console. 

The issue is fixed in Experience Manager Assets 6.5.5. You can upgrade your Experience Manager Assets instance to the latest service pack and [upgrade your configurations](https://experienceleague.adobe.com/docs/experience-manager-65/assets/brandportal/configure-aem-assets-with-brand-portal.html#upgrade-integration-65) on Adobe Developer Console. 

<!--
Broken link of download hotfix, comment out this section until we have the latest URL.

For immediate fix on AEM 6.5.4, it is recommended to [download the hotfix](https://www.adobeaemcloud.com/content/marketplace/marketplaceProxy.html?packagePath=/content/companies/public/adobe/packages/cq650/hotfix/cq-6.5.0-hotfix-33041) and install on your AEM author instance.
-->

**Ques. I do not see the contribution folder's content published from Brand Portal in Experience Manager Assets. What could be the possible reason?**

**Ans.** Contact your Experience Manager Assets administrator to verify the configurations and ensure that your Brand Portal tenant is configured with only one Experience Manager Assets author instance.   

This issue possibly occurs when you have configured a Brand Portal tenant on multiple Experience Manager Assets author instances. For example, the administrator configures the same Brand Portal tenant on the Experience Manager Assets author instance of staging and production environment. In this case, the asset publishing triggers in Brand Portal but the Experience Manager Assets author instance could not import the asset coz the replication agent does not receive the requesting token.  


**Ques. I am unable to publish assets from Experience Manager Assets to Brand Portal. The replication log states that the connection timed out. Is there a quick fix?**

**Ans.** Usually the publishing fails with a timeout error if there are multiple pending requests in the replication queue. To resolve this issue, ensure that the replication agents are configured to avoid timeout. 

Perform the following steps to configure the replication agent:

1. Log in to your Experience Manager Assets author instance.
1. From the **Tools** panel, navigate to **[!UICONTROL Deployment]** > **[!UICONTROL Replication]**.
1. In the Replication page, click **[!UICONTROL Agents on author]**. You can see the four replication agents for your Brand Portal tenant. 
1. Click the replication agent URL to open the agent details.
1. Click **[!UICONTROL Edit]** to modify the replication agent settings.
1. In Agent Settings, click the **[!UICONTROL Extended]** tab. 
1. Select the **[!UICONTROL Close Connection]** check box.
1. Repeat steps 4 through 7 to configure all the four replication agents. 
1. Restart the server and verify the connection.


## Brand Portal 6.4.5 FAQs  {#faqs-bp645}

**Ques. What is the major change in Brand Portal 6.4.5 release?**

**Ans.** Experience Manager Assets Brand Portal 6.4.5 is a feature release which allows the Brand Portal users to upload content from wihtin the Brand Portal instance and publish the Contribution folder back to Experience Manager Assets without needing administrator rights.
For more information, see [Asset Sourcing in Brand Portal](brand-portal-asset-sourcing.md).



**Ques. Will I lose access to any existing assets, features, or configurations I have created?**

**Ans.** All of your existing features and configurations remain intact. Your end-users are not impacted, and your content remains intact.



**Ques. When am I moving to the new version of Brand Portal?**

**Ans.** Brand Portal 6.4.5 was released to production in October 2019. And the next Brand Portal version is expected to be released in Q3 2020. 
For updates and version change, it is recommended to track the [Release Notes](brand-portal-release-notes.md) and [What's New in Brand Portal](whats-new.md).



**Ques. Will my users be impacted?**

**Ans.** The Brand Portal 6.4.5 release is exclusively within Brand Portal, so there is no impact to your end-users.



**Ques. Is there any action required on my part as a Brand Portal user?**

**Ans.** Brand Portal 6.4.5 release comes with a new feature named Asset Sourcing. The administrator has to configure Asset Sourcing feature in Experience Manager Assets to enable the feature for the Brand Portal users. For more information, refer to [Enable Asset Sourcing](brand-portal-asset-sourcing.md).



**Ques. Who can create a Contribution folder?**

**Ans.** Any Experience Manager Assets user having permissions to create a new folder in Experience Manager Assets, can create a **Contribution** folder. To create a **Contribution** folder, create a new folder of type **Asset Contribution**. 
This folder is shared with the active Brand Portal users for contribution.  



**Ques. What does a Contribution folder contains?**

**Ans.** **Contribution** folder contains two sub-folders **NEW** and **SHARED**. Initially, the NEW folder is blank and the SHARED folder contains the reference content (reusable assets) for the Brand Portal users. 
The Brand Portal users access the **Contribution** folder and upload content in the **NEW** folder.  



**Ques.  Can I modify the name of an existing Contribution folder?**

**Ans.** **No**, you cannot modify the name of an existing **Contribution** folder.  



**Ques. What is asset requirements w.r.t contribution?**

**Ans.** The **Brief** document attached to the **Contribution** folder and the reference content (reusable assets) uploaded in the **SHARED** folder helps the Brand Portal user to understand the need of contribution and expectations as a contributor, and is collectively called as the asset requirements.  



**Ques. Can I upload assets to any permitted folder?**

**Ans.** Not all the permitted folders. A Brand Portal user can upload content only to the **Contribution** folder which is shared by the Experience Manager Assets or Brand Portal administrator.



**Ques. How do I get access to a Contribution folder?**

**Ans.** You can access a **Contribution** folder only if it has been shared with you. You will get an email/pulse notification whenever a Contribution folder is shared with you. You can either access the Contribution folder via the link shared in the email, or login to your Brand Portal instance and navigate to the bell icon for notfication to access the Contribution folder.  

>[!NOTE]
>
>If you are not an existing Brand Portal user, request the Experience Manager Assets administrator to create your user in the admin console and add your profile to the user configuration file in Brand Portal users list. 

**Ques. What is the Format of the CSV file for user import?**

**Ans.** The format is same as what is supported by Admin Console for bulk user import. Email, first name, and last name are mandatory.



**Ques. What populates the list of users (Brand Portal contributors) in the Asset Contribution user drop-down?**

**Ans.** The users in the drop-down are populated from the Brand Portal user configuration (.csv) file uploaded in Experience Manager Assets.



**Ques. Where can I see the status of import and publish jobs?**

**Ans.** In Experience Manager Assets, you can see the status of an import in **async** job page. In Brand Portal, you can see the status of a publish job in **[!UICONTROL Tools > Asset Contribution status]**.



**Ques. What is the frequency of an import job which runs periodically in Experience Manager?**

**Ans.** In Experience Manager Assets, polling is run every 5 mins.



**Ques. Is there any threashold on the number of times a folder can be published from Brand Portal to Experience Manager Assets?**

**Ans.** No, all the assets in the **NEW** folder are published to Experience Manager Assets regardless of the fact they were published earlier. Everytime a **Contribution** folder is published from Brand Portal to Experience Manager Assets, it overrides the content of the **NEW** folder. 



**Ques. How to upload new assets in a Contribution folder?**

**Ans.** Refer to the detailed documentation for [Uploading assets to Contribution folder](brand-portal-publish-contribution-folder-to-brand-portal.md).



**Ques. I do not see thumbnails/previews on the assets uploaded to the NEW folder by a Brand Portal user?**

**Ans.** It is as designed, coz there is no workflow being run at the Brand Portal end.



**Ques. What happens if a folder is published from Experience Manager Assets to Brand Portal that is in flux?**

**Ans.** In Experience Manager Assets, logs are maintained for each time a folder is published to Brand Portal. At the time of publishing, all the assets which are not published to Brand Portal are put in a replication queue. Any asset added to the folder after the publishing job is triggered are not published to Brand Portal. When the Experience Manager Assets user publishes the folder again, only the assets which were not published earlier (existing in replication queue) are published to Brand Portal. 
This holds true for any folder published from Experience Manager Assets to Brand Portal, and SHARED folder within a Contribution folder.

**Ques. Who do I contact with questions?**

**Ans.** Contact your Adobe Account Manager or Customer Support.

>[!NOTE]
>
>Release schedule is tentative and subject to change. Contact your Adobe Account Manager or Customer Support to get the updated release schedule.


## Product Access and Support (Restricted Sites) {#product-access-and-support-restricted-sites}

These sites are only available to customers. If you are a customer and require access, contact your Adobe account manager.

<!--
* [](https://daycare.day.com) [Product Access](https://login.marketing.adobe.com)

* [Adobe Customer Support]()
-->
