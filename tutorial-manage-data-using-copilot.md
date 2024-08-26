---
title: Tutorial - Manage your BCDR estate efficiently using Azure Business Continuity Center Copilot
description: In this tutorial, learn how to manage your BCDR estate efficiently using Azure Business Continuity Center Copilot
ms.topic: how-to
ms.date: 03/29/2024
ms.service: azure-business-continuity-center
ms.reviewer: dapatil
author: AbhishekMallick-MS
ms.author: v-abhmallick
---

# Tutorial: Manage your BCDR estate efficiently using Azure Business Continuity Center Copilot

This article describes how to leverage Azure Business Continuity Center Copilot to make your business continuity journey easy.  

## What is Azure Business Continuity Center Copilot? 
Azure Business Continuity Center Copilot assists users in protecting and recovering their resources. Below are the key use cases for the ABCC Copilot MVP, prioritized by the four BCDR pillars: 

1. Protection Management 

1. Ransomware Protection 

1. Monitoring and Reporting 

1. Learn and get help on capabilities.

With Azure Business Continuity Center Copilot (preview), you can ask questions about your Azure resources' protection directly within the Azure portal using natural language. The Copilot retrieves information about your resources and their protection status and guides you through relevant processes. 

## Sample prompts 

The following table lists all supported prompts:

| Category | Prompts |
| --- | --- |
| [Security] | - "How many vaults are in poor security level?" <br> - "Show security level of all the vaults." <br> - "How can I increase the security level of a vault?"  |
| [Management] | - "Show the BCDR real estate across all the subscriptions" <br> - "Show the datasources which are not protected in XXX regions" <br> - "Show me a list of all datasources which are protected only using ASR"  <br> |
| [Monitoring] | - "Which data sources do not have RP/Recovery Point in the last 7 days" <br> - "How Many backup jobs failed in last 12 hours?" <br> - "Retrigger backup for all failed backup jobs in the last 24 hours" 


## Examples 

1. **View the BCDR real estate across all the subscriptions** <br>

You can Ask Copilot for Azure Business Continuity Center(preview) to get information on your resource protection with prompts like **"Show the BCDR real estate across all the subscriptions"** <br>
Copilot provides a summary of resources based on their protection status and generates an ARG query that you can run directly to get detailed information. Additionally, you can export the data as a CSV file from the ARG Query Explorer page. 

:::image type="content" source="./media/business-continuity-center-copilot/Show-BCDR-real-estate-Prompt.png" alt-text="Screenshot showing Copilot prompt." lightbox="./media/business-continuity-center-copilot/Show-BCDR-real-estate-Prompt.png":::

:::image type="content" source="./media/business-continuity-center-copilot/Show-BCDR-real-estate-result.png" alt-text="Screenshot showing Copilot BCDR estate result." lightbox="./media/business-continuity-center-copilot/Show-BCDR-real-estate-result.png":::


2.	**Enhance the protection for your resources.** <br>
In addition to providing a summary of your BCDR resources, Copilot also helps you improve resilience by enhancing the protection of existing resources. With this feature, you can enable protection using multiple available solutions. **Currently, this feature is only available for Azure VMs.**

:::image type="content" source="./media/business-continuity-center-copilot/Show-BCDR-real-estate-result.png" alt-text="Screenshot showing Copilot BCDR estate result." lightbox="./media/business-continuity-center-copilot/Show-BCDR-real-estate-result.png":::

**Step 1: Select your virtual machine.** <br>

:::image type="content" source="./media/business-continuity-center-copilot/Enhance-protection-select-item.png" alt-text="Screenshot showing Copilot BCDR estate result." lightbox="./media/business-continuity-center-copilot/Enhance-protection-select-item.png":::

**Step 2: Review your current protection details and move forward with enhance protection.** <br>

:::image type="content" source="./media/business-continuity-center-copilot/Enhance-protection-select-solution.png" alt-text="Screenshot showing current protection details." lightbox="./media/business-continuity-center-copilot/Enhance-protection-select-solution.png":::

**Step 3: You’ll be taken to a specific solution blade where you can configure Backup/DR.**  <br>

:::image type="content" source="./media/business-continuity-center-copilot/Enhance-protection-configure-solution.png" alt-text="Screenshot showing configure solution." lightbox="./media/business-continuity-center-copilot/Enhance-protection-configure-solution.png":::

2.	**View security level.** <br>

You can ask Copilot for a summary of your security posture and get guidance on enhancing your security. 
Start by asking, "Show security level for all datasources." Copilot will provide a summary of the number of datasources based on their security levels. You can also run an ARG query inline for more details or download the data as a CSV file.

:::image type="content" source="./media/business-continuity-center-copilot/view-security-level.png" alt-text="Screenshot showing security levels for datasource." lightbox="./media/business-continuity-center-copilot/view-security-level.png":::
## Next steps

- []()
