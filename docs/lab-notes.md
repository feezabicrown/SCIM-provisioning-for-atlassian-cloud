# Configure SCIM Provisioning for Atlassian Cloud

## Overview

Configure SCIM-based user provisioning between Microsoft Entra ID and Atlassian Cloud to automate user lifecycle management.

## Objective

Establish automated user provisioning and deprovisioning from Microsoft Entra ID to Atlassian Cloud using the SCIM protocol.

## Step 1: Create Identity Provider Directory

I initiated the creation of a Microsoft Entra ID identity provider directory within Atlassian Guard and selected the manual provisioning option to enable SCIM integration.

## Step 2: Configure User Provisioning

I selected the user provisioning option to establish automated user lifecycle management between Microsoft Entra ID and Atlassian Cloud.

## Step 3: Generate SCIM Configuration Details

I generated the SCIM Base URL and API key in Atlassian Guard. These values were required to establish a secure provisioning connection between Microsoft Entra ID and Atlassian Cloud.

![Generated SCIM Base URL and API key](../screenshots/Generated-SCIM-Base-URL-and-API-key-for-Microsoft-Entra-ID-provisioning)

*Generated SCIM Base URL and API key for Microsoft Entra ID provisioning.*

## Step 4: Save the SCIM Configuration

I completed the SCIM configuration in Atlassian Guard and saved the provisioning settings. Atlassian confirmed that user provisioning was successfully configured and ready to synchronize users from Microsoft Entra ID.

## Step 5: Verify Initial SCIM Directory State

I verified that the Microsoft Entra ID directory had been successfully created in Atlassian Guard before enabling synchronization. At this stage, no users or groups had been provisioned from Microsoft Entra ID.

![Initial SCIM directory state](../screenshots/Initial-SCIM-directory-state-before-user-provisioning)

*Initial SCIM directory state before user provisioning.*

## Step 6: Add the Atlassian Cloud Enterprise Application

I added the Atlassian Cloud enterprise application from the Microsoft Entra application gallery to enable SCIM-based user provisioning.

## Step 7: Configure the SCIM Connection

I began configuring automatic user provisioning in Microsoft Entra ID by providing the SCIM endpoint and API key generated in Atlassian Guard.

## Step 8: Validate the SCIM Connection

I entered the SCIM Base URL and API key generated in Atlassian Guard into the Atlassian Cloud enterprise application in Microsoft Entra ID. I then tested the connection to verify successful communication between Microsoft Entra ID and Atlassian Cloud.

![Successful SCIM connection](../screenshots/Successful-SCIM-provisioning-connection-between-Microsoft-Entra-ID-and-Atlassian-Cloud)

*Successful SCIM provisioning connection between Microsoft Entra ID and Atlassian Cloud.*

## Step 9: Create the Provisioning Configuration

I created the provisioning configuration in Microsoft Entra ID using the SCIM endpoint and API key from Atlassian Guard. Microsoft Entra ID successfully established the provisioning connection and prepared the synchronization job.

## Step 10: Assign a User for Provisioning

I assigned Sofia Martinez to the Atlassian Cloud enterprise application so that Microsoft Entra ID could provision the account to Atlassian Cloud through SCIM.

## Step 11: Enable Automatic Provisioning

I enabled automatic provisioning in Microsoft Entra ID to synchronize assigned users and groups to Atlassian Cloud through SCIM.

## Step 12: Start User Provisioning

After assigning Sofia Martinez to the Atlassian Cloud enterprise application, I started the provisioning service in Microsoft Entra ID. Entra initiated the first synchronization cycle and successfully completed the initial sync with Atlassian Cloud using the SCIM connection configured earlier.

## Step 13: Verify SCIM Provisioning

I verified that Microsoft Entra ID successfully provisioned the assigned user to Atlassian Cloud. The provisioning logs confirmed that Sofia Martinez was created in Atlassian Cloud and that the required user attributes were synchronized through SCIM.

![User created in Atlassian Cloud](../screenshots/Verification-that-Microsoft-Entra-ID-successfully-created-a-user-account-in-Atlassian-Cloud)

*Verification that Microsoft Entra ID successfully created a user account in Atlassian Cloud through SCIM provisioning.*

![Successful SCIM user provisioning](../screenshots/Verification-of-successful-SCIM-user-provisioning-from-Microsoft-Entra-ID-to-Atlassian-Cloud)

*Verification of successful SCIM user provisioning from Microsoft Entra ID to Atlassian Cloud.*

## Conclusion

This project successfully demonstrated SCIM-based user provisioning between Microsoft Entra ID and Atlassian Cloud. The assigned user was automatically provisioned into Atlassian Cloud, validating the configuration and synchronization process.
