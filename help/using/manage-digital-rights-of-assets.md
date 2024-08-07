---
title: Manage digital rights of assets
description: Licensing assets and setting expiration for assets and shared links ensure controlled usage of these assets and safeguard them.
contentOwner: bdhar
topic-tags: download-install
products: SG_EXPERIENCEMANAGER/Brand_Portal
content-type: reference
role: Admin
exl-id: 86c31891-0627-41ca-b571-8dac3a074d55
---
# Manage digital rights of assets {#manage-digital-rights-of-assets}

Ensuring secure distribution and usage of creative assets and the brand material is vital to protect your brand. This process can be enforced by associating an expiration date (and time) with approved assets published from AEM to Brand Portal, or by licensing these assets for conditional use. Also, Brand Portal lets you specify an expiration date for links to the assets shared from Brand Portal.

Read on to know how the assets are secured on Brand Portal and understand the associated usage permissions.

## Asset expiration {#asset-expiration}

Asset expiration is an effective way of controlling the usage of approved assets on Brand Portal across an organization. All the assets published from AEM Assets to Brand Portal can have an expiration date, which restricts the usage of these assets by different user roles.

### Usage permissions related to expired assets {#usage-permissions-expired-assets}

In Brand Portal, Administrators can view, download, and add expired assets to collections. However, Editors and Viewers can only view and add expired assets to collections.

Administrators can publish expired assets from AEM Assets to Brand Portal. However, expired assets cannot be shared using a link from Brand Portal. If you select any expired asset from a folder containing both expired and non-expired assets, the **[!UICONTROL Share Link]** action is not available. But, if you select a folder that contains expired and non-expired assets, the [!UICONTROL Share] and **[!UICONTROL Share Link]** actions are available.

>[!NOTE]
>
>A folder can still be shared as a link, even if it contains expired assets. In this case, the link does not list expired assets and only the non-expired assets are shared.

The following table displays the usage permissions of expired assets:

|   |**[!UICONTROL Link share]** |**[!UICONTROL Download]** |**[!UICONTROL Properties]** |**[!UICONTROL Add to collection]** |**[!UICONTROL Delete]** |
|---|---|---|---|---|---|
| **[!UICONTROL Administrator]** |Unavailable |Available |Available |Available |Available |
| **[!UICONTROL Editor]** |Unavailable |Unavailable |Available |Available |Unavailable |
| **[!UICONTROL Viewer]** |Unavailable |Unavailable |Available |Available |Unavailable |
| **[!UICONTROL Guest user]** |Unavailable |Unavailable |Available |Available |Unavailable |

>[!NOTE]
>
>If Viewers and Editors download a folder containing expired and non-expired assets, only the non-expired assets are downloaded. If a folder contains only expired assets, an empty folder is downloaded.

### Expiration status of assets {#expiration-status-of-assets}

You can view the expiration status of assets in their **[!UICONTROL Card View]**. A red flag on the card indicates that the asset has expired.

![](assets/expired_assets_cardview.png)

>[!NOTE]
>
>List and Column views do not display the expiration status of assets.

## Asset Link Expiration {#asset-link-expiration}

While sharing assets through links, Administrators and Editors can set a date and time of expiration using the **[!UICONTROL Expiration]** field in the **[!UICONTROL Link Sharing]** dialog box. The default expiration of a link is seven days from the date on which the link is shared.

![](assets/asset-link-sharing.png)

It ensures that assets shared as links expire at the date and time set by Brand Portal Administrators and Editors. And, the assets can no longer be viewed and downloaded beyond the expiration date. To protect your approved assets from external users, set an expiration date on shared links to ensure they are not exposed to unknown entities beyond a specified time.

For more information about link sharing, refer to [Share assets as a link](../using/brand-portal-link-share.md).

## Licensed Assets {#licensed-assets}

Licensed assets are subject to the acceptance of a license agreement prior to download from Brand Portal. This agreement for licensed assets comes when you directly download the asset from Brand Portal or by way of a shared link. Whether expired or not expired, all the users can view icense-protected assets. However, the download and usage of expired licensed assets are limited. To know about the behavior of expired licensed assets and permissible activities based on user roles, refer to [usage permissions of expired assets](../using/manage-digital-rights-of-assets.md#usage-permissions-expired-assets).

License-protected assets have a [license agreement attached](https://experienceleague.adobe.com/en/docs/experience-manager-65/content/assets/administer/drm) to them, which is done by setting the asset's metadata property in [!DNL Experience Manager Assets]. 

An asset is considered protected if it contains one of the following (or both) metadata properties:

* `xmpRights:WebStatement`: This property refers to the path of the page that contains the license agreement for the asset. `xmpRights:WebStatement` should be a valid path in the repository.  
* `adobe_dam:restrictions`: The value of this property is a raw HTML that specifies the license agreement. 


If you chose to download license-protected assets, you are redirected to the **[!UICONTROL Copyright Management]** page depending upon the metadata properties.

| `adobe_dam:restrictions` | `xmpRights:WebStatement` | Copyright Management |
| --- | --- | --- |
| Yes | - | The interface appears in both, Assets and Brand Portal |
| - | Yes (invalid path) | No interface |
| Yes | Yes (invalid path) | No interface |
| Yes | Yes (valid path) | The interface appears in Assets or Brand Portal</br>Depending on whether the path is valid for Assets or Brand Portal (or both).|

![](assets/asset-copyright-mgmt.png)

Here you need to select the asset to download and accept the associated license agreement. If you do not accept the license agreement, the **[!UICONTROL Download]** button is not enabled.

![](assets/licensed-asset-download-2.png)

If the selection contains multiple protected assets, select one asset at a time, accept the license agreement, and proceed to download the asset.

## Generate report about expired assets {#generate-report-about-expired-assets}

Administrators can generate and download a report listing all the assets expired within a specific time frame. This report includes detailed information— such as size, type, path specifying asset location in the asset hierarchy, when did the asset expire, and when was the asset published— about the expired assets. Columns of this report can be customized to display more data based on user requirements.

![](assets/assets-expired.png)

For more information about the reports feature, go to [Work with reports](../using/brand-portal-reports.md#work-with-reports).
