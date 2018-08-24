---
title: "Create app discovery reports using Office 365 Cloud App Security"
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 2/26/2018
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
search.appverid:
- MET150
- MOE150
ms.assetid: 3e68e691-1fc4-4d3e-a2c0-d3134eb64055
description: "Create reports with Office 365 Cloud App Security that enable you to understand how people in your organization are using Office 365 and other apps."
---

# Create app discovery reports using Office 365 Cloud App Security

Office 365 Advanced Security Management is now Office 365 Cloud App Security.
  
|****Evaluation** \>**|****Planning** \>**|****Deployment** \>**|****Utilization****|
|:-----|:-----|:-----|:-----|
|[Start evaluating](office-365-cas-overview.md) <br/> |[Start planning](get-ready-for-office-365-cas.md) <br/> |[Start deploying](turn-on-office-365-cas.md) <br/> |You are here!  <br/> [Next steps](#next-steps) <br/> |
   
Office 365 Cloud App Security helps global administrators, security administrators, and security readers gain insight into the cloud services people in an organization are using. For example, you can see where users are storing and collaborating on documents and how much data is being uploaded to apps or services that are outside of Office 365.
  
To generate an app discovery report, you manually upload your web traffic log files from your firewalls and proxies, and then Office 365 Cloud App Security parses and analyzes those files for your report.
  
> [!NOTE]
> You must be a global administrator, security administrator, or security reader to perform the tasks described in this article. To learn more, see [Permissions in the Office 365 Security &amp; Compliance Center](permissions-in-the-security-and-compliance-center.md). 
  
## Create a report with app discovery

To create an app discovery report, you identify the vendor data source for the log files that you want to have analyzed, select the log files, and then request the report.
  
> [!NOTE]
> Use web traffic log files that include peak traffic periods to get the best representation of usage in your organization. 
  
1. Collect your [web traffic logs and data sources for Office 365 Cloud App Security](web-traffic-logs-and-data-sources-for-ocas.md).
    
2. Go to [https://protection.office.com](https://protection.office.com) and sign in using your work or school account. 
    
3. In the Security &amp; Compliance Center, choose **Alerts** \> **Manage advanced alerts**.
    
4. Choose **Go to Office 365 Cloud App Security**.
    
5. Choose **Discover** \> **Create new report**.
    
    ![In the Office 365 CAS portal, choose Discover](media/73b5299f-94b5-49dd-a00f-154d188eb2c5.png)
  
6. Specify a name and description for your report, and then select the data source for your web traffic logs in the **Data source** list. 
    
    ![In O365 CAS, choose Discover \> Create new report](media/22e660f0-5eb2-49fa-9fea-f88a5809a07b.png)
  
    > [!NOTE]
    > If a data source that you'd like to use is not listed, you can request that it be added. Select **Other** for **Data source**, and then type the name of the data source that you're trying to upload. We'll review the log, and let you know if we add support for the data source that generated it. 
  
7. Browse to the location of the log files you collected and select the files. The log files must have been generated by the data source that you chose for the report.
    
8. Click **Create** to start the report creation process. 
    
9. To see the status of the report, click **Manage snapshot reports**. When a report is ready, you'll see the **View report** option. 
    
## Next steps

- [Review and take action on alerts](review-office-365-cas-alerts.md)
    
- [Review app discovery findings in Office 365 Cloud App Security](review-app-discovery-findings-in-ocas.md)
    
- Review your [utilization activities for Office 365 Cloud App Security](utilization-activities-for-ocas.md)
    
