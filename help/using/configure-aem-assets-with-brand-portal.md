---
title: Configure Experience Manager Assets with Brand Portal
description: Get an insight into configuring Experience Manager Assets with Brand Portal.
content-type: reference
contentOwner: Vishabh Gupta
topic-tags: brand-portal
products: SG_EXPERIENCEMANAGER/Brand_Portal
role: Admin
exl-id: 261c0e84-6b3d-459c-b6b9-a9af106d6943
---
# Configure Experience Manager Assets with Brand Portal {#configure-integration}

Configuring Adobe Experience Manager Assets with Brand Portal enables asset publishing, asset distribution, and asset contribution features for the Brand Portal users. It lets Experience Manager Assets users publish and distribute assets with the Brand Portal users. The Brand Portal users can access the shared assets and contribute by uploading new assets to the asset contribution folders and publishing them back to Experience Manager Assets. 

Configuring Experience Manager Assets with Brand Portal is supported on:

* Experience Manager Assets as a Cloud Service
* Experience Manager Assets (on premise and managed service) 6.5 and above

Experience Manager Assets as a Cloud Service is automatically configured with Brand Portal by activating Brand Portal from the Cloud Manager. The activation workflow creates the required configurations at the backend and activates Brand Portal on the same IMS org as of the Experience Manager Assets as a Cloud Service instance.  

Whereas Experience Manager Assets (on premise and managed service) is manually configured with Brand Portal using Adobe Developer Console, which procures an Adobe Identity Management Services (IMS) token for authorization of the Brand Portal tenant. 

>[!NOTE]
>
>***For Experience Manager Assets, 6.5 and above***
>
>Previously, the classic interface configured Brand Portal using the Legacy OAuth Gateway, which employs the JSON Web Token (JWT) exchange to obtain an IMS token for authorization.
>
>Configuration by way of Legacy OAuth is no longer supported from April 6, 2020, and is changed to configuring by way of Adobe Developer Console.


>[!TIP]
>
>***For existing customers only (on premise and managed service)*** 
>
>Legacy OAuth Gateway configuration continues working for existing customers. 
>
>In case you encounter problems with the Legacy OAuth Gateway configuration, delete the existing configuration and create a new configuration by way of Adobe Developer Console.

The steps to configure AEM Assets with Brand Portal are different depending on your AEM version, and whether you are configuring for the first time, or upgrading the existing configurations:

| **AEM Version** |**New Configuration** |**Upgrade Configuration** |
|---|---|---|
| **AEM Assets as a Cloud Service** |[Activate Brand Portal](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/brand-portal/configure-aem-assets-with-brand-portal) |- |
| **AEM 6.5 (6.5.4.0 and above)** |[Create configuration](https://experienceleague.adobe.com/en/docs/experience-manager-65/content/assets/brandportal/configure-aem-assets-with-brand-portal) |[Upgrade configuration](https://experienceleague.adobe.com/en/docs/experience-manager-65/content/assets/brandportal/configure-aem-assets-with-brand-portal#upgrade-integration-65) | 
