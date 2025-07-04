---
title: What's new in Experience Manager Assets Brand Portal
description: Learn about the new features and enhancements in Experience Manager Assets Brand Portal version 2024.10.0.
products: SG_EXPERIENCEMANAGER/Brand_Portal
content-type: reference
contentOwner: Kirandeep Kour
topic-tags: introduction
exl-id: 69335d85-ed96-42e6-8a84-1b8d7367522c
---
# What's new in Experience Manager Assets Brand Portal {#what-s-new-in-aem-assets-brand-portal}

Adobe Experience Manager Assets Brand Portal helps you easily acquire, control, and securely distribute approved creative assets to external parties and internal business users across devices. It helps improve the efficiency of asset sharing, accelerates the time-to-market for assets, and reduces the risk of non-compliance and unauthorized access. Adobe is working to improve the overall Brand Portal experience. Here is a sneak peek into the new features and enhancements.

## What changed in 2024.10.0 {#what-changed-in-October-2024}

Brand Portal 2024.10.0 is an internal release that includes fixes to the critical issues. See the latest [Brand Portal Release Notes](brand-portal-release-notes.md).

## What changed in 2024.02.0 {#what-changed-in-February-2024}

Brand Portal 2024.02.0 is an internal release that includes fixes to the critical issues. See the latest [Brand Portal Release Notes](brand-portal-release-notes.md).

## What changed in 2023.10.0 {#what-changed-in-October-2023}

Brand Portal 2023.10.0 is an internal release that includes fixes to the critical issues. See the latest [Brand Portal Release Notes](brand-portal-release-notes.md).

## What changed in 2023.08.0 {#what-changed-in-August-2023}

Brand Portal 2023.08.0 is an internal release that includes fixes to the critical issues. See the latest [Brand Portal Release Notes](brand-portal-release-notes.md).

## What changed in 2023.05.0 {#what-changed-in-May-2023}

Brand Portal 2023.05.0 is an internal release that includes fixes to the critical issues. See the latest [Brand Portal Release Notes](brand-portal-release-notes.md).

## What changed in 2023.02.0 {#what-changed-in-February-2023}

Brand Portal 2023.02.0 is an internal release that includes fixes to the critical issues. See the latest [Brand Portal Release Notes](brand-portal-release-notes.md).

## What changed in 2022.10.0 {#what-changed-in-October-2022}

Brand Portal 2022.10.0 is an internal release that includes fixes to the critical issues. See the latest [Brand Portal Release Notes](brand-portal-release-notes.md).

## What changed in 2022.08.0 {#what-changed-in-August-2022}

Brand Portal 2022.08.0 is an internal release that includes fixes to the critical issues. See the latest [Brand Portal Release Notes](brand-portal-release-notes.md).

## What changed in 2022.05.0 {#what-changed-in-May-2022}

Brand Portal now runs jobs automatically every twelve hours to delete all Brand Portal assets that are published to AEM. As a result, you do not need to delete the assets in the Contribution folder manually to keep the folder size below the threshold limit. You can also monitor the status of the automatically run delete jobs using the **[!UICONTROL Tools]** > **[!UICONTROL Asset Contribution Status]** > **[!UICONTROL Deletion Reports]** option in Brand Portal. The report for a job provides the following details:

* Job start time
* Job end time
* Job status
* Total assets included in a job
* Total assets successfully deleted in a job
* Total storage made available as a result of the job run

![Deletion Report](assets/deletion-reports.png)

  You can also drill down further to view the details of each asset included in a delete job. Details such as asset title, size, author, delete status, and deletion time are included in the report.

  ![Deletion Report Detailed](assets/deletion-reports-detailed.png)

  In addition, Brand Portal 2022.05.0 includes fixes to the critical issues. See the latest [Brand Portal Release Notes](brand-portal-release-notes.md).


## What changed in 2022.02.0 {#what-changed-in-Feb-2022}

Brand Portal 2022.02.0 is an internal release that includes fixes to the critical issues. See the latest [Brand Portal Release Notes](brand-portal-release-notes.md).

## What changed in 2021.10.0 {#what-changed-in-october-2021}

Brand Portal 2021.10.0 is an internal release that includes fixes to the critical issues. See the latest [Brand Portal Release Notes](brand-portal-release-notes.md).

## What changed in 2021.08.0 {#what-changed-in-august-2021}

Brand Portal 2021.08.0 is an internal release introducing Business profiles for enterprise and teams customers to give organizations better control over their assets. The users now have organization-specific entitlement in the new and migrated organizations. During migration, all the existing Adobe ID accounts are migrated over to Business IDs. 

* Business IDs to all new and existing organizations after they are migrated. 
* Business IDs do not require any specific setup, such as claiming a domain or setting up an SSO.
* You can add users with any email address, including public email domains such as gmail.com or outlook.com.

**Impact on the Brand Portal users**

The migration does not impact on your existing data-set, assets, users, or any settings. The only internal change that takes place during the migration is the entitlement of your existing organization to Business profiles. 

>[!NOTE]
>
>Business profiles are currently applicable for the new organizations that are created after August 16, 2021. 
>
>Until your organization is migrated, you can continue to use Adobe ID, Enterprise ID, or Federated ID types to access the organization.   

### Reference articles {#reference-articles}

* [Introducing Adobe Profiles](https://helpx.adobe.com/enterprise/kb/introducing-adobe-profiles.html)

* [Manage Adobe Profiles](https://helpx.adobe.com/enterprise/using/manage-adobe-profiles.html)

* [Update to Sign in experience for users and admins](https://helpx.adobe.com/enterprise/using/storage-for-business.html#new-admin-sign-in-exp)

* [Log in restriction during migration](https://helpx.adobe.com/enterprise/kb/account-temporarily-unavailable.html)

* [Manage users in Admin Console](https://helpx.adobe.com/enterprise/using/manage-users-individually.html)

* [Manage product profiles for enterprise users](https://helpx.adobe.com/enterprise/using/manage-product-profiles.html#assign-users)

* [Domain trust](https://helpx.adobe.com/enterprise/admin-guide.html/enterprise/using/set-up-identity.html#directory-trusting)


<!--   
### Add new users to T2E organization   {#add-users-to-T2E-org}

On adding a new user in Admin Console for a new or migrated T2E organization, the user will have to perform an additional step **Join Team** to get entitled to the T2E organization. 

The user is entitled only if the user chooses to **Join Team**, otherwise the user won't get access to the selected T2E organization in Brand Portal. 

>[!NOTE]
>
>The workflow is not applicable to the existing Brand Portal users.

![join team](assets/join-team.png)

### Additional screen while navigating to Admin Console   {#navigate-to-admin-console}

The administrators will have to perform an additional step of selecting the T2E organization while navigating from Brand Portal to Admin Console. The workflow applies on the new and migrated T2E organizations.   

Selection of the T2E organization is a one-time activity and is not required everytime the administrator navigates from Brand Portal to Admin Console.

1. Log in to a T2E organization in Brand Portal as administrator.
1. Go to **[!UICONTROL Tools]** > **[!UICONTROL Users]** > **[!UICONTROL Management]** and click on the link **[!UICONTROL Launch Admin Console]**. 

   Or, go to **[!UICONTROL Unified Shell]** > **[!UICONTROL Administration]** and click on the link **[!UICONTROL Launch Admin Console]**. 
1. Search the T2E organization to login to Admin Console.

   ![org picker](assets/org-picker.png)


### Restriction during migration of an organization   {#login-restriction}

When an organization is undergoing T2E migration, the users of that organization will not be able to login to Brand Portal. The following error message appears on the screen. However, the migration won't impact the active user session until the token expires. 

![login restriction](assets/login-restriction.png)

Once the migration is complete, the users can login to Brand Portal. The users will receive an email notification containing the entitlement changes. If the users are entitled to more than one organization, they will have to select the organization at the time of login. 
-->


<!--
For a new or migrated T2E orgnization, the users will have an organization specific entitlement. A user can have multiple entitlements with the same email id for different T2E organizations. 
-->

## What changed in 2021.06.0 {#what-changed-in-june-2021}

Brand Portal 2021.06.0 is an internal release that includes fixes to the critical issues. See the latest [Brand Portal Release Notes](brand-portal-release-notes.md).


## What changed in 2021.02.0 {#what-changed-in-feb-2021}

Brand Portal 2021.02.0 enhances AEM Assets as a Cloud Service with the activation workflow and Asset Sourcing feature. It also improves the asset download experience and includes critical fixes. It also enables the administrators to configure the default download behavior of folders, collections, and bulk download of assets at tenant level. The Brand Portal **[!UICONTROL Usage Report]** has also been modified to reflect the active Brand Portal users.

>[!IMPORTANT]
>
> * Brand Portal is in maintenance mode. All new product innovations are available on [Content Hub](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/content-hub/product-overview).
> * If you still need to activate Brand Portal, contact your Adobe representative with details of your use case and other specific requirements.
> * Brand Portal is not available with [Assets Prime](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/assets-prime) or [Assets Ultimate](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/assets-ultimate-overview). However, existing Assets as a Cloud Service customers, who already have access to Brand Portal can continue to use it when they transition to Assets Ultimate.

<!--

### Activate Brand Portal on AEM Assets as a Cloud Service {#bp-automation-on-cloud-service}

AEM Assets as a Cloud Service is now entitled to have a pre-configured Brand Portal instance. The Cloud Manager user can activate Brand Portal on the AEM Assets as a Cloud Service instance.

Earlier, AEM Assets as a Cloud Service was manually configured with Brand Portal using Adobe Developer Console.

The Cloud Manager user triggers the activation workflow that creates the required configurations at the backend and activates Brand Portal on the same IMS org as of the AEM Assets as a Cloud Service instance. 

To activate Brand Portal on your AEM Assets as a Cloud Service instance:

1. Log in to Adobe Cloud Manager and navigate to **[!UICONTROL Environments]**.
1. Select the environments (one by one) from the list. Once you find the environment associated with Brand Portal, click on the **[!UICONTROL Activate Brand Portal]** button to begin the activation workflow. 
1. Once the Brand Portal tenant is activated, the status changes to Activated.

![View Status](assets/create-environment5.png)

See [activate Brand Portal on AEM Assets as a Cloud Service](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/brand-portal/configure-aem-assets-with-brand-portal).

### Asset Sourcing on AEM Assets as a Cloud Service {#asset-sourcing-on-cloud-service}

The Asset Sourcing feature is now available on AEM Assets as a Cloud Service. The feature is by default enabled for all the cloud service users. The permitted Brand Portal users can contribute to Asset Sourcing by uploading new assets to the contribution folders and publish the contribution folder from Brand Portal to AEM Assets as a Cloud Service instance. Administrators can review and approve contributions from Brand Portal users before distributing them to other users.     

Earlier, Asset Sourcing was only available on AEM Assets (on premise and managed service). 

See [Asset Sourcing in Brand Portal](https://experienceleague.adobe.com/en/docs/experience-manager-brand-portal/using/asset-sourcing-in-brand-portal/brand-portal-asset-sourcing).
-->

### Asset Download {#asset-download-setting}

In addition to the existing **[!UICONTROL Download Settings]**, the Brand Portal administrators can now configure the **[!UICONTROL Asset Download]** setting. This setting allows the administrators to govern the default download behavior of folders, collections, and bulk download of assets (more than 20 assets) at tenant level.  

<!--
Earlier, all the asset renditions were directly downloaded in a zip folder in case of folder, collection, and bulk download of assets. As the **[!UICONTROL Download]** dialog box is skipped for folders or collections, there was no mechanism to control the downloading behaviour of the assets. Due to this, the users were finding it difficut to search for a particular asset rendition from a folder containing huge bunch of downloaded renditions. 
-->

Earlier, all the asset renditions were directly downloaded in a zip folder. The **[!UICONTROL Download]** dialog box was skipped for folders and collections. And, there was no method to control over the download behavior of the assets, making it difficult to search for a particular rendition from many downloads. 

**[!UICONTROL Asset Download]** setting now provide an option to create a separate folder for each asset while downloading the folders, collections, or bulk download of assets. 

If the **[!UICONTROL Asset Download]** setting is disabled, the folders or collections are downloaded in a zip folder containing all the asset renditions under the same folder, except for downloading the assets using share link.  


Log in to your Brand Portal tenant as an administrator and navigate to **[!UICONTROL Tools]** > **[!UICONTROL Download]**. The administrators can enable the **[!UICONTROL Asset Download]** setting to create a separate folder for each asset while downloading folders, collections, and bulk download of assets. 

![](assets/download-settings-new.png)

See [download assets from Brand Portal](https://experienceleague.adobe.com/en/docs/experience-manager-brand-portal/using/download/brand-portal-download-assets).
<!--
### Download using Share link {#download-using-share-link}

The default behavior of downloading the assets using share link is now independent of the **[!UICONTROL Download Settings]**. A separate folder is created for each asset while downloading the assets using share link. 
-->

### Usage report {#usage-report}

The Brand Portal **[!UICONTROL Usage Report]** has been modified to reflect only the active Brand Portal users. The Brand Portal users who are not assigned to any product profile in the Admin Console are considered as inactive users and are not reflected in the **[!UICONTROL Usage Report]**.

Earlier, both active and inactive users were shown in the Usage Report.

![](assets/usage-report.png)

## What changed in 2020.10.0 {#what-changed-in-oct-2020}

Brand Portal 2020.10.0 is an enhancement release that focuses on simplifying the asset download experience and includes critical fixes. The enhancement introduces a new and improved workflow for asset downloads, with options to exclude renditions and direct downloads from the **[!UICONTROL Renditions]** panel. It also allows configuration of access and download rights for specific user groups, and provides easy navigation to files, collections, and shared links from all Brand Portal pages. See the [Brand Portal Release Notes](brand-portal-release-notes.md).


### Simplified download experience {#download-dialog}

Previously, the **[!UICONTROL Download]** dialog box offered multiple options like creating separate folders for each asset, emailing assets, selecting original assets, and more. These options were confusing for non-technical or new users, especially when downloading multiple assets or folders. Also, the user could not see all the asset renditions or exclude a specific custom or dynamic rendition.

The new **[!UICONTROL Download]** dialog box generalizes the asset selection and filtration process that makes it easier for the Brand Portal users to take effective decisions while downloading the asset renditions. It lists all the selected assets and their renditions depending on the [**[!UICONTROL Download]**](brand-portal-download-assets.md) configuration and **[!UICONTROL Download]** settings. 

>[!NOTE]
>
>All the users now have **[!UICONTROL Fast Download]** enabled by default and requires IBM&reg; [Aspera Connect 3.9.9](https://www.ibm.com/support/fixcentral/swg/selectFixes?parent=ibm~Other%20software&product=ibm/Other+software/IBM+Aspera+Connect&release=3.9.9&platform=All&function=all) installed in their browser's extension before downloading the assets from Brand Portal.

<!--
If any of the **[!UICONTROL Custom Rendition]** or **[!UICONTROL System Rendition]** is enabled in the [**[!UICONTROL Download]**](brand-portal-download-assets.md) configuration and **[!UICONTROL Download]** settings are enabled for the group users, the new **[!UICONTROL Download]** dialog box appears with all the renditions of the selected assets or folders containing assets in a List View. 
-->

From the **[!UICONTROL Download]** dialog box, the users can:

* View all the available renditions of any asset in the download list.
* Exclude renditions of the assets that are not required for download.
* Apply the same set of renditions to all the similar asset types in one click.
* Apply a different set of renditions for different asset types.
* Create a separate folder for each asset.
* Download selected assets and their renditions.

The download workflow is consistent for stand-alone assets, multiple assets, folders with assets, licensed or unlicensed assets, and when downloading assets by way of share link. See [steps to download assets from Brand Portal](https://experienceleague.adobe.com/en/docs/experience-manager-brand-portal/using/download/brand-portal-download-assets).

![download-dialog-box](assets/download-dialog-box.png)

### Quick navigation {#quick-navigation}

Earlier, the option to view **[!UICONTROL Files]**, **[!UICONTROL Collections]**, and **[!UICONTROL Shared Links]** were hidden and required multiple clicks every time the user wanted to switch to another view. 

In Brand Portal 2020.10.0, the users can navigate to **[!UICONTROL Files]**, **[!UICONTROL Collections]**, and **[!UICONTROL Shared Links]** from all the Brand Portal pages in one-click using the quick navigation links.

![collection-navigation](assets/collection-navigation.png)

### Enhanced rendition panel {#rendition-panel}

Earlier, the users could only view the original asset and its renditions in the **[!UICONTROL Renditions]** panel if any of the **[!UICONTROL Custom Rendition]** or **[!UICONTROL System Rendition]** was enabled in the **[!UICONTROL Download]** configuration. Also, the users had to download all the asset renditions as there was no filter to exclude specific custom or dynamic renditions that were not required. 

<!--
Earlier, if any of the custom or system renditions was enabled in the **[!UICONTROL Download]** settings, an additional **[!UICONTROL Download]** dialog box appeared on clicking the **[!UICONTROL Download]** button wherein the user had to manually select the set of renditions (original asset, custom renditions, dynamic renditions) to download.
There was no filter to exclude specific custom or dynamic renditions which were not required for download.
-->

In Brand Portal 2020.10.0, the users can exclude specific renditions and directly [download the selected renditions from the Renditions panel](brand-portal-download-assets.md#download-assets-from-asset-details-page) in the asset details page without having to open the **[!UICONTROL Download]** dialog box. 


<!-- 
In Brand Portal 2020.10.0, direct download and exclude renditions features are introduced in the **[!UICONTROL Renditions]** panel on the asset details page. All the renditions (original asset, custom renditions, dynamic renditions) under the rendition panel are now associated with a check box and are enabled by default. 

The user can clear the check boxes to exclude the renditions which are not required for download. And can click on the **[!UICONTROL Download]** button in the **[!UICONTROL Renditions]** panel to directly download the selected set of renditions in a zip folder without having to open the **[!UICONTROL Download]** dialog box.
-->

![renditions-panel](assets/renditions-panel.png)


### Configure download settings {#download-permissions}

Brand Portal administrators can now configure settings for user groups to view or download original assets and renditions, or both, from the asset details page, in addition to existing **[!UICONTROL Download]** configurations.

Log in to your Brand Portal tenant as an administrator and navigate to **[!UICONTROL Tools]** > **[!UICONTROL Users]**.

In the **[!UICONTROL User Roles]** page, navigate to the **[!UICONTROL Groups]** tab to configure the view and (or) download settings for the user groups.

Earlier, the settings were available only to restrict the group users from downloading the original asset.

The **[!UICONTROL Groups]** tab on the **[!UICONTROL User Roles]** page allows administrators to configure the view and download settings:

* If both **[!UICONTROL Download Original]** and **[!UICONTROL Download Renditions]** settings are turned-on, the users of the selected group can view and download the original assets and their renditions.
* If both the settings are turned-off, the users can only view the original assets. The asset renditions are not visible to the users on the asset details page.
* If only **[!UICONTROL Download Original]** setting is turned-on, the users can view and download only the original assets from the asset details page.
* If only **[!UICONTROL Download Renditions]** setting is turned-on, the users can view the original asset but cannot download it. Though, the user can view and download the asset renditions.

See [configure asset download](https://experienceleague.adobe.com/en/docs/experience-manager-brand-portal/using/download/brand-portal-download-assets#configure-download-permissions).

![view-download-permission](assets/download-permissions.png)

>[!NOTE]
>
>If a user is added to multiple groups and if one of those groups has restrictions, the restrictions apply to the user.

 
<!--
>Restrictions to access the original asset and their renditions do not apply to administrators even if they are members of restricted groups.
 >
 >The users can always download assets and their renditions from the repository using a `curl` request even if the download configurations are turned-off.
 >
-->

## What changed in 6.4.7 {#what-changed-in-647}

Brand Portal 6.4.7 release brings in the Document Viewer, enhances the experience for downloading assets, and includes critical fixes. See the latest [Brand Portal Release Notes](brand-portal-release-notes.md).

<!--
Brand Portal 6.4.7 release brings in the Document Viewer, leverages the Brand Portal administrators to configure asset download, and centers top customer requests. See latest [Brand Portal Release Notes](brand-portal-release-notes.md).
-->

### Document Viewer {#doc-viewer}

The Document Viewer enhances the PDF viewing experience. It provides a similar experience as of the Adobe Document Cloud while viewing the PDF files in Brand Portal. 

Earlier, limited options were available to view the PDF files. 

Brand Portal users can use Document Viewer to view pages and bookmarks, search text, zoom in and out, and navigate pages. They can switch to a specific page, fit to a window or screen, and toggle the toolbar visibility. 

>[!NOTE]
>
>The viewing experience for other document formats remains unchanged.


![](assets/doc-viewer.png)

### Download Experience {#download-configurations}

The asset download process is revamped, providing a simplified user experience while [downloading assets from Brand Portal](brand-portal-download-assets.md). 

The existing workflow of downloading assets from Brand Portal is inevitably followed by the appearance of a **[!UICONTROL Download]** dialog box with multiple download options from which to choose. 

In Brand Portal 6.4.7, the Brand Portal administrators can configure the asset **[!UICONTROL Download]** settings. The available configurations are:

* **[!UICONTROL Fast Download]**
* **[!UICONTROL Custom Renditions]**
* **[!UICONTROL System Renditions]**

The Brand Portal administrator can enable any combination to configure asset download.  

<!--In Brand Portal 6.4.7, fast download, custom renditions, and system renditions are the three configurations available.-->

* If both **[!UICONTROL Custom Renditions]** and **[!UICONTROL System Renditions]** configurations are turned-off, the original renditions of the assets are downloaded without any additional dialog box, which simplifies the download experience for the Brand Portal users.

* If any of the **[!UICONTROL Custom Rendition]** or **[!UICONTROL System Rendition]** is enabled, the **[!UICONTROL Download]** dialog box appears and the original asset along with the asset renditions are downloaded. Enabling **[!UICONTROL Fast Download]** configuration speeds-up the download process.

Based on the configuration, the download workflow remains constant for stand-alone assets, multiple assets, and folders containing assets. It also includes licensed or unlicensed assets, and downloading assets using a share link. 


## What changed in 6.4.6 {#what-changed-in-646}

In Brand Portal 6.4.6, the authorization channel between AEM Assets and Brand Portal is changed. Brand Portal is now supported on AEM Assets as a Cloud Service, AEM Assets 6.3 and above. In AEM Assets 6.3 and above, Brand Portal was initially configured in Classic UI using the Legacy OAuth Gateway. This gateway employs the JWT token exchange to obtain an IMS Access token for authorization. AEM Assets are now configured with Brand Portal through Adobe Developer Console, which procures an IMS token for authorization of your Brand Portal tenant.

<!-- The steps to configure integration are different depending on your AEM version, and whether you are configuring for the first-time, or upgrading the existing integration:
-->

<!--
  
   | **AEM Version** |**New Integration** |**Upgrade Integration** |
|---|---|---|
| **AEM 6.5** |[Create new integration](../using/brand-portal-configure-integration-65.md) |[Upgrade existing integration](../using/brand-portal-configure-integration-65.md#upgrade-integration-65) | 
| **AEM 6.4** |[Create new integration](../using/brand-portal-configure-integration-64.md) |[Upgrade existing integration](../using/brand-portal-configure-integration-64.md#upgrade-integration-64) | 
| **AEM 6.3** |[Create new integration](../using/brand-portal-configure-integration-63.md) |[Upgrade existing integration](../using/brand-portal-configure-integration-63.md#upgrade-integration-63) | 
| **AEM 6.2** | | 

   -->

The steps to configure AEM Assets with Brand Portal are different depending on your AEM version, and whether you are configuring for the first time, or upgrading the existing configurations:

<!--| **AEM Version** |**New Configuration** |**Upgrade Configuration** |
|---|---|---|
| **AEM 6.5 (6.5.4.0 and above)** |[Create configuration](../using/brand-portal-configure-integration-65.md) |[Upgrade configuration](../using/brand-portal-configure-integration-65.md#upgrade-integration-65) | 
| **AEM 6.4 (6.4.8.0 and above)** |[Create configuration](../using/brand-portal-configure-integration-64.md) |[Upgrade configuration](../using/brand-portal-configure-integration-64.md#upgrade-integration-64) | 
| **AEM 6.3 (6.3.3.8 and above)** |[Create configuration](../using/brand-portal-configure-integration-63.md) |[Upgrade configuration](../using/brand-portal-configure-integration-63.md#upgrade-integration-63) | 

-->


<!-- AEM Assets configuration with Brand Portal on Adobe I/O is supported on:
* AEM 6.5.4.0 and above
* AEM 6.4.8.0 and above
* AEM 6.3.3.8 and above -->

| **AEM Version** |**New Configuration** |**Upgrade Configuration** |
|---|---|---|
| **AEM Assets as a Cloud Service** |[Create configuration](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/brand-portal/configure-aem-assets-with-brand-portal) |- |
| **AEM 6.5 (6.5.4.0 and above)** |[Create configuration](https://experienceleague.adobe.com/en/docs/experience-manager-65/content/assets/brandportal/configure-aem-assets-with-brand-portal) |[Upgrade configuration](https://experienceleague.adobe.com/en/docs/experience-manager-65/content/assets/brandportal/configure-aem-assets-with-brand-portal#upgrade-integration-65) | 

>[!NOTE]
>
>Adobe recommends you update your AEM instance to use the latest service pack.

See the [Brand Portal Release Notes](brand-portal-release-notes.md).

See [Brand Portal FAQs](brand-portal-faqs.md).

## What changed in 6.4.5 {#what-changed-in-645}


Brand Portal 6.4.5 lets external agencies and teams upload content to Brand Portal and publish to AEM Assets, all without needing access to the author environment. This feature is called **[Asset Sourcing in Brand Portal](brand-portal-asset-sourcing.md)**, and improves customer experiences by providing a two-way mechanism for users to both contribute and share assets with other globally distributed Brand Portal users.

### Asset Sourcing in Brand Portal {#asset-sourcing-in-bp}

Asset Sourcing allows AEM users (administrators/non-admin users) to create folders with an extra **Asset Contribution** property, ensuring the new folder created open to asset submission by Brand Portal users. It automatically triggers a workflow that creates two additional sub folders, called NEW and SHARED, within the newly created **Contribution** folder.

The AEM user uploads a brief and baseline assets to the **SHARED** folder. They define the types of assets needed in the contribution folder, ensuring Brand Portal users have the necessary reference information. The administrator can then grant active Brand Portal users access to the contribution folder before publishing the newly created **Contribution** folder to Brand Portal.


Once the user is finished adding content in the **NEW** folder, they can publish the contribution folder back to the AEM Author environment. It may take a few minutes to complete the import and reflect the newly published content within AEM Assets.

Also, all existing functionality remains unchanged. Brand Portal users can view, search, and download assets from the contribution folder and from the other permitted folders. And administrators can further share the contribution folder, modify properties and add assets to collections. 

>[!NOTE]
>
>Asset Sourcing in Brand Portal is supported on AEM 6.5.2.0 and above.
>
>The feature is not supported in the earlier versions, AEM 6.3 and AEM 6.4.

### Upload assets to contribution folder {#upload-assets-in-bp} 

Brand Portal users with appropriate permissions can upload individual assets or folder (.zip file) containing multiple assets to the contribution folder. A user can upload multiple assets to an asset contribution folder. However, only one folder can be created at a time. 

The Brand Portal users are only able to upload assets to the **NEW** subfolder. The **SHARED** folder is meant for the distribution of requirements and baseline assets. 


![](assets/upload-asset6.png)

![](assets/upload-asset4.png)


### Publish contribution folder to AEM Assets {#publish-assets-to-aem}

Once upload is complete to the **NEW** folder, Brand Portal users can then publish the contribution folder back to AEM. It may take a few minutes to import and reflect the published content/assets in AEM Assets. See [publish contribution folder to AEM Assets](brand-portal-publish-contribution-folder-to-aem-assets.md).


![](assets/upload-asset5.png)

## What changed in 6.4.4 {#what-changed-in-644}

Brand Portal 6.4.4 release focuses on enhancements to text search and top customer requests. See the latest [Brand Portal Release Notes](brand-portal-release-notes.md).

### Search enhancements

Brand Portal 6.4.4 onwards supports partial text search in Property Predicate in the filtering pane. To allow partial text search, enable **Partial Search** in Property Predicate in the search form.

Read on to know more about partial text search and wildcard search.

#### Partial phrase search {#partial-phrase-search}

You can now search for assets by specifying only a part, that is, a word or two, of the searched phrase in the filtering pane.

**Use case**
Partial phrase search is helpful when you are unsure of the exact combination of words occurring in the searched phrase.

For example, if your search form in Brand Portal uses Property Predicate for partial search on assets title, then specifying the term **camp** returns all the assets with the word camp in their title phrase.

![](assets/partialphrasesearch.png)

#### Wildcard search {#wildcard-search}

The Brand Portal allows using the asterisk (&#42;) with part of a word in your search query.

If you are not sure of the exact words occurring in the searched phrase, you can use a wildcard search to fill the gaps in your search query.

For example, specifying **climb&#42;** returns all the assets having words beginning with the characters **climb** in their title phrase if the search form in Brand Portal uses Property Predicate for partial search on assets title.

![](assets/wildcard-prop.png)

Similarly, specifying:

* **&#42;climb** returns all the assets having words ending with characters **climb** in their title phrase.

* **&#42;climb&#42;** returns all the assets having words comprising the characters **climb** in their title phrase.

>[!NOTE]
>
>On selecting the **Partial Search** checkbox, **Ignore Case** is selected by default.

[![](assets/see-the-guide.png)](../using/brand-portal-searching.md#facetedsearchbyapplyingfilterstosearch)

## What changed in 6.4.3 {#what-changed-in}

 Brand Portal 6.4.3 introduces an alternate alias for access URLs, a new folder hierarchy, and video support enhancements. It also introduces scheduled publishing from AEM Author to Brand Portal, operational improvements, and addresses customer requests.

### Folder hierarchy navigation for non-admins

Administrators can now configure how the folders are shown to non-admin users (Editors, Viewers, and Guest Users) on login. [Enable Folder Hierarchy](../using/brand-portal-general-configuration.md) configuration is added in **General Settings**, in the admin tools panel. If the configuration is:

* **enabled**, the folder tree starting from the root folder is visible to non-admin users. Thus, granting them a navigation experience similar to administrators.
* **disabled**, only the shared folders are displayed on the landing page.

 ![](assets/enable-folder-hierarchy.png)

The [Enable Folder Hierarchy](../using/brand-portal-general-configuration.md) functionality (when enabled) helps you differentiate the folders with the same names shared from different hierarchies. On logging in, non-admin users now see the virtual parent (and ancestor) folders of the shared folders.
 
 ![](assets/disabled-folder-hierarchy1-2.png) 
 
 ![](assets/enabled-hierarchy1-2.png)

The shared folders are organized within the respective directories in virtual folders. You can recognize these virtual folders with a lock icon.

The default thumbnail of the virtual folders is the thumbnail image of the first shared folder.

![](assets/hierarchy1-nonadmin-2.png)

[![](assets/see-the-guide.png)](../using/brand-portal-general-configuration.md)

### Search in a specific folder hierarchy or path

**Path Browser** predicate is introduced in search form to allow searching of assets in a specific directory. The default search path of search predicate for Path Browser is `/content/dam/mac/<tenant-id>/`, which can be configured by editing the default search form.

* Admin users can use Path Browser to navigate to any folder directory on Brand Portal.
* Non-admin users can use Path Browser to navigate only to the folders (and navigate back to the parent folders) shared with them.

  For example, `/content/dam/mac/<tenant-id>/folderA/folderB/folderC` is shared with a non-admin user. The user can search for assets within folderC using Path Browser. This user can also navigate to folderB and folderA (since they are ancestors of the folderC that is shared with the user).

![](assets/edit-search-form.png)


You can now restrict asset search within a specific folder you have browsed to, instead of beginning at the root folder.

Searching under these folders returns results only from the assets that have been shared with the user.

![](assets/filter-panel.png) 

[![](assets/see-the-guide.png)](../using/brand-portal-search-facets.md#listofsearchpredicates)

### Dynamic Media video renditions support

Users whose AEM Author instance is in Dynamic Media hybrid mode can preview and download the dynamic media renditions, in addition to the original video files.

To enable preview and download of dynamic media renditions on specific tenant accounts, administrators specify a **Dynamic Media Configuration**. This step includes the video service URL and registration ID in the **Video** configuration from the admin tools panel.


Dynamic Media videos can be previewed on:

* Asset details page
* Asset's Card View
* Link share preview page

Dynamic Media Video encodes can be downloaded from:

* Brand Portal
* Shared link

![](assets/edit-dynamic-media-config.png)

[![](assets/see-the-guide.png)](../using/brand-portal.md#tenantaliasforportalurl)

### Scheduled publish to Brand Portal

Assets (and folders) publish workflow from AEM 6.4.2.0 Author instance to Brand Portal can be scheduled for a later date, time.

Similarly, published assets can be removed from the portal later, by scheduling the Unpublish from Brand Portal workflow.

![](assets/schedule-publish.png)

![](assets/publishlater-workflow.png)

 [![](assets/see-the-guide.png)](../using/brand-portal.md#tenantaliasforportalurl)

### Configurable tenant alias in URL

Organizations can get their portal URL customized by having an alternate prefix in the URL. To get an alias for the tenant name in their existing portal URL, organizations must contact Customer Support.

Only the prefix of the Brand Portal URL can be customized and not the entire URL.  
For example, an organization with an existing domain **geomettrix.brand-portal.adobe.com** can get **geomettrixinc.brand-portal.adobe.com** created on request.

However, the AEM Author instance can be [configured](https://experienceleague.adobe.com/en/docs/experience-manager-65/content/assets/brandportal/configure-aem-assets-with-brand-portal) only with the tenant ID URL and not with the tenant alias (alternate) URL.

Organizations can meet their branding needs by getting the portal URL customized, instead of sticking to the URL provided by Adobe.

[![](assets/see-the-guide.png)](../using/brand-portal.md#tenantaliasforportalurl)

### Download experience enhancements

The release offers a simplified download experience with a reduced number of clicks and warnings, on:

* Opting to download only the renditions (and not the original assets).
* Downloading the assets when access to the original renditions is restricted.

## What changed in 6.4.2 {#what-changed-in-1}

Brand Portal 6.4.2 introduces features to meet organizations' asset distribution needs, enabling global reach by way of Guest access and faster downloads. It also offers enhanced control with new admin configurations, an added report, and addresses customer requests.

### Guest Access

![](assets/bp-login-screen-1.png)

AEM Brand Portal allows guest access to the portal. A Guest User does not require credentials to enter the portal and can access and download all the public folders and collections. Guest users can add assets to their lightbox (private collection) and download the same. They can also view smart tag search and search predicates set by administrators. The guest session does not allow users to create collections and saved searches or share them further, access folder and collections settings, and share assets as links.

In an organization, multiple concurrent guest sessions are allowed, which is limited to 10% of the total user quota per organization.

A guest session remains active for two hours. Therefore, the state of the lightbox is also preserved until two hours from the session start time. After two hours, the guest session has to restart, so the lightbox state is lost.

### Accelerated downloads

Brand Portal users can apply IBM&reg; Aspera Connect based fast downloads to get speeds up to 25x faster and enjoy a seamless download experience irrespective of their location across the globe. To download the assets faster from Brand Portal or the shared link, users need to select the **Enable Download Acceleration** option in the download dialog box, provided download acceleration is enabled in their organization.

![](assets/donload-assets-dialog-2.png)

To enable IBM&reg; Aspera based accelerated download for the organization, administrators **Enable Download Acceleration** option (which is disabled by default) from [General Settings](brand-portal-general-configuration.md#allow-download-acceleration) in the administrative tools panel.

For prerequisites and troubleshooting steps to download asset files faster from Brand Portal and shared links, see [Guide to accelerate downloads from Brand Portal](../using/accelerated-download.md#main-pars-header).

### User Logins Report

A new report to track User Logins is now introduced. The **User Logins** report can be instrumental in enabling organizations to audit and keep a check on the delegated administrators and other users of Brand Portal.

The report logs display names, email IDs, personas (admin, viewer, editor, guest), groups, last login, activity status, and log in count of each user from Brand Portal 6.4.2 deployment until the time of report generation. Administrators can export the report as .csv. Along with other reports, the User Logins report lets organizations closely monitor user interactions with approved brand resources, ensuring conformance to corporate compliance offices.

![](assets/user-logins-1.png)

### Access to original renditions

Administrators can restrict access to original image files and provide access to low-resolution renditions for download from Brand Portal or shared links. This access can be controlled at user group level from the Groups tab of the User Roles page.

![](assets/access-original-rend-1.png)

* By default, all the users are able to download original renditions as the Access to Original is enabled for all.
* Administrators need to deselect the respective checkboxes to prevent a group of users from accessing the original renditions.
* If a user is the member of multiple groups, but only one of the groups has restrictions, the restrictions apply to that user.
* The restrictions do not apply to administrators, even though they are members of restricted groups.
* Permissions of the user sharing assets as link apply to the users who download assets using shared links.

### Folder hierarchy path on Card and List Views

Cards of folders, in Card View, now display folder hierarchy information to non-admin users (Editor, Viewer, and Guest User). This functionality lets users know the location of the folders they are accessing with respect to the parent hierarchy.

Folder hierarchy information is particularly helpful in differentiating the folders. That is, folder having names similar to other folders shared from a different folder hierarchy. If the non-admin users are not aware of the folder structure of the assets shared with them, assets/folders with similar names seem confusing.

* The paths shown on the respective cards are truncated to fit the card sizes. However, users can see the full path as a tool tip by hovering over the truncated path.

![](assets/folder-hierarchy1-1.png)

List View shows a folder Path of assets in a column to all the users of Brand Portal.

![](assets/list-view-1.png)

### Overview option to view Asset Properties

Brand Portal provides an Overview option to non-admin users (Editors, Viewers, Guest Users) to view Asset Properties of selected assets/folders. The Overview option is visible:

1. In the toolbar, at the top, on selecting an asset/folder.
2. In the drop-down, on selecting the Rail Selector.

On selecting the Overview option, while an asset/folder is selected, users can see the title, path, and time of asset creation. Whereas on the asset detail page, selecting the Overview option lets the users see metadata of the asset.

![](assets/overview-option-2.png) 

![](assets/overview-rail-selector-2.png)

## New configurations

Six new configurations are added for administrators to enable or disable the following functionalities on specific tenants:

* Allow Guest Access
* Allow users to request access to Brand Portal
* Allow administrators to delete assets from Brand Portal
* Allow creation of public collections
* Allow creation of public smart collections
* Allow Download Acceleration

The above configurations are available under the Access and General settings in the administrative tools panel.

![](assets/access-configs-1.png) 
![](assets/general-configs-1.png)
![](assets/admin-tools-panel-13.png)

### `Adobe I/O` UI to configure oAuth integrations

Brand Portal 6.4.2 onwards uses Legacy OAuth (`https://legacy-oauth.cloud.adobe.io/`) interface to create JWT application, which enables configuring oAuth integrations to allow AEM Assets integration with Brand Portal. Previously, the UI for configuring OAuth integrations was hosted in `https://marketing.adobe.com/developer/`. To know more about integrating AEM Assets with Brand Portal for publishing assets and collections to Brand Portal refer [Configure AEM Assets integration with Brand Portal](https://experienceleague.adobe.com/en/docs/experience-manager-65/content/assets/brandportal/configure-aem-assets-with-brand-portal).

## Search Enhancements

Administrators can make the property predicates non-case sensitive by using the updated Property Predicate, which has a check for Ignore Case. This option is available for Property Predicate and multi-value Property Predicate.  
However, the non-case sensitive search is comparatively slower than the default search for Property Predicate. If there are too many non-case sensitive predicates in the search filter, the search can slow down. Adobe recommends you use the non-case sensitive search judiciously.

## What changed in 6.4.1 {#what-changed-in-2}

Brand Portal 6.4.1 is a platform upgrade release. It introduces several new features and vital enhancements such as browsing, searching, and performance enhancements.

### Browse Enhancements

* The new Content Tree rail lets users quickly navigate an asset hierarchy.

![](assets/contenttree-2.png)

* New keyboard shortcuts, for example _(p)_ for navigation to properties page, _(e)_ for Edit, and _(ctrl+c)_ for copy operations.
* Improved scrolling, lazy loading experience in Card and List View for browsing a large number of assets.
* Enhanced Card View with support for different-sized cards based on view setting.

![](assets/cardviewsettings-1.png)

* The Card View now displays a date/time stamp on hovering above the date label.

* Enhanced Column view with **More Details** under the asset snapshot, which lets you navigate to the details page of an asset.

![](assets/columnmoredetail.png)

* The List View now displays file names of assets in the first column by default. It also displays locale, asset type, dimensions, size, rating, and publication information. New **View Settings** can be used to configure the amount of detail to display in the List View.

* Improved asset detail experience with ability to navigate back and forth between assets using new navigation buttons, and view asset count.

![](assets/navbtn.png)

* New capability to preview audio files, uploaded from AEM, in the asset's details page.
* New Related Assets capability provided in Asset Properties. Related assets published on Brand Portal from AEM now maintain their relationships, with links to these related assets available on the properties page.
* A new configuration to restrict non-admin users from creating public collections has been introduced. Organizations can work with the Customer Support team to configure this capability on specific accounts.

### Search enhancements

* Capability introduced to come back to the same position in search results, after navigating to a search item, without running the search query again.
* A new search results count to display the number of search results has been provided.
* The improved File Type Search Filter now lets you filter search results by specific MIME types like .jpg, .png, and .psd, rather than just broad categories like Images, Documents, and Multimedia.
* Enhanced search filters for collections, with accurate time stamps instead of the previous time slider functionality.
* New Access type filters have been introduced to search for the collections that are Public or non-Public.

![](assets/accesstypefilter.png)

### Download optimizations

* A single large file is directly downloaded, without the creation of a zip file, improving speed and throughput.
* The download limit per file size for the link share feature is **1**GB.

* Users can now choose to download only the custom and original files, and prevent out-of-the-box renditions, while downloading assets from Brand Portal or through the shared links feature.

 ![](assets/excludeautorendition.png)

### Performance enhancements

* Up to 100% improvement in assets download speed.
* Up to 40% improvement in search response for assets.
* Up to 40% improvement in browsing performance.

**Note**: Cited improvements are as per the tests conducted in the lab.

### Enhanced reporting capabilities

**Introduced Link Share Report**
A new report, to provide information about shared links, has been introduced. The Link Share report lists all the URLs to the assets shared with internal and external users. It reports for users across the organization in the specified time frame. It also informs when the link was shared, by whom, and when it expires.

![](assets/navigatereport.png)

**Modified the entry point to access the Usage Report**
The Usage Report is now consolidated with other reports and can now be viewed from the Asset Reports console. To reach the Asset Reports console, navigate to **Create/Manage Reports** from the administrative tools panel.

![](assets/accessassetreport.png)

**An improved user experience for reporting**
Reporting interface on Brand Portal has become more intuitive and imparts greater control to organizations. Apart from creating various reports, administrators can now revisit the generated reports and download or delete them, as these reports are saved in Brand Portal.

Each of the reports being created can be customized by adding or removing default columns. Moreover, custom columns can be added to Download, Expiration, and Publish reports to control their degree of granularity.

### Improved Admin tools

Improved Property picker in Admin tools for Metadata, Search, and Reports with Type-ahead and browsing capability to simplify the admin experience.

### Other enhancements

* Assets published to Brand Portal from AEM 6.3.2.1 and 6.4 can now be made publicly available by checking the Public Folder Publish box in the AEM Assets Brand Portal Replication dialog box.

![](assets/public-folder-publish.png)

* Administrators are notified through access request emails, apart from the notifications in the Brand Portal notification area, if someone has requested access to the Brand Portal.

## What changed in 6.3.2 {#what-changed-in-3}

Brand Portal 6.3.2 includes new and enhanced functionality oriented toward top customer requests and general performance enhancements.

### Request access to Brand Portal {#request-access-to-brand-portal}

Users can now request access to Brand Portal using the new **need access** capability available on the login screen of Brand Portal. 

![](assets/bplogin_request_access.png)

Depending on whether users have an Adobe ID or need to create an Adobe ID, users can follow the appropriate workflow to submit a request. Brand Portal product administrators receive such requests in their notification area and grant access through the Adobe Admin Console.

For more information, see [Request access to Brand Portal](../using/brand-portal.md#requestaccesstobrandportal).

### Enhancement in the assets downloaded report {#enhancement-in-the-assets-downloaded-report}

The assets downloaded report now includes the asset download count per user within the specified date and time range. Users can download this report in .csv format to compile data like the total download count for a licensed asset.

![](assets/reports_download_downloaded_by.png)

For more information, see Steps 3 and 6 in [Create and manage additional reports](../using/brand-portal-reports.md#createandmanageadditionalreports).

### Brand Portal maintenance notification {#brand-portal-maintenance-notification}

Brand Portal now displays a notification banner a few days before an upcoming maintenance activity. A sample notification:

![](assets/bp_maintenance_notification-1.png)

For more information, see the [Brand Portal maintenance notification](https://experienceleague.adobe.com/en/docs/experience-manager-brand-portal/using/introduction/brand-portal).

### Enhancement for licensed assets shared using the link share feature {#enhancement-for-licensed-assets-shared-using-the-link-share-feature}

While downloading licensed assets using the link share feature, you are now prompted to agree to the license agreement for those assets. 

![](assets/copyright_management.png)

For more information, see Step 12 in [Share assets as a link](../using/brand-portal-link-share.md#shareassetsasalink).

### User picker enhancement {#user-picker-enhancement}

User picker performance is now enhanced to cater to the needs of customers with a large user base.

### Experience Cloud branding changes {#experience-cloud-branding-changes}

Brand Portal now conforms to the new Adobe Experience Cloud branding.

![](assets/bp_solution_switcher.png) 

## What changed in 6.3.1 {#what-changed-in-4}

Brand Portal 6.3.1 includes new and enhanced functionality oriented toward aligning Brand Portal with AEM.

### Upgraded user interface {#upgraded-user-interface}

To align the Brand Portal user experience with AEM, Adobe is transitioning to Coral 3 user interface. This change enhances the overall usability, including navigation, and appearance.

#### Enhanced navigational experience {#enhanced-navigational-experience}

* Quick access to administrative tools through the new Adobe logo:

![](assets/aemlogo-3.png)

* Product navigation through an overlay:

![](assets/overlay_navigation.png)

* Quick navigation to parent folders:

![](assets/navigationparentfolders.png)

* Quick search and navigation to the required content and tools:

![](assets/omnisearchicon.png) 

### Enhanced browsing experience {#enhanced-browsing-experience}

* New column view to browse through nested folders:

![](assets/millercolumnnavigation.png) ![](assets/multi-columnview.png)

* In the list of assets in a folder, the latest asset uploaded appears at the top.

### Enhanced search experience {#enhanced-search-experience}

* The new Omni search feature facilitates quick access to relevant content, capability, or tags through automatic suggestions as you type search keywords. Omni search is available across all search features.

![](assets/omnisearch_whatsnew.png)

* You can also add search filters to Omni search so you can further narrow down and quicken your search.

![](assets/omnisearch_withfilters.png)

* The new asset rating-based search lets you search for assets with ratings, if published from AEM Assets.
* The new multi-value search feature accepts multiple keywords with the AND operator to discover assets faster.
* The new search boost capability lets you improve the search relevance so that specific assets appear at the top of the search results.
* The new path-based search feature lets you provide the path to a nested folder to be able to search assets in that folder.

#### New smart tags-based search {#new-smart-tags-based-search}

If images with smart tags are published from AEM Assets to Brand Portal, you can search for these images in Brand Portal using the smart tag names as search keywords. This feature is available only for files.

### Enhanced downloading experience {#enhanced-downloading-experience}

After downloading a nested folder, you can preserve the original folder hierarchy. Assets inside a nested folder are downloadable in a single folder as opposed to separate folders.

### Improved performance {#improved-performance}

Enhancements in the browse, search, and download capabilities significantly improve Brand Portal performance.

### New Digital Rights Management for assets {#new-digital-rights-management-for-assets}

Administrators can set the expiry date and time for assets before sharing them. After an asset expires, it is visible to viewers and editors, but not downloadable. When an asset expires, administrators receive a notification.

### Enhanced asset sorting {#enhanced-asset-sorting}

Asset sorting in a folder in List View is no longer restricted to the number of assets being displayed on the first page. All assets in a folder are sorted, irrespective of whether all are listed on the first page.

### Enhanced reporting {#reporting-capabilities}

Administrators can create and manage three types of reports-assets downloaded, expired, and published. The ability to configure the columns in a report, and export the reports to CSV format is also available.

![](assets/newreport.png) 

### Additional metadata {#additional-metadata}

Brand Portal 6.3.1 introduces additional metadata, which is at par with AEM Assets 6.3. You can use the Schema Editor form to control the metadata that should be visible on the Assets Properties page. Asset metadata is not visible to external link share users, who can only preview and download assets using the link share URL. 

![](assets/additionsinmetadata.png) 

### Additional capabilities for administrators {#additional-capabilities-for-administrators}

* Before finalizing customizations to the login screen wallpaper, administrators can preview the changes.

![](assets/wallpaperpreview.png)

* After an administrator adds new users, they are automatically included in Brand Portal without needing to accept any invitations.

### New publishing capabilities in AEM Assets 6.3 {#new-publishing-capabilities-in-aem-assets}

* AEM administrators can publish metadata schema from AEM Assets to Brand Portal using AEM 6.3 SP 1-CFP 1 (6.3.1.1), available in the fourth quarter of 2017.

![](assets/publish_metadataschemaaemassets.png)

* AEM administrators can publish all the tags from AEM Assets to Brand Portal using AEM 6.2 SP1-CFP7 and AEM 6.3 SP 1-CFP 1 (6.3.1.1).

![](assets/publish_tags_aemassets.png)

* From AEM Assets, you can publish assets and collections that have tags, including smart tags. You can then search for these assets or collections using these tags as search keywords in Brand Portal.
