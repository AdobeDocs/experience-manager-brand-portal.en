---
title: Publish presets, schema, and facets to Brand Portal
description: Learn how to publish presets, schema, and facets to Brand Portal.
topic-tags: publish
products: SG_EXPERIENCEMANAGER/Brand_Portal
content-type: reference
exl-id: 9b585606-6538-459b-87a9-2e68df0087b3
---
# Publish presets, schema, and facets to Brand Portal {#publish-presets-schema-and-facets-to-brand-portal}

The article delves into publishing image presets, metadata schemas, and custom search facets from AEM Author instance to Brand Portal. Publishing capability allows organizations to reuse the image presets, metadata schemas, and search facets created or edited on an AEM Author instance. This approach reduces duplicate efforts.

>[!NOTE]
>
>The capability to publish image presets, metadata schema, and search facets from AEM Author instance to Brand Portal is available from AEM 6.2 SP1-CFP7 and AEM 6.3 SP 1-CFP 1 (6.3.1.1) onwards.

## Publish image presets to Brand Portal {#publish-image-presets-to-brand-portal}

Image presets are a set of sizing and formatting commands that are applied to the image at the time of image delivery. Image presets can be created and modified at Brand Portal. Alternatively, if an AEM Author instance is running in Dynamic Media mode, users can create presets in AEM Author and publish them to AEM Assets Brand Portal. This approach avoids re-creating the same presets at Brand Portal.
After the preset is created, it is listed as a dynamic rendition on the asset detail renditions rail and download dialog box.

>[!NOTE]
>
>If the AEM Author instance is not running in **[!UICONTROL Dynamic Media Mode]** (the customer has not purchased Dynamic Media), then the **[!UICONTROL Pyramid TIFF]** rendition of the assets are not created at the time of upload. Image presets or dynamic renditions work on **[!UICONTROL Pyramid TIFF]** of an asset. Therefore, if **[!UICONTROL Pyramid TIFF]** is unavailable on AEM Author instance, it is unavailable on Brand Portal. As a result, no dynamic renditions are present in renditions rail of the asset details page and download dialog box.

To publish image presets to Brand Portal:

1. In AEM Author instance, click the AEM logo to access the global navigation console and click the Tools icon and navigate to **[!UICONTROL Assets > Image Presets]**.
1. Select the image preset or multiple image presets from the list of image presets and click **[!UICONTROL Publish to Brand Portal]**.

![](assets/publishpreset.png)

>[!NOTE]
>
>When users click **[!UICONTROL Publish to Brand Portal]**, the image presets are queued for publishing. Users are advised to monitor the log of the replication agents to confirm if the publish was successful.

To unpublish an image preset from Brand Portal:

1. In AEM Author instance, click the AEM logo to access the global navigation console and click the **[!UICONTROL Tools]** icon and navigate to **[!UICONTROL Assets > Image Presets]**.
1. Select an image preset, and select **[!UICONTROL Remove from Brand Portal]** from the options available at the top.

## Publish metadata schema to Brand Portal {#publish-metadata-schema-to-brand-portal}

Metadata schema describes the layout and properties that are displayed on the properties page of asset/ collections.

![](assets/metadata-schema-editor.png) ![](assets/asset-properties-1.png)

If users edited the default schema on an AEM Author instance and they want to use the same schema as the default schema on the Brand Portal, publish the metadata schema forms to Brand Portal. In such a scenario, the default schemas published from the AEM Author instance override the default schema at Brand Portal.

If users have created a custom schema on AEM Author instance, they can publish the custom schema to Brand Portal instead of re-creating the same custom schema there. Users can then apply this custom schema to any folder/ collection in Brand Portal.

>[!NOTE]
>
>Default schemas cannot be published to the Brand Portal if they were locked at the AEM instance. That is, they are not edited.

![](assets/default-schema-form.png)

>[!NOTE]
>
>If a folder has a schema applied on AEM Author instance, the same schema must also exist on the Brand Portal. Doing so helps to maintain the consistency in the asset properties page on AEM Author and Brand Portal.

To publish a metadata schema from AEM Author instance to Brand Portal:

1. In AEM Author instance, click the AEM logo to access the global navigation console and click the Tools icon and navigate to **[!UICONTROL Assets > Metadata Schemas]**.
1. Select a metadata schema, and select **[!UICONTROL Publish to Brand Portal]** from the options available at the top.

>[!NOTE]
>
>When users click **[!UICONTROL Publish to Brand Portal]**, the metadata schemas are queued for publishing. Users are advised to monitor the log of the replication agents to confirm if the publish was successful.

To unpublish a metadata schema from Brand Portal:

1. In AEM Author instance, click the AEM logo to access the global navigation console and click the Tools icon and navigate to **[!UICONTROL Assets > Metadata Schemas]**.
1. Select a metadata schema, and select **[!UICONTROL Remove from Brand Portal]** from the options available at the top.

## Publish search facets to Brand Portal {#publish-search-facets-to-brand-portal}

Search forms provide the capability of [faceted search](../using/brand-portal-search-facets.md) to users on Brand Portal. Search facets impart greater granularity to searches on Brand Portal. All the [predicates added](https://experienceleague.adobe.com/en/docs/experience-manager-65/content/assets/administer/search-facets) in the search form are available to users as search facets in search filters.

![](assets/property-predicate-removed.png)
![](assets/search-form.png)

To use a custom search form on **[!UICONTROL Assets Admin Search Rail]** from AEM Author instance, publish it directly to Brand Portal instead of re-creating it.

>[!NOTE]
>
>To publish a locked search form on **[!UICONTROL Assets Admin Search Rail]** from AEM Assets to Brand Portal, you must first edit it. Once edited and published, this search form overrides the existing search form on Brand Portal.

To publish the edited search facet from AEM Author instance to Brand Portal:

1. Click the AEM logo, and then go to **[!UICONTROL Tools > General > Search Forms]**.
1. Select the edited search form, and select **[!UICONTROL Publish to Brand Portal]**.

   >[!NOTE]
   >
   >When users click **[!UICONTROL Publish to Brand Portal]**, the search facets are queued for publishing. Users are advised to monitor the log of the replication agents to confirm if the publish was successful.

To unpublish search forms from Brand Portal:

1. In AEM Author instance, click the AEM logo to access the global navigation console and click the Tools icon and navigate to **[!UICONTROL General > Search Forms]**.
1. Select the search form, and select **[!UICONTROL Remove from Brand Portal]** from the options available at the top.

>[!NOTE]
>
>The **[!UICONTROL Unpublish from Brand Portal]** action leaves the default search form on Brand Portal, and does not restore to the last search form used before publishing.

### Limitations {#limitations}

1. Few search predicates are not applicable to search filters on the Brand Portal. When these search predicates are published as part of the search form from AEM Author instance to Brand Portal, they are filtered out. Users, therefore, see less number of predicates in the published form at the Brand Portal. See [search predicates applicable to filters on Brand Portal](../using/brand-portal-search-facets.md#list-of-search-predicates).

1. For [!UICONTROL Options Predicate], if a user is using any custom path to read options on an AEM Author instance, it does not work on Brand Portal. These additional paths and options are not published to Brand Portal with the search form. In this case, users can select the **[!UICONTROL Manual]** option in **[!UICONTROL Add Options]** within **[!UICONTROL Options Predicate]** to add these options manually at Brand Portal.

![](assets/options-predicate-manual.png)
