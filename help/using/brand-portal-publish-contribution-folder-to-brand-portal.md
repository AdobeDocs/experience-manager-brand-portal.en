---
title: Configure and publish contribution folder from Experience Manager Assets to Brand Portal 
description: Get an insight into configuring and publishing a contribution folder from Experience Manager Assets to Brand Portal.
content-type: reference
contentOwner: Vishabh Gupta
topic-tags: brand-portal
products: SG_EXPERIENCEMANAGER/Brand_Portal
exl-id: 9acad588-977a-45de-b544-f2cc8874ba12
---
# Configure contribution folder in Experience Manager Assets {#configure-contribution-folder}

For collaborative asset sourcing, Experience Manager Assets users (administrators and non-admin users having permission) can create folders of the type **Asset Contribution**, ensuring the folder created is open to asset submission by Brand Portal users.  This method automatically triggers a workflow that creates two additional sub folders, called **SHARED** and **NEW**, within the newly created **Contribution** folder.

The Experience Manager Assets user defines the asset requirements by uploading a brief about the types of assets that should be added to the contribution folder. They also upload a set of baseline assets to the SHARED folder to ensure that users of Brand Portal have the information they need. The administrator can then grant active Brand Portal users access to the contribution folder before publishing the newly created Contribution folder to Brand Portal.

The following video demonstrates how to configure a Contribution folder in Experience Manager Assets:

>[!VIDEO](https://video.tv.adobe.com/v/30547)

Experience Manager Assets user performs the following activities while configuring a contribution folder:

* [Create a contribution folder](#create-contribution-folder)
* [Upload asset requirements and assign contributors](#configure-contribution-folder-properties)
* [Upload baseline assets](#uplad-new-assets-to-contribution-folder)
* [Publish contribution folder from Experience Manager Assets to Brand Portal](#publish-contribution-folder-to-brand-portal)

## Create contribution folder {#create-contribution-folder}

Experience Manager Assets administrators and non-admin users with permission to create a new folder can create a contribution folder in Experience Manager Assets. 
To create a contribution folder, create a folder of type asset contribution, ensuring the folder created is open to asset submission by Brand Portal users. This method automatically triggers a workflow that creates two additional sub folders, called SHARED and NEW, within the contribution folder.

>[!NOTE]
>
>The administrators can create multiple asset contribution folders within a folder. 
>
>An asset contribution folder contains NEW and SHARED folders for the distribution and contribution of the assets. Do not create an asset folder, or contribution folder within a contribution folder.   


You can configure the contribution folder properties separately as well as while creating the contribution folder. In this example, the properties are configured separately.

**To create a contribution folder:**

1. Log in to your Experience Manager Assets instance.

1. Navigate to **[!UICONTROL Assets]** > **[!UICONTROL Files]**. It lists all the existing folders in the Experience Manager Assets repository.

1. Click **[!UICONTROL Create]** to create a new folder. **[!UICONTROL Create Folder]** dialog opens.

1. Enter the **[!UICONTROL Title]** and **[!UICONTROL Name]** of the folder and select the **[!UICONTROL Asset Contribution]** check box.
Adobe recommends that you use lowercase letters without any space to name the folder.

1. Click **[!UICONTROL Create]**. You can see the contribution folder listed in the Experience Manager Assets repository.

   >[!NOTE]
   >
   >A non-admin user can create and share an asset contribution folder but cannot modify or delete it.  


   ![](assets/create-contribution-folder.png)

1. Open the contribution folder. You can see two sub folders&ndash;**[!UICONTROL SHARED]** and **[!UICONTROL NEW]**&ndash;that are automatically created within the contribution folder. 
  
   ![](assets/contribution-folder.png)


## Configure contribution folder properties {#configure-contribution-folder-properties}

Experience Manager Assets administrator performs the following activities while configuring the properties of a contribution folder.

* **Add description**: Provide a high-level description of the contribution folder.
* **Upload brief**: Upload an asset requirement document containing asset related information.
* **Add contributors**: Add Brand Portal users to grant them access to the contribution folder.

Asset requirement refers to the details provided by administrators to help contributors (Brand Portal users) understand the need and requirements of the contribution folder. The administrator uploads an asset requirement document detailing the types of assets for the contribution folder, including purpose, image types, and maximum size.

**To configure contribution folder properties:**

1. Log in to your Experience Manager Assets instance. 

1. Navigate to **[!UICONTROL Assets > Files]** and locate the contribution folder.
1. Select contribution folder and click **[!UICONTROL Properties]** to open the Folder properties window.

   ![](assets/properties.png)

   ![](assets/contribution-folder-property1.png)

1. Navigate to the **[!UICONTROL Asset Contribution]** tab.
1. Enter a high-level **[!UICONTROL Description]** of the contribution folder.
1. Click **[!UICONTROL Upload Brief]** to browse from your local machine and upload an **Asset Requirement Document**.

   ![](assets/upload.png) 

1. In the **[!UICONTROL Add User]** field, add Brand Portal users with whom you want to share the contribution folder. These users can access and upload content to the contribution folder using the Brand Portal interface.
1. Click **[!UICONTROL Save]**.

   ![](assets/contribution-folder-property3.png)

>[!NOTE]
>
>The search results are based on the Brand Portal user list configured in Experience Manager Assets. Ensure that you have the updated Brand Portal user list. 

The administrators can download the `user.csv` file from [!DNL Admin Console] and use it as the base template for adding Brand Portal users. Go to [!UICONTROL Users] and click on the [!UICONTROL Export users list to csv] option to download the `users.csv` file. The following sample users list details the attributes required for adding the users. The only mandatory attribute for a user entry is the `Email` and all the other attributes are optional. 

[Get File](assets/users.csv)

## Upload assets to contribution folder {#uplad-new-assets-to-contribution-folder}

Experience Manager Assets user uploads a set of baseline assets to the **SHARED** folder to ensure that users of Brand Portal have the information they need. 

**To upload baseline assets:**

1. Log in to your Experience Manager Assets instance. 

1. Navigate to **[!UICONTROL Assets > Files]** and locate the contribution folder.

1. Select the contribution folder and click to open it. 

1. Click on the **[!UICONTROL NEW]** folder.

   ![](assets/upload-new-assets1.png)

1. Click **[!UICONTROL Create]** > **[!UICONTROL Files]** to upload individual files or folder (.zip) containing multiple assets.

   ![](assets/upload-new-assets2.png)

1. Browse and upload assets (files or folders) to the **[!UICONTROL NEW]** folder.

   ![](assets/upload-asset4.png)

After uploading all the assets or folders to the NEW folder, publish the contribution folder to Experience Manager Assets. 


## Publish contribution folder to Brand Portal {#publish-contribution-folder-to-brand-portal}

Once the contribution folder is configured, Experience Manager Assets user (administrator/non-admin user) can publish the contribution folder from Experience Manager Assets to Brand Portal. Brand Portal users that have permission to access the contribution folder, receive an email or pulse notification at the completion of the publish action.


**To publish a contribution folder:**

1. Log in to your Experience Manager Assets instance. 

1. Navigate to **[!UICONTROL Assets > Files]** and locate the contribution folder in which you want to publish to Brand Portal.
1. Select a contribution folder and click **[!UICONTROL Quick Publish]** > **[!UICONTROL Publish to Brand Portal]**.

   ![](assets/publish-contribution-folder-to-bp.png)
      
   You receive a success message after the contribution folder is published to Brand Portal.

An email/pulse notification is sent to the Brand Portal users assigned to the contribution folder. The Brand Portal users can access the contribution folder and begin a contribution. See, [Upload assets to the contribution folder and publish to Experience Manager Assets](brand-portal-publish-contribution-folder-to-aem-assets.md).
