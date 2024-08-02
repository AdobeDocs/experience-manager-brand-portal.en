---
title: Administer General Tenant Configurations
description: Configure download acceleration, public smart collection creation, public collection creation, and enable admin users to delete assets on tenants.
contentOwner: mgulati
topic-tags: administration
content-type: reference
products: SG_EXPERIENCEMANAGER/Brand_Portal
role: Admin
exl-id: 5607be8e-0a7f-4692-b71b-5f66eb9ac5ee
---
# Administer general tenant configurations {#administer-general-tenant-configurations}

Experience Manager Assets Brand Portal allows organizations to configure the following capabilities for specific tenants:

* Asset deletion by administrators
* Public collection creation by non-admin users
* Public smart collection creation by non-admin users
* The parent hierarchy of shared folders is visible to non-admin users

These configurations have been provided as **[!UICONTROL General Settings]** configurations in the administrative tools panel.

![](assets/general-config.png)

**A** - Configuration to let administrators delete assets from Brand Portal. (Default is enabled)

**B** - Configuration to let non-admin users create public collections. (Default is enabled)

**C** - Configuration to let non-admin users create public smart collections. (Default is enabled)

**D** - Configuration to display the folder hierarchy (from the root) of shared folders to non-admin users (Editors, Viewers, Guest Users). (Default is disabled)

## Enable or Disable General configurations {#enable-disable-general-configurations}

To enable or disable each of these configurations:

1. Log in with administrator privileges.
1. Select the Experience Manager logo to access administrative tools from the toolbar at the top.
1. From the administrative tools panel, select **[!UICONTROL General]** to open the **[!UICONTROL General Settings]** page.
1. Use the respective toggle switch to enable or disable any of the General configurations.
1. **[!UICONTROL Save]** the changes.
1. Log out so the changes can take effect.

## Allow admin users to delete assets from Brand Portal {#allow-admin-users-to-delete-assets-from-brand-portal}

**[!UICONTROL Allow users to delete]** configuration enables organizations to allow (or restrict) users with administrator privileges to delete assets and folders from Brand Portal.

## Allow public collections creation by non-admins {#allow-public-collections-creation-by-non-admins}

[[!UICONTROL Allow public collections creation]](../using/brand-portal-share-collection.md#main-pars-text-1915052376) configuration controls whether non-administrators can create public collections on Brand Portal. The configuration is enabled by default. By disabling the configuration, organizations can prevent having numerous public collections on their portal so that system space can be saved.

## Allow public smart collections creation by non-admins {#allow-public-smart-collections-creation-by-non-admins}

[[!UICONTROL Allow public smart collections creation]](../using/brand-portal-searching.md#main-pars-header-500620467) configuration controls whether non-administrators can save their searches as smart collections and make them public for that tenant. The configuration is enabled by default. By disabling the configuration, organizations can prevent having a huge number of public smart collections created by non-admin users on the organization's Brand Portal.

<!-- 
## Allow download acceleration {#allow-download-acceleration}

[[!UICONTROL Allow download acceleration]](../using/accelerated-download.md) configuration lets the organizations to allow accelerated downloads of assets from Brand Portal and shared links, by integrating with IBM Aspera Connect that is an install-on-demand application. The application uses proprietary technology to remove TCP overheads.
-->

## Enable Folder Hierarchy {#enable-folder-hierarchy}

[[!UICONTROL Enable Folder Hierarchy]](../using/brand-portal-sharing-folders.md#non-admin-user-access-to-shared-folders) configuration allows the administrators to control how the non-admin users (Editors, Viewers, and Guest Users) see the shared folders after logging in.
