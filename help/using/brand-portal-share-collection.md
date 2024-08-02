---
title: Share a collection
description: Learn how Experience Manager Assets Brand Portal Administrators can share and unshare a collection or a smart collection with authorized users. Editors can view and share only the collections created by them, shared with them, and public collections.
contentOwner: Vishabh Gupta
content-type: reference
topic-tags: sharing
products: SG_EXPERIENCEMANAGER/Brand_Portal
exl-id: 29b877f6-4200-4299-9b8d-81d88f4e8221
---
# Share collections {#share-collections}

A collection represents a group of related assets stored together in Adobe Experience Manager Assets Brand Portal. The users can create smart collections by [applying omnisearch or facet search to filter out related assets](brand-portal-searching.md) and store them together for easy access and further sharing it with other Brand Portal users. 

 <!--The administrators can share and unshare a collection with the authorized Brand Portal users. Editors and viewers can view and share the collections created by them, shared with them, and public collections.-->

Collections are shared as link by way of an e-mail. Everybody with access to the share link can open the collection. However, shared e-mails can be forwarded to anyone. Additionally, [shared links](https://experienceleague.adobe.com/en/docs/experience-manager-brand-portal/using/share/brand-portal-link-share) are temporary and accessible for a limited duration only. Alternatively, users can be invited as permanent members to collections. There are the following types of users for the collections:

* **Administrators** can share or unshare a collection with authorized Brand Portal users. They can invite other users to a specific collection and define their role in that collection. In addition, administrators can create public collections.

* **Editors** are allowed to create and share collections. They can invite other users to a specific collection and define their role in that collection. In addition, they can also share collections, if they have been invited to the collection as an editor or owner.

* **Viewers** can create private collections only. They cannot share a collection even when they were invited as owners.

>[!NOTE]
>
>Editors cannot change a public collection to a non-public collection and therefore do not have the **[!UICONTROL Public Collection]** check box available in the **[!UICONTROL Collection Settings]** dialog box.

## Share a collection {#share-collection}

Following are the steps to share a collection with the authorized Brand Portal users:

1. Log in to your Brand Portal tenant. By default, the **[!UICONTROL Files]** view opens which contains all the published assets and folders. 

1. From the quick navigation on the top, click **[!UICONTROL Collections]**. 

1. From the **[!UICONTROL Collections]** console, do one of the following:

   * Hover the pointer over the collection that you want to share. From the quick action thumbnails available for the collection, click the **[!UICONTROL Settings]** icon.

     ![](assets/settings-icon.png)

   * Select the collection that you want to share. From the toolbar at the top, click **[!UICONTROL Settings]**.
    
     ![](assets/collection-console.png)

1. In the **[!UICONTROL Collection Settings]** dialog box, select the users with whom you want to share the collection and select the role for the user to match their global role. For example, assign the Editor role to a global editor, the Viewer role to a global viewer.

   Alternatively, to make the collection available to all the users irrespective of their group membership and role, make it public by selecting the **[!UICONTROL Public Collection]** check box.

   >[!NOTE]
   >
   >However, non-admin users can be restricted from creating public collections, to avoid having numerous public collections so that system space can be saved. Organizations can disable the **[!UICONTROL Allow public collections creation]** configuration from **[!UICONTROL General]** settings available in the admin tools panel.

   ![](assets/collection_sharingadduser.png)

   The editors cannot change a public collection to a non-public collection and therefore do not have a **[!UICONTROL Public Collection]** check box available in the **[!UICONTROL Collection Settings]** dialog.

   ![](assets/collection-setting-editor.png)

1. Click the **[!UICONTROL Add]** button to add the user, and then click **[!UICONTROL Save]**. The collection is shared with the users.

   >[!NOTE]
   >
   >A user's role governs access to the assets and folders inside a collection. If a user does not have access to assets, an empty collection is shared with the user. Also, a user's role governs the actions available for collections.

## Unshare a collection {#unshare-a-collection}

To unshare a previously shared collection, do the following:

1. From the **[!UICONTROL Collections]** console, select the collection you want to unshare.

   From the toolbar at the top, click **[!UICONTROL Settings]**.

   ![](assets/collection_settings.png)

1. In the **[!UICONTROL Collection Settings]** dialog box, under the **[!UICONTROL Members]** section, click the **[!UICONTROL x]** symbol next to users to remove them from the list of users having access to the collection.

   ![](assets/unshare_collection.png)

1. A warning message appears. Click **[!UICONTROL Confirm]** to unshare the collection.

1. Click **[!UICONTROL Save]** to apply the changes.

   Once the user is removed from the shared list, the unshared collection is removed from the user's **[!UICONTROL Collections]** console.

<!--
1. Click the overlay icon on the left, and choose **[!UICONTROL Navigation]**.

   ![](assets/contenttree-1.png)

1. From the siderail on the left, click **[!UICONTROL Collections]**.

   ![](assets/access_collections.png)

1. From the **[!UICONTROL Collections]** console, do one of the following:

    * Hover the pointer over the collection you want to share. From the quick action thumbnails available for the collection, click the **[!UICONTROL Settings]** icon.

   ![](assets/settings_thumbnail.png)

    * Select the collection you want to share. From the toolbar at the top, click **[!UICONTROL Settings]**.
    
   ![](assets/collection-sharing.png)

1. In the [!UICONTROL Collection Settings] dialog box, select the users or groups with whom you want to share the collection and select the role for a user or a group to match their global role. For example, assign the Editor role to a global editor, the Viewer role to a global viewer.

   Alternatively, to make the collection available to all users irrespective of their group membership and role, make it public by selecting the **[!UICONTROL Public Collection]** check-box.

   >[!NOTE]
   >
   >However, non-admin users can be restricted from creating public collections, to avoid having numerous public collections so that system space can be saved. Organizations can disable the **[!UICONTROL Allow public collections creation]** configuration from [!UICONTROL General] settings available in admin tools panel.

   ![](assets/collection_sharingadduser.png)

   Editors cannot change a public collection to a non-public collection and, therefore, do not have **[!UICONTROL Public Collection]** check-box available in **[!UICONTROL Collection Settings]** dialog.

   ![](assets/collection-setting-editor.png)

1. Select **[!UICONTROL Add]**, and then **[!UICONTROL Save]**. The collection is shared with the chosen users.

   >[!NOTE]
   >
   >A user's role governs access to the assets and folders inside a collection. If a user does not have access to assets, an empty collection is shared with the user. Also, a user's role governs the actions available for collections.

## Unshare a collection {#unshare-a-collection}

To unshare a previously shared collection, do the following:

1. From the **[!UICONTROL Collections]** console, select the collection you want to unshare.

   In the toolbar, click **[!UICONTROL Settings]**.

   ![](assets/collection_settings.png)

1. On the **[!UICONTROL Collection Settings]** dialog box, under **[!UICONTROL Members]**, click the **[!UICONTROL x]** symbol next to users or groups to remove them from the list of users you shared the collection with.

   ![](assets/unshare_collection.png)

1. In the warning message box, click **[!UICONTROL Confirm]** to confirm unshare.

   Click **[!UICONTROL Save]**.

1. Log in to Brand Portal with the credentials of the user you removed from the shared list. The collection is removed from the **[!UICONTROL Collections]** console.
-->
