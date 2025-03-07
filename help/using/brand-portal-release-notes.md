---
title: Release Notes
description: Get an insight into the features, enhancements, critical issues fixed, and known issues in the Adobe Experience Manager Assets Brand Portal 2024.10.0 release.
content-type: reference
contentOwner: Kirandeep Kour
topic-tags: brand-portal
products: SG_EXPERIENCEMANAGER/Brand_Portal
exl-id: e4e89080-9863-4857-8f3a-fcd516ef3271
---
# Release Notes {#release-notes}

Get an insight into the new features, enhancements, critical issues fixed, and known issues in the Adobe Experience Manager Assets Brand Portal 2024.10.0 release.

## Release Information {#release-information}

| Product |Adobe Experience Manager Assets Brand Portal |
|---|---|
| Version | 2024.10.0|
| Date | October 2024 |

## Overview {#overview}

Adobe Experience Manager (AEM) Assets Brand Portal helps you easily acquire, control, and securely distribute approved creative assets to external parties and internal business users across devices. It helps improve the efficiency of asset sharing, accelerates the time to market for assets, and reduces the risk of non-compliance and unauthorized access. Brand Portal allows users to browse, search, preview, download, and export assets in corporate-approved formats-anytime, anywhere.

## What's New in 2024.10.0 {#whats-new-in-2024.10.0}

### Critical Issues Fixed {#critical-issues-fixed}

#### Bug fixes {#bug-fixes}

This release includes the following bug fixes:

* The email notifications for sourcing import events are not being sent.
* While using the search filter, [!DNL Brand Portal] displays duplicate folders within search Filter window.
* The download of collections containing non-licensed assets with special characters in their names is not working.
* While navigating to [!UICONTROL Search Form Editor], labels are not localized.
* Labels are not localized in the link sharing window.
* Unable to download video with special characters in its name.
* Publishing and unpublishing the assets from [!DNL Adobe Experience Manager Assets] to Brand Portal is not working appropriately.
* Unable to play videos downloaded from the Brand Portal.

## Previous releases

### February 2024 release {#feb-2024}

**Bug fixes and enhancements**

This release includes the following bug fixes:

* Unable to download digital assets protected by DRM in the Turkish locale.
* Unable to open and download the existing reports containing assets with multi-line title.
* When you download assets using the [!UICONTROL Download] button from the action bar, a maximum of 1000 assets are downloaded.
* Incorrect name of PSD type assets, when viewing in the content tree.
* [!UICONTROL Delete Rendition] option on the asset details page is not working.
* Misaligned title and size of assets in download pop-up window.
* While creating a report, labels are not localized.
* Support administrators were termed as administrators in Brand Portal.

### October 2023 release {#oct-2023}

**Bug fixes and enhancements**
This release includes the following enhancements:

* Performance improvements while browsing through [!UICONTROL Collections].

* Improvements in search results while performing a partial search using the OmniSearch field.

This release includes the following bug fixes:

* Unable to save [!UICONTROL Date] and [!UICONTROL Options] predicates to the [!UICONTROL Smart Collection].

* The [!UICONTROL Date and Time] format is inconsistent while working in locale other than English.

* While performing a search for assets, the [!UICONTROL Delete] button is missing.

* If the [!UICONTROL Title] field contains multibyte symbols in [!UICONTROL Link Share], the report cannot be downloaded.

* While viewing a PDF-type document, the labels and tool tips are not localized.

### August 2023 release {#aug-2023}

**Bug fixes and enhancements**
This release includes the following enhancements:

* Performance improvements while loading assets on the [!UICONTROL Download] pop up.
* When you download an asset or a rendition of an asset, it is now downloaded in its original file type format instead of a zip file.

This release includes the following bug fixes:

* The long labels or tags do not display appropriately for search filters. 
* Unable to display long rendition names in the Download dialog box.
* Unable to preview video assets in Card view.

### May 2023 release {#may-2023}

**Bug Fixes**
This release includes fixes to the following critical issues:

* If an error occurs while downloading an Asset from a shared link, the `Notice` and `Close` labels of the error prompt are not localized.
* Brand Portal displays **Request Header fields Too Large** error while accessing search filters using `Filter` pane.

**Known issues**
This release includes the following known issues:

* Partial localization in Asset sourcing report content.
* Few fields of the user profile are not editable on the user profile.

### February 2023 release {#feb-2023}

**Bug Fixes**

This release includes fixes to the following critical issues:

* Profile picture cannot be updated on the Brand Portal.
* The content tree pane is not resizable. If the file name is longer than the default width of the content tree, you cannot drag the content tree both horizontally and vertically. As a result, longer file names are not readable.
* The search results are inconsistent for the same property predicate used twice in the search forms.
* The text on the intermediate login pages is not localized for all languages.
    
**Enhancements**

This release includes the following enhancements:

* A new modern PDF viewer is now available for an improved preview of the PDF assets.
* You can now choose to enable or disable asset sourcing notifications for Administrators. Navigate to [!UICONTROL General Settings] and then enable or disable [!UICONTROL `Notify Administrator of asset contribution`].

    ![Notify Administrator for asset contribution](assets/notify-admin.png)

* An unauthorized user cannot request access to the Brand Portal if the request access is disabled.
* The organizations only that are provisioned for Brand Portal are visible on the profile picker list.

**Known Issues**

This release includes the following known issues:

* Partial localization in Asset sourcing report content.
* Few fields of the user profile are not editable on the user profile.

### October 2022 release {#oct-2022}

**Critical Issues Fixed**

This release includes fixes to the following critical issues:

* Slow response times while copying large files from Brand Portal to a third-party tool.
* When you select the renditions count checkbox, the checkboxes to select individual renditions are disabled.
* Slow response time for search.

>[!IMPORTANT]
>
>Pulse notifications in the AEM Assets Brand Portal is going to discontinue from December 1, 2022. Instead of Pulse notifications, you continue receiving email notifications for the following events: 
>
>* Sharing assets by way of link
>* Requesting access workflow
>* Sharing of contribution folder
>* Initiating export to AEM
>* Completed exporting to AEM
>

### August 2022 release {#aug-2022}

**Critical Issues Fixed**

This release includes fixes to the following critical issues:

* When NUI fails to process an asset in Experience Manager, Brand Portal displays an inaccurate asset import status.
* When the preview action fails, there is no notification to communicate the failure.
* The inaccurate value for the `totalUploadedSize` property for each asset is fixed.
* When you click **Download all items** and there are a large number of renditions available for an asset, Brand Portal downloads an invalid .ZIP file.
* The translation of some strings gets truncated on the Brand Portal user interface.

### May 2022 release {#may-2022}

**New features**

Brand Portal now executes automatic jobs every twelve hours to delete all Brand Portal assets that are published to AEM. As a result, you do not need to delete the assets in the Contribution folder manually to keep the folder size below the threshold limit.

**Critical Issues Fixed**

This release includes fixes to the following critical issues:

* When you download a folder or a collection that includes assets with color tags, an XML file gets downloaded as well.
* When you download a video that includes renditions, Brand Portal creates an invalid .ZIP file.
* When you create presets and assets on AEM author, then you publish them to Brand Portal, you can select dynamic renditions while downloading the assets. However, you cannot extract the downloaded .ZIP file. This issue prevents access to the downloaded content.
* Issues while downloading video assets from certain folders available on Brand Portal.
* When you share the Contribution folder's URL using an email, Viewer and Editor roles face issues while accessing its parent folder using the breadcrumb.
* Sourcing published report displays an incorrect job start time.

### February 2022 release {#feb-2022}

**New features**

* The threshold of session timeout for the guest users has been reduced from 2 hours to 15 minutes.
* The additional **[!UICONTROL View pages]** option has been removed for multi-page PDFs as the user can now view the PDF pages from the Adobe Document Cloud Viewer.
* The users are unable to search, navigate, or open folders. The user interface reflects the error message: `Failed to load data`. 
* The **[!UICONTROL Renditions]** panel does not list all the static renditions of the assets that are published to Brand Portal.
* The **[!UICONTROL Renditions]** panel lists the smart crop renditions of the asset, however, the user cannot preview or download the smart crop renditions.
* The download dialog lists the smart crop renditions of the selected asset, however, the user cannot download the smart crop renditions. 
* A non-admin user is getting only the original asset rendition when downloading an asset. The system and custom renditions are not downloaded.  
* When applying search filter to download an asset, the `Download` button is disabled in the download dialog and does not allows the user to download the asset.
* If `Smart Tags` and (or) `Color Tags` are enabled, the download dialog lists the `json` files as renditions and downloads these `json` files in the archived zip folder.
* The anonymous users are unable to download assets using a shared link because the link redirects to the Brand Portal login page. 
* The system is not reflecting the correct value for the number of active concurrent users.

<!--
### New Features {#new-features}

This release includes the following new features:

* AEM Assets as a Cloud Service is now entitled to have a pre-configured Brand Portal instance. The Cloud Manager user can activate Brand Portal on the AEM Assets as a Cloud Service instance.

* Asset Sourcing feature is now available on AEM Assets as a Cloud Service. It allows the Brand Portal users to upload assets to the permitted contribution folders and publish the contribution folder from Brand Portal to AEM Assets as a Cloud Service instance. 

* An additional **[!UICONTROL Asset Download]** setting has been introduced under the **[!UICONTROL Download Settings]**. It creates a separate folder for each asset while downloading the folders, collections, or bulk download of assets. 
-->
<!-- 
* The **[!UICONTROL Download]** dialog is revamped in a list view with additional options to exclude the renditions which are not required, apply the same set of rules for similar asset types, and download the selected asset renditions.
-->

<!--
* The new **[!UICONTROL Download]** dialog now appears with all the renditions of the selected assets or folders containing assets in a list view, wherein the Brand Portal users can apply same set of renditions for similar asset types and download the selected asset renditions. 
-->

<!-- 
* Navigation to the **[!UICONTROL Files]**, **[!UICONTROL Collections]**, and **[!UICONTROL Shared Links]** is now possible from all the Brand Portal pages in one-click.  

* The **[!UICONTROL Renditions]** panel in the asset details page now allows the Brand Portal users to select the original asset and (or) specific asset renditions, and directly download them from the **[!UICONTROL Renditions]** panel without having to open the **[!UICONTROL Download]** dialog.
-->

<!--
Brand Portal users can exclude specific renditions which are not required and directly download the original asset and its renditions from the **[!UICONTROL Renditions]** panel on the asset details page. 
-->

<!-- 
* In addition to the existing **[!UICONTROL Download]** configurations, the Brand Portal administrators can also [configure permissions for different group of users]() to view and (or) download the original asset and its renditions from the asset details page. These configurations will define who can access and (or) download the asset renditions.
-->

<!--
### Enhancements {#enhancements}

Brand Portal 2021.08.0 is an internal release that introduces Business profiles for enterprise and teams customers to give organizations better control over their assets. 

This release includes the following enhancements:

* The users now have organization-specific entitlement on the new and migrated organizations. If a user is entitled to multiple organizations, the user has to select the organization at the time of login.

* The new users that are added in Admin Console must **Join Team** to get entitled to the organization. 

>[!NOTE]
>
>Business profiles are currently applicable for the new organizations that are created after August 16, 2021. 
>
>Until your organization is migrated, you can continue to use Adobe ID, Enterprise ID, or Federated ID types to access the organization.   
-->

<!-- 
* For folder download, a separate folder is created for each asset using share link irrespective of the **[!UICONTROL Download Settings]**. 
* The Brand Portal **[!UICONTROL Usage Report]** has been modified to reflect only the active Brand Portal users.
-->

<!--
* The threshold of session timeout for the guest users has been reduced from 2 hours to 15 minutes.
* The additional **[!UICONTROL View pages]** option has been removed for multi-page PDFs as the user can now view the PDF pages from the Adobe Document Cloud Viewer.

* The users are unable to search, navigate, or open folders. The user interface reflects the error message: `Failed to load data`. 
* The **[!UICONTROL Renditions]** panel does not list all the static renditions of the assets that are published to Brand Portal.
* The **[!UICONTROL Renditions]** panel lists the smart crop renditions of the asset, however, the user cannot preview or download the smart crop renditions.
* The download dialog lists the smart crop renditions of the selected asset, however, the user cannot download the smart crop renditions. 
* A non-admin user is getting only the original asset rendition when downloading an asset. The system and custom renditions are not downloaded.  
* When applying search filter to download an asset, the `Download` button is disabled in the download dialog and does not allows the user to download the asset.
* If `Smart Tags` and (or) `Color Tags` are enabled, the download dialog lists the `json` files as renditions and downloads these `json` files in the archived zip folder.
* The anonymous users are unable to download assets using a shared link because the link redirects to the Brand Portal login page. 
* The system is not reflecting the correct value for the number of active concurrent users.
-->

<!--
### New features {#new-features}

Brand Portal now executes automatic jobs every twelve hours to delete all Brand Portal assets that are published to AEM. As a result, you do not need to delete the assets in the Contribution folder manually to keep the folder size below the threshold limit. See [What's new in Experience Manager Assets Brand Portal](whats-new.md).
--> 

<!--
This release includes fixes to the following critical issues:

* When you download a folder or a collection that includes assets with color tags, an XML file gets downloaded as well.

* When you download a video that includes renditions, Brand Portal creates an invalid .ZIP file.

* When you create presets and assets on AEM author and publish them to Brand Portal and then select dynamic renditions while downloading the assets, you cannot extract the downloaded .ZIP file.

* Issues while downloading video assets from certain folders available on Brand Portal.

* When you share the Contribution folder's URL using an email, Viewer and Editor roles face issues while accessing its parent folder using the breadcrumb.

* Sourcing published report displays an incorrect job start time.
>
 
<!--
* Asset Sourcing email notifications are not delivered for some organizations. 

* Video files with extension `.mov` are not running on Brand Portal. 

* In the **[!UICONTROL Smart Collections]** dropdown list, only ten saved collections are visible. 
-->
<!--
* *_deleted tenants are listed as valid tenant which fails during the execution of TenantCustomizers/TenantUpdates where tenant id is returned as /etc/tenants/`<nodename>`.
-->

<!--
In case only the original assets are downloaded, the asset reflects its own extension and does not open until the extension is manually changed to zip. 
* The user interface of the collection folder does not respond on clicking the navigation arrow. 
* **[!UICONTROL Create]** button is visible in the **[!UICONTROL Column]** view even when the folders are empty.
* **[!UICONTROL Omni search]** fails with a 414 error message (Request-URI Too Long) if the dispatcher is bypassed while accessing the Brand Portal instance.
* An empty zip folder is downloaded if the asset contains a comma (`,`) in the file name.
* The viewer users get the option to add users to the collection they have created. 
* Inconsistent behavior is experienced when an asset (thumbnail or web rendition) is downloaded using share link.

See [what's new in Brand Portal 2021.02.0](whats-new.md).
-->

<!--
### Known Issues {#known-issues}

This release includes the following known issue:

* Search on the **[!UICONTROL Asset Reports]** shows processing on the product interface with no search result.
* The video DM encodes are not visible to the non-admin users on the asset details page.
* The alignment of the size of individual asset renditions and total download size is distorted in the Download dialog.
-->


<!--
* Download Settings configuration to configure asset download from Brand Portal. Fast download, custom renditions, and system renditions are the available configurations. 
-->

<!--
* Document Viewer has been introduced to enhance the PDF viewing experience. New options are available for viewing the PDF files in Brand Portal.

* Advances in the asset download process which improves the Brand Portal user experience while [downloading assets from Brand Portal](brand-portal-download-assets.md). Brand Portal administrators can configure **[!UICONTROL Fast Download]**, **[!UICONTROL Custom Renditions]**, and **[!UICONTROL System Renditions]** from the **[!UICONTROL Download]** settings. 

For details, see [what's new in Brand Portal 6.4.7](whats-new.md). 

### Critical Issues Fixed {#critical-issues-fixed-647}

This release includes fixes to the following critical issues:

* The viewer users are not permitted to share link for collections but the option to share is visible to them on the product interface.

* The **[!UICONTROL Download]** button on the options bar does not list all the licensed assets of the selected folder.

* The search takes longer to show the results for certain keywords.

* The **[!UICONTROL Agree]** and **[!UICONTROL Disagree]** check boxes does not appear on bulk selection of licensed and unlicensed assets during download.

* Filter-based search shows processing on the product interface with no search result. 

* The assets do not download from share link if the shared folder contains numerous and large assets.


### Known Issues {#known-issues-647}

This release includes the following known issues:

* If multiple assets are selected, license text does not appear on clicking Terms and Conditions on the license agreement page during download using share link.   

-->

## Languages {#languages}

The Brand Portal user interface is available in the following languages:

* English
* German
* French
* Spanish
* Italian
* Brazilian Portuguese
* Japanese
* Simplified Chinese
* Korean

## Certified Platforms {#certified-platforms}

To see which platforms are certified for this Brand Portal release, check the **Support for Touch-optimized UI** column in the **Supported Browsers for Authoring User Interface** section of [Technical Requirements](https://experienceleague.adobe.com/en/docs/experience-manager-65/content/implementing/deploying/introduction/technical-requirements).

## Links {#links}

* [Adobe Experience Manager Product Page on adobe.com](https://business.adobe.com/in/products/experience-manager/adobe-experience-manager.html)
* [Assets Brand Portal Documentation](https://experienceleague.adobe.com/en/docs/experience-manager-brand-portal/using/home)

## Product Access and Support (Restricted Sites) {#product-access-and-support-restricted-sites}

These sites are only available to customers. If you are a customer and require access, contact your Adobe account manager.

<!--
* [https://daycare.day.com](https://daycare.day.com) 
-->

<!--
* [Customer Support]()
-->
