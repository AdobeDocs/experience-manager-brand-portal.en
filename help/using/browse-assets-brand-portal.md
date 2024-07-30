---
title: Browse assets on Brand Portal
description: Browse through assets, traverse asset hierarchies, and search assets, using different view options and UI elements on Brand Portal.
products: SG_EXPERIENCEMANAGER/Brand_Portal
content-type: reference
topic-tags: introduction
exl-id: 405d7861-a140-44b1-ae1f-4f0839f05033
---
# Browse assets on Brand Portal {#browsing-assets-on-brand-portal}

Experience Manager Assets Brand Portal offers various features and user interface elements that make it easy to browse resources, navigate asset hierarchies, and search for assets using different view options.

The Experience Manager logo in the toolbar at the top facilitates admin users to access the administrative tools panel.

![](assets/aemlogo.png)

![](assets/admin-tools-panel-2.png)

![](assets/bp_subheader.png)

The rail selector at the upper left in Brand Portal drops-down to expose options to navigate into asset hierarchies, streamline your search, and display resources.

![](assets/siderail-1.png)

You can view, navigate, and select assets using any of the available views (Card, Column, and List) in the view selector of Brand Portal.

![](assets/viewselector.png)

## Viewing and Selecting Resources {#viewing-and-selecting-resources}

Viewing, navigating, and selecting each are conceptually the same across all views, but have small variations in handling, depending on the view you are using.

You can view, navigate through, and select (for further action) your resources with any of the available views:

* Column View
* Card View
* List View

### Card View

![](assets/card-view.png)

Card view displays information cards for each item at the current level. These cards provide the following details:

* A visual representation of the asset/folder.
* Type
* Title
* Name
* Date and time when the asset was published to Brand Portal from AEM
* Size
* Dimensions

You can navigate down the hierarchy by clicking cards (taking care to avoid the quick actions) or up again by using the [breadcrumbs in the header](https://experienceleague.adobe.com/en/docs/experience-manager-65/content/sites/authoring/essentials/basic-handling).

![](assets/cardquickactions.png)

#### Card view for non-admin users

Cards of folders, in Card View, display folder hierarchy information to non-admin users (Editor, Viewer, and Guest User). This functionality lets the users know the location of the folders that they are accessing, with respect to the parent hierarchy.

Folder hierarchy information is particularly helpful in differentiating the folders that have names similar to other folders shared from a different folder hierarchy. If the non-admin users are not aware of the folder structure of the assets shared with them, assets/folders with similar names seem confusing.

* The paths shown on the respective cards are truncated to fit the card sizes. However, users can see the full path as a tool-tip by hovering over the truncated path.

![](assets/folder-hierarchy1.png)

**Overview option to view Asset Properties**

Overview option is available to non-admin users (Editors, Viewers, Guest users) to view asset properties of selected assets/folders. The Overview option is visible:

* In the toolbar, at the top, on selecting an asset/folder.
* In the drop-down, on selecting the rail selector.

When selecting the **[!UICONTROL Overview]** option while an asset/folder is selected, users can see the title, path, and time of asset creation. Whereas on the asset detail page, selecting the Overview option lets the users see metadata of the asset.

![](assets/overview-option.png)

![](assets/overview-rail-selector.png)

#### View settings in card view

The **[!UICONTROL View Settings]** dialog box opens by selecting **[!UICONTROL View Settings]** from the view selector. It enables you to resize the asset thumbnails in the Card View. This way, you can personalize your view and control the number of thumbnails that are displayed.

![](assets/cardviewsettings.png)

### List View

![](assets/list-view.png)

The list view displays information for each resource at the current level. The List view provides the following details:

* Thumbnail image of assets
* Name
* Title
* Locale
* Type
* Dimension
* Size
* Rating
* Folder path showing asset hierarchy
* Date of publishing the asset on Brand Portal

The path column lets you easily identify asset location in the folder hierarchy. You can navigate down the hierarchy by clicking the resource name, and back up by using the [breadcrumbs in the header](https://experienceleague.adobe.com/en/docs/experience-manager-65/content/sites/authoring/essentials/basic-handling).

<!--
Comment Type: draft lastmodifiedby="mgulati" lastmodifieddate="2018-08-17T03:12:05.096-0400" type="annotation">Removed:- "Selecting assets in list view To select all items in the list, use the checkbox at the upper left of the list. When all items in the list are selected, this check box appears checked. To deselect all, click the checkbox. When only some items are selected, it appears with a minus sign. To select all, click the checkbox. To deselect all, click the checkbox again. You can change the order of items using the dotted vertical bar at the far right of each item in the list. Click the vertical selection bar and drag the item to a new position in the list."
 -->

### View settings in list view

The List view shows the asset **[!UICONTROL Name]** as the first column by default. Additional information, such as asset **[!UICONTROL Title]**, **[!UICONTROL Locale]**, **[!UICONTROL Type]**, **[!UICONTROL Dimensions]**, **[!UICONTROL Size]**, **[!UICONTROL Rating]**, publish status are also shown. However, you can select the columns to be shown using **[!UICONTROL View Settings]**.

![](assets/list-view-setting.png)

### Column View

 ![](assets/column-view.png)

Use the column view to navigate a content tree through a series of cascading columns. This view helps you visualize and traverse the asset hierarchy.

Selecting a resource in the first (leftmost) column displays child resources in the second column to the right. Selecting a resource in the second column displays child resources in the third column to the right, and so on.

You can navigate up and down in the tree. Click the resource name or the chevron to the right of the resource name.

* The resource name and chevron are highlighted when clicked.
* Tapping or clicking the thumbnail selects the resource.
* When selected, a check mark is overlaid on the thumbnail and the resource name is highlighted.
* The details of the selected resource are shown in the final column.

When an asset is selected in column view, a visual representation of the asset is displayed in the final column along with the following details:

* Title
* Name
* Dimensions
* Date and time when the asset was published to Brand Portal from AEM
* Size
* Type
* More Details option that goes with the details page of the asset

<!--
Comment Type: draft

<h3>Selecting Resources</h3>
-->

<!--
Comment Type: draft

<p>Selecting a specific resource depends on a combination of the view and the device:</p>
-->

<!--
Comment Type: draft

<table border="1" cellpadding="1" cellspacing="0" width="100%">
<tbody>
<tr>
<td> </td>
<td>Select</td>
<td>Deselect</td>
</tr>
<tr>
<td>Column View<br /> </td>
<td>
<ul>
<li>Desktop:<br /> Mouseover, then use the check mark quick action</li>
<li>Mobile device:<br /> Tap the thumbnail</li>
</ul> </td>
<td>
<ul>
<li>Desktop:<br /> Click the thumbnail</li>
<li>Mobile device:<br /> Tap the thumbnail</li>
</ul> </td>
</tr>
<tr>
<td>Card View<br /> </td>
<td>
<ul>
<li>Desktop:<br /> Mouseover, then use the check mark quick action</li>
<li>Mobile device:<br /> Tap-and-hold the card</li>
</ul> </td>
<td>
<ul>
<li>Desktop:<br /> Click the card</li>
<li>Mobile device:<br /> Tap the card</li>
</ul> </td>
</tr>
<tr>
<td>List View</td>
<td>
<ul>
<li>Desktop:<br /> Mouseover, then use the check mark quick action</li>
<li>Mobile device:<br /> Tap the thumbnail</li>
</ul> </td>
<td>
<ul>
<li>Desktop:<br /> Click the thumbnail</li>
<li>Mobile device:<br /> Tap the thumbnail</li>
</ul> </td>
</tr>
</tbody>
</table>
-->

<!--
Comment Type: draft

Deselecting All
-->

<!--
Comment Type: draft

<p>In all cases, as you select items the count of the items selected is displayed at the upper right of the toolbar.</p>
<p>You can deselect all items and exit selection mode by clicking the X next to the count.</p>
-->

<!--
Comment Type: draft

<p>In all views, all items can be deselected by clicking escape on the keyboard if you are using a desktop device.</p>
-->

## Content Tree {#content-tree}

In addition to these views, use the tree view to drill down the asset hierarchy while you view and select desired assets or folders.

To open the tree view, click the rail selector at upper left and select the **[!UICONTROL Content tree]** from the menu.

![](assets/contenttree.png)

From the content hierarchy, navigate to the desired asset.

![](assets/content-tree.png)

## Asset Details {#asset-details}

Asset detail page lets you view an asset, download, share the asset's link, move it to a collection, or view its properties page. It also lets you navigate the details page of other assets of the same folder in succession.

![](assets/asset-detail.png)

To view the asset's metadata, or view its various renditions, use the rail selector on the asset detail page.

![](assets/asset-overview.png)

You can view all the available renditions of the asset on the asset details page, and select a rendition from the **[!UICONTROL Renditions]** panel to preview it.

![](assets/renditions.png)

<!-- removed as it is fixed in 2022.02.0 release
>[!CAUTION]
>
>(**Experience Manager Assets as a Cloud Service** only) The following known issues will be fixed in the upcoming release:
>
>The **[!UICONTROL Renditions]** panel does not list all the static renditions of the assets that are published to Brand Portal after December 16, 2021.
>
>The **[!UICONTROL Renditions]** panel lists the smart crop renditions of the asset, however, the user cannot preview or download the smart crop renditions.
-->

To open the asset properties page, use the **[!UICONTROL Properties (p)]** option from the top bar.

![](assets/asset-properties.png)

You can also view a list of all its related assets (source or derived assets on AEM) on an asset's properties page, as asset relationship is also published from AEM to Brand Portal.
