---
title: "Remove a former employee - Overview"
f1.keywords:
- NOCSH
ms.author: kwekua
author: kwekua
manager: scotv
audience: Admin
ms.topic: article
ms.service: o365-administration
ms.localizationpriority: medium
ms.collection: 
- M365-subscription-management
- Adm_O365
- Adm_TOC
- SPO_Content
ms.custom:
- MSStore_Link
- TRN_M365B
- OKR_SMB_Videos
- AdminSurgePortfolio
- AdminTemplateSet
- m365solution-removeemployee
- business_assist
search.appverid:
- BCS160
- MET150
- MOE150
description: "Follow the steps in this solution to remove a former employee from Microsoft 365 and secure your organization's data."
---

# Overview: Remove a former employee and secure data

A question we often get is, "What should I do to secure data and protect access when an employee leaves my organization?" This article series explains how to block access to Microsoft 365 so these users can't sign in to Microsoft 365, the steps you should take to secure organization data, and how to allow other employees to access email and OneDrive data.

> [!TIP]
> If you need help with the steps in this topic, consider [working with a Microsoft small business specialist](https://go.microsoft.com/fwlink/?linkid=2186871). With Business Assist, you and your employees get around-the-clock access to small business specialists as you grow your business, from onboarding to everyday use.

## Before you begin

You need to be a global administrator to complete the steps in this solution.

To complete the steps in this series, you use these Microsoft 365 capabilities and features.

|Product or component|Capability or feature|
|---|---|
|Microsoft 365 admin center|Convert mailbox, forward email, revoke access, remove user |
|Exchange admin center|Block user, block access to email, wipe device |
|OneDrive and SharePoint |Give access to other users |
|Outlook|Import pst files, add mailbox |
|Active Directory|Remove users in hybrid environments |

## Watch: Delete a user

> [!VIDEO https://www.microsoft.com/videoplayer/embed/RE1FOfR?autoplay=false]

When an employee leaves the company, you'll need to remove them from Microsoft 365 for business. Before doing so, you should block them from accessing company files, preserve the documents they created, and perform several other admin tasks associated with removing a user.

1. From the admin center, select **Users**, and choose **Active users**.
1. Select the user you want to remove, and then select **Delete user**.
1. Check the box to remove their license, and check the box to remove their email aliases.
1. Check the box to give another user access to the former employee’s email, and choose **Select a user and set email options**.
1. To remove associated email aliases, select **X** next to their aliases.
1. Review the shared mailbox information, and select **Finish**.
1. Confirm your options are set correctly, and choose **Assign and convert**.
1. Review your results, and select **Close**.

After you remove a user, you have up to 30 days to restore their account.

## Solution: Remove a former employee

> [!IMPORTANT]
> Although we've numbered the steps in this solution and you don't have to complete the solution using the exact order, we do recommend doing the steps this way.

:::image type="content" source="../../media/delete-user-account.png" alt-text="Screenshot: Steps for removing a former employee from your organization":::

<br>

****

|Step|Why do this|
|---|---|
|[Step 1 - Prevent a former employee from logging in and block access to Microsoft 365 services](remove-former-employee-step-1.md)|This blocks your former employee from logging in to Microsoft 365 and prevents the person from accessing Microsoft 365 services.|
|[Step 2 - Save the contents of a former employee's mailbox](remove-former-employee-step-2.md)|This is useful for the person who is going to take over the employee's work, or if there is litigation.|
|[Step 3 - Wipe and block a former employee's mobile device](remove-former-employee-step-3.md)|Removes your business data from the phone or tablet.|
|[Step 4 - Forward a former employee's email to another employee or convert to a shared mailbox](remove-former-employee-step-4.md)|This lets you keep the former employee's email address active. If you have customers or partners still sending email to the former employee's address, this gets them to the person taking over the work.|
|[Step 5 - Give another employee access to OneDrive and Outlook data](remove-former-employee-step-5.md)|If you only remove a user's license but don't delete the account, the content in the user's OneDrive will remain accessible to you even after 30 days. <p> Before you delete the account, you should give access of their OneDrive and Outlook to another user. After you delete an employee's account, the content in their OneDrive and Outlook is retained for **30** days. During that 30 days, however, you can restore the user's account, and gain access to their content. If you restore the user's account, the OneDrive and Outlook content will remain accessible to you even after 30 days.| 
|[Step 6 - Remove and delete the Microsoft 365 license from a former employee](remove-former-employee-step-6.md)|When you remove a license, you can assign it to someone else. Or, you can delete the license so you don't pay for it until you hire another person. <p> When you remove or delete a license, the user's old email, contacts, and calendar are retained for **30 days**, then permanently deleted. If you remove or delete a license but don't delete the account, the content in the user's OneDrive will remain accessible to you even after 30 days.|
|[Step 7 - Delete a former employee's user account](remove-former-employee-step-7.md)|This removes the account from your admin center. Keeps things clean.|

## Related content

[Restore a user](restore-user.md) (article)\
[Add a new employee to Microsoft 365](add-new-employee.md) (article)\
[Assign licenses to users](../manage/assign-licenses-to-users.md) (article)\
[Unassign licenses from users](../manage/remove-licenses-from-users.md) (article)
