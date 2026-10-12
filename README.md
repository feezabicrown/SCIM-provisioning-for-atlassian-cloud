# Atlassian Cloud SCIM Provisioning Lab

## Project Overview

I configured automated user provisioning and deprovisioning between Microsoft Entra ID and Atlassian Cloud using System for Cross-domain Identity Management (SCIM).

## Business Scenario

South West Tech needed an automated identity lifecycle management solution to reduce manual account administration and ensure users receive and lose application access appropriately.

## Tools Used

- Microsoft Entra ID
- Atlassian Cloud
- SCIM Provisioning

## What I Built

- Configured Atlassian Cloud as an enterprise application in Microsoft Entra ID
- Established SCIM provisioning between Entra ID and Atlassian Cloud
- Assigned users for application provisioning
- Tested and verified successful user provisioning
- Tested user deprovisioning by removing application assignment

## Screenshots

Configuration and testing evidence is available in the [Screenshots](../Screenshots/) folder.

## Security Lessons Learned

SCIM automates identity lifecycle management, reduces manual administration and helps prevent unnecessary access by deprovisioning users when application access is removed.

## Documentation

Detailed implementation notes are available in [docs/lab-notes.md](docs/lab-notes.md).
