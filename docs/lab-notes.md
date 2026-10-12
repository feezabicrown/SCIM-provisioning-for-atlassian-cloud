# Configure SCIM Provisioning for Atlassian Cloud

## Overview

Configure SCIM-based user provisioning between Microsoft Entra ID and Atlassian Cloud to automate user lifecycle management.

## Objective

Establish automated user provisioning and deprovisioning from Microsoft Entra ID to Atlassian Cloud using the SCIM protocol.

## Step 1: Create Identity Provider Directory

I initiated the creation of a Microsoft Entra ID identity provider directory within Atlassian Guard and selected the manual provisioning option to enable SCIM integration.

![Microsoft Entra ID directory creation](../Screenshots/scim-step-01.png)

*Microsoft Entra ID directory creation with manual SCIM provisioning selected.*

## Step 2: Configure User Provisioning

I selected the user provisioning option to establish automated user lifecycle management between Microsoft Entra ID and Atlassian Cloud.

![User provisioning configuration](../Screenshots/scim-step-02.png)

*Selecting user provisioning for SCIM-based user lifecycle management.*

## Step 3: Generate SCIM Configuration Details

I generated the SCIM Base URL and API key in Atlassian Guard. These values were required to establish a secure provisioning connection between Microsoft Entra ID and Atlassian Cloud.

![SCIM configuration details](../Screenshots/scim-step-03.png)

*Generated SCIM Base URL and API key for Microsoft Entra ID provisioning.*

## Step 4: Save the SCIM Configuration

I completed the SCIM configuration in Atlassian Guard and saved the provisioning settings. Atlassian confirmed that user provisioning was successfully configured and ready to synchronize users from Microsoft Entra ID.

![SCIM configuration saved](../Screenshots/scim-step-04.png)

*SCIM provisioning configuration completed and saved in Atlassian Guard.*

## Step 5: Verify Initial SCIM Directory State

I verified that the Microsoft Entra ID directory had been successfully created in Atlassian Guard before enabling synchronization. At this stage, no users or groups had been provisioned from Microsoft Entra ID.

![Initial SCIM directory](../Screenshots/scim-step-05.png)

*Initial SCIM directory state before user provisioning.*

## Step 6: Add the Atlassian Cloud Enterprise Application

I added the Atlassian Cloud enterprise application from the Microsoft Entra application gallery to enable SCIM-based user provisioning.

![Atlassian enterprise application](../Screenshots/scim-step-06.png)

*Atlassian Cloud enterprise application added to Microsoft Entra ID.*

## Step 7: Configure the SCIM Connection

I began configuring automatic user provisioning in Microsoft Entra ID by providing the SCIM endpoint and API key generated in Atlassian Guard.

![SCIM connection configuration](../Screenshots/scim-step-07.png)

*Preparing the SCIM provisioning connection between Microsoft Entra ID and Atlassian Cloud.*

## Step 8: Validate the SCIM Connection

I entered the SCIM Base URL and API key generated in Atlassian Guard into the Atlassian Cloud enterprise application in Microsoft Entra ID. I then tested the connection to verify successful communication between Microsoft Entra ID and Atlassian Cloud.

![SCIM connection validation](../Screenshots/scim-step-08.png)

*Successful SCIM provisioning connection between Microsoft Entra ID and Atlassian Cloud.*

## Step 9: Create the Provisioning Configuration

I created the provisioning configuration in Microsoft Entra ID using the SCIM endpoint and API key from Atlassian Guard. Microsoft Entra ID successfully established the provisioning connection and prepared the synchronization job.

![Provisioning configuration created](../Screenshots/scim-step-09.png)

*Provisioning configuration successfully created for Atlassian Cloud.*

## Step 10: Assign a User for Provisioning

I assigned Sofia Martinez to the Atlassian Cloud enterprise application so that Microsoft Entra ID could provision the account to Atlassian Cloud through SCIM.

![User assigned for provisioning](../Screenshots/scim-step-10.png)

*Sofia Martinez assigned to the Atlassian Cloud enterprise application.*

## Step 11: Enable Automatic Provisioning

I enabled automatic provisioning in Microsoft Entra ID to synchronize assigned users and groups to Atlassian Cloud through SCIM.

![Automatic provisioning enabled](../Screenshots/scim-step-11.png)

*Automatic SCIM provisioning enabled for Atlassian Cloud.*

## Step 12: Start User Provisioning

After assigning Sofia Martinez to the Atlassian Cloud enterprise application, I started the provisioning service in Microsoft Entra ID. Entra initiated the first synchronization cycle and successfully completed the initial sync with Atlassian Cloud using the SCIM connection configured earlier.

![Initial synchronization completed](../Screenshots/scim-step-12.png)

*Initial SCIM synchronization completed successfully between Microsoft Entra ID and Atlassian Cloud.*

## Step 13: Verify SCIM Provisioning

I verified that Microsoft Entra ID successfully provisioned the assigned user to Atlassian Cloud. The provisioning logs confirmed that Sofia Martinez was created in Atlassian Cloud and that the required user attributes were synchronized through SCIM.

![SCIM provisioning verification](../Screenshots/scim-step-13.png)

*Verification that Microsoft Entra ID successfully created a user account in Atlassian Cloud through SCIM provisioning.*

![Successful user provisioning](../Screenshots/scim-step-14.png)

*Verification of successful SCIM user provisioning from Microsoft Entra ID to Atlassian Cloud.*

## Conclusion

This project successfully demonstrated SCIM-based user provisioning between Microsoft Entra ID and Atlassian Cloud. The assigned user was automatically provisioned into Atlassian Cloud, validating the configuration and synchronization process.
