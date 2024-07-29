---
title: Apply image presets or dynamic renditions
description: Like a macro, an image preset is a predefined collection of sizing and formatting commands saved under a name. Image presets enable Experience Manager Assets Brand Portal to deliver images of different sizes, formats, and properties dynamically.
content-type: reference
topic-tags: administration
products: SG_EXPERIENCEMANAGER/Brand_Portal
role: Admin
exl-id: 212a1b3a-686f-4250-be06-b679b6039887
---
# Apply image presets or dynamic renditions {#apply-image-presets-or-dynamic-renditions}

Like a macro, an image preset is a predefined collection of sizing and formatting commands saved under a name. Image presets enable Experience Manager Assets Brand Portal to deliver images of different sizes, formats, and properties dynamically.

An image preset is used to generate dynamic renditions of images that can be previewed and downloaded. When previewing images and their renditions, you can choose a preset to reformat images to the specifications set by your Administrator.

(*If Experience Manager Assets author instance is running in **Dynamic Media Hybrid mode***). To view dynamic renditions of an asset in Brand Portal, ensure that its Pyramid TIFF rendition exists at the Experience Manager Assets author instance from where you publish to Brand Portal. When you publish the asset, its PTIFF rendition is also published to Brand Portal.

>[!NOTE]
>
>When downloading images and their renditions, there is no option to choose from the existing presets. Instead, you can specify the properties of a custom image preset. For more information, see [Apply image presets when downloading images](../using/brand-portal-image-presets.md#main-pars-text-1403412644).


For more information about the parameters required while creating image presets, see [Managing Image Presets](../using/brand-portal-image-presets.md).

## Create an image preset {#create-an-image-preset}

The Experience Manager Assets administrators can create image presets that appear as dynamic renditions on the asset detail page. You can create an image preset from scratch or save an existing one with a new name. When creating an image preset, choose a size for image delivery and the formatting commands. When an image is delivered for viewing, its appearance is optimized according to the chosen commands.

>[!NOTE]
>
>Dynamic renditions of an image are created using its Pyramid TIFF. If the Pyramid TIFF is not available for any asset, dynamic renditions for that asset cannot be fetched in Brand Portal.
>
>If the Experience Manager Assets Author instance is running in **Dynamic Media Hybrid mode**, then Pyramid TIFF renditions of image assets are created and saved in the Experience Manager Assets repository. 
>
>Whereas if Experience Manager Assets author instance is running in **Dynamic Media Scene7 mode**, then Pyramid TIFF renditions of image assets exist on the Scene7 server.
>
>When such assets are published to Brand Portal, image presets are applied and dynamic renditions are displayed.


1. From the toolbar at the top, click the Experience Manager logo to access administrative tools.

1. From the administrative tools panel, click **[!UICONTROL Image Presets]**.

   ![](assets/admin-tools-panel-4.png)

1. In the image presets page, click **[!UICONTROL Create]**.

   ![](assets/image_preset_homepage.png)

1. In the **[!UICONTROL Edit Image Preset]** page, enter values into the **[!UICONTROL Basic]** and **[!UICONTROL Advanced]** tabs as appropriate, including a name. Presets appear in the left pane and can be used on-the-fly with other assets.

   ![](assets/image_preset_create.png)

   >[!NOTE]
   >
   >You can also use the **[!UICONTROL Edit Image Preset]** page to edit the properties of an existing image preset. To edit an image preset, select it from the image presets page, and click **[!UICONTROL Edit]**.

1. Click **[!UICONTROL Save]**. The image preset is created and displayed on the image presets page.
1. To delete an image preset, select it from the image presets page and click **[!UICONTROL Delete]**. In the confirmation page, click **[!UICONTROL Delete]** to confirm the deletion. The image preset is removed from the image presets page.

## Apply image presets when previewing images {#apply-image-presets-when-previewing-images}

When previewing images and their renditions, choose from the existing presets to reformat images to the specifications set by your Administrator.

1. From the Brand Portal interface, click an image to open it.
1. Click the overlay icon on the left, and choose **[!UICONTROL Renditions]**.

   ![](assets/image-preset-previewrenditions.png)

1. From the **[!UICONTROL Renditions]** list, select the appropriate dynamic rendition, for example, **[!UICONTROL Thumbnail]**. The preview image is rendered based on your choice of the rendition.

   ![](assets/image-preset-previewrenditionthumbnail.png)

## Apply image presets when downloading images {#apply-image-presets-when-downloading-images}

When downloading images and their renditions from Brand Portal, you cannot choose from the existing image presets. However, you can customize image preset properties based on which you want to reformat images.

1. From the Brand Portal interface, do one of the following:

    * Hover the pointer over the image that you want to download. From the quick action thumbnails available, click the **[!UICONTROL Download]** icon.

   ![](assets/downloadsingleasset.png)

    * Select the image that you want to download. From the toolbar at the top, click the **[!UICONTROL Download]** icon.

   ![](assets/downloadassets.png)

1. From the **[!UICONTROL Download]** dialog box, select the required options depending upon whether you want to download the asset with or without its renditions.

   ![](assets/donload-assets-dialog.png)

1. To download dynamic renditions of the asset, select the **[!UICONTROL Dynamic Renditions]** option.
1. Customize image preset properties to reformat the image and its renditions dynamically during download. Specify the size, format, color space, resolution, and image modifier.

   ![](assets/dynamicrenditions.png)

1. Click **[!UICONTROL Download]**. The custom dynamic renditions are downloaded in a ZIP file along with the image and renditions that you chose to download. However, no zip file is created if a single asset is downloaded, which ensures a speedy download.
