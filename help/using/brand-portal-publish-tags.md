---
title: Publish tags to Brand Portal
description: Learn how to publish tags from Experience Manager Assets to Brand Portal.
topic-tags: publish
products: SG_EXPERIENCEMANAGER/Brand_Portal
content-type: reference
exl-id: 842656a6-1a2b-4b64-954d-1e663923a1a1
---
# Publish tags to Brand Portal {#publish-tags-to-brand-portal}

Learn how to publish tags from Experience Manager Assets to Brand Portal.

Tags are useful in organizing assets and enhance the searchability of assets to which they are associated. Tags can be thought of as keywords or labels (metadata) that are attached with assets, and allow assets to be quickly found as the result of a search. To know how to assign tags to assets in Experience Manager Assets, refer [use tags to organize assets](https://experienceleague.adobe.com/en/docs/experience-manager-65/content/assets/managing/organize-assets).

Tags (associated with assets and collections in AEM) are auto-published to Brand Portal when the assets (and collections) with associated tags are published to Brand Portal. The published tags are helpful in enabling the searches to find the associated assets.

>[!NOTE]
>
>Adobe recommends that you exclusively publish tags to Brand Portal before publishing the assets (and collections) with which the tags are associated. This approach ensures faster publishing of the assets (and collections) to Brand Portal.

## Manage tags {#manage-tags}

You can use the pre-existing tags to attach to an asset or create new tags from the AEM Tags console (**[!UICONTROL Tools | Tagging | AEM Tags]**). In both the scenarios, you must first publish the tags to Brand Portal and then associate them with appropriate assets.

To create tags on AEM, publish the tags on Brand Portal, and associate the tags with appropriate assets (or collections), follow these steps:

1. **Create Tags**
Sign in to an AEM Author instance with administrative privileges, and access the **[!UICONTROL AEM Tags]** console from global navigation:

   1. Select **[!UICONTROL Tools]**

   1. Select **[!UICONTROL General]**

   1. Select **[!UICONTROL Tagging]**

1. Select **[!UICONTROL Create]** and then select the **[!UICONTROL Create Tag]** option.
1. Specify:

    * **[!UICONTROL Title]**
      *(required)* A display title for the tag.
    * **[!UICONTROL Name]**
      *(required)* A name for the tag. If not specified, a valid node name is created from the Title. See [TagID](https://experienceleague.adobe.com/en/docs/experience-manager-65/content/implementing/developing/platform/tagging/framework).
    * **Description**
      *(optional)* A description of the tag.
    * **Tag Path**
      JCR path of the tag.

1. Select **[!UICONTROL Submit]** to create the tag.

   After you have created a tag on an AEM instance, the tag is available for attachment to an asset (using the Properties section or Manage Tags section of that asset).

1. **Publish the tag to Brand Portal**.

   Go to the **[!UICONTROL AEM Tags]** console ([!UICONTROL Tools | Tagging | AEM Tags]), select the desired tag and Publish to Brand Portal.

1. **Attach the tag to an asset (or collection)**.

   Select an asset (or collection), and attach the desired tag using the Properties section or Manage Tags section of that asset. To know more about how to assign tags to assets in AEM Assets, go to [use tags to organize assets](https://experienceleague.adobe.com/en/docs/experience-manager-65/content/assets/managing/organize-assets).

1. **Publish assets (or collections) to Brand Portal**.  
   When you publish an asset (or collection) to Brand Portal, the attached tag is also available on Brand Portal.

   To see the attached tag on the respective asset (or collection) in Brand Portal, log in to Brand Portal, then select the asset. Under the Properties section, you can see the attached Tag.

## Search Promote {#search-promote}

AEM Assets Brand Portal lets you make specific assets come as the top results for searches based on a keyword tag.

To elevate an asset for a search keyword, follow these steps:

1. Open the **[!UICONTROL Properties]** page of an asset on AEM author instance.
1. Go to the **[!UICONTROL Advanced]** tab.
1. In the **[!UICONTROL Search Promote]** within the **[!UICONTROL Elevate for search keywords]** section, select **[!UICONTROL Add]** to add the search keywords or tags.

   ![](assets/search-promote.png)

1. Save the changes.
1. Publish the asset to Brand Portal.
1. Log in to Brand Portal. View the **[!UICONTROL Advanced]** tab in the **[!UICONTROL Properties]** section of the asset.
Note that the **[!UICONTROL Search Promote]** keyword is also visible in the Properties of that asset.
