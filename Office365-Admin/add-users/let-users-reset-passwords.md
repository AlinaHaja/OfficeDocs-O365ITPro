---
title: "Let users reset their own passwords in Office 365"
ms.author: dianef
author: dianef77
manager: mnirkhe
ms.audience: Admin
ms.topic: get-started-article
ms.service: o365-administration
localization_priority: Normal
ms.collection:
- Adm_O365
- Adm_O365_Top
- strat_admin_top
ms.custom:
- Adm_O365
- Adm_O365_FullSet
- Adm_O365_Top
- Core_O365Admin_Migration
- MiniMaven
- strat_admin_top
search.appverid:
- BCS160
- MET150
- MOE150
ms.assetid: 5bc3f460-13cc-48c0-abd6-b80bae72d04a
description: "Learn how you can reset your passwords using the self-service password reset tool."
---

# Let users reset their own passwords in Office 365
Getting crushed with people asking you to reset their passwords? As the Office 365 admin, you can let people use the [self-service password reset tool](https://go.microsoft.com/fwlink/p/?LinkId=522677) so you don't have to reset passwords for them. Less work for you! 
  
Here are a few things you need to know:
  
- You get self-service password reset for cloud users **free** with any Office 365 business, education, or nonprofit paid plan. It doesn't work with Office 365 trial. 
    
- It uses Azure. You'll automatically get this feature in Azure for **free** when you do these steps. It won't cost you anything to turn on self-service password reset if you don't use other Azure features. 
    
- **If you're using an on-premises Active Directory**, the above two points don't apply. Rather, you can set this up but **it requires a paid subscription to Azure AD Premium**. 
    
## Let people reset their own passwords in Office 365

These steps turn on self-service password reset for everyone in your business.
  
::: moniker range="o365-worldwide"
1.  Go to the [![Go to the Office 365 admin center.](../media/e00ba917-c3fb-4173-b344-43eb5c7eeb15.png)](https://portal.office.com/adminportal/home).

::: moniker-end

::: moniker range="o365-germany"

1. Go to the [Office 365 admin center](https://portal.office.de/adminportal/home).

::: moniker-end

::: moniker range="o365-21vianet"

1. Go to the [Office 365 admin center](https://login.partner.microsoftonline.cn).

::: moniker-end

2. Choose **Settings** \> **Security &amp; privacy**.
    
3. Choose the link for the **Azure AD admin center**. You'll get Azure for free!
    
    ![Choose the link to go to the Azure admin center.](../media/1b72241f-df7b-44b0-9477-8687fe9f7315.png)
  
4. Choose **Users and groups** \> **Password reset**.
    
    ![Choose Users and groups](../media/8d6739c8-b245-437c-8a77-63b38db4429b.png)
  
5. On the Properties page, choose **All** to enable it for everyone in your business, and then choose **Save**.
    
    ![Choose All](../media/1a7ad5c4-1dbe-46b9-9ed0-5507b62023d0.png)
  
6. When your users sign in to Office 365, they will be prompted to enter additional contact information that will help them reset their password in the future.

::: moniker range="o365-worldwide"

Need help with the steps in this topic? We’ve got you covered. Make an appointment at your local Microsoft Store with an Answer Desk expert to help resolve your issue.

Go to the [Microsoft Stores page](https://go.microsoft.com/fwlink/?LinkID=2041482) and choose your location to schedule an appointment.

::: moniker-end

## Related articles

[Set the password expiration policy for your organization](../manage/set-password-expiration-policy.md)
  
[Set an individual user's password to never expire](set-password-to-never-expire.md)
  

