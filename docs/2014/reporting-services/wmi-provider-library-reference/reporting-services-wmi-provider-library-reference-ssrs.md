---
title: "Reporting Services WMI Provider Library Reference (SSRS) | Microsoft Docs"
ms.custom: ""
ms.date: "06/13/2017"
ms.prod: "sql-server-2014"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "reporting-services-native"
ms.tgt_pltfrm: ""
ms.topic: conceptual
api_name: 
  - "Reporting Services WMI Provider Library"
api_location: 
  - "reportingservices.mof"
topic_type: 
  - "apiref"
helpviewer_keywords: 
  - "WMI provider [Reporting Services], library"
ms.assetid: 17ba711d-7eff-4423-9168-63dc425a3428
caps.latest.revision: 42
author: "douglaslM"
ms.author: "douglasl"
manager: "mblythe"
---
# Reporting Services WMI Provider Library Reference (SSRS)
  The [!INCLUDE[ssRSnoversion](../../includes/ssrsnoversion-md.md)] Windows Management Instrumentation (WMI) provider supports WMI operations that enable you to write scripts and code to modify settings of the report server and Report Manager.  
  
 For example, if you want to change whether integrated security is used when the report server connects to the report server database, create an instance of the MSReportServer_ConfigurationSetting class and use the DatabaseIntegratedSecurity property of the of the report server instance. The classes shown in the following table represent [!INCLUDE[ssRSnoversion](../../includes/ssrsnoversion-md.md)] components. The classes are defined in either the [!INCLUDE[ssRSWMInmspc](../../includes/ssrswminmspc-md.md)] or the [!INCLUDE[ssRSWMInmspcA](../../includes/ssrswminmspca-md.md)] namespaces. Each of the classes support read and write operations. Create operations are not supported.  
  
## Classes  
 [MSReportServer_Instance Class](msreportserver-instance-class.md)  
 Provides basic information required for a client to connect to an installed report server.  
  
 [MSReportServer_ConfigurationSetting Class](msreportserver-configurationsetting-class.md)  
 Represents the installation and run-time parameters of a report server instance. These parameters are stored in the configuration file for the report server.  
  
 For more information about WMI operations, see the WMI SDK documentation included with the [!INCLUDE[msCoName](../../includes/msconame-md.md)] [!INCLUDE[dnprdnshort](../../includes/dnprdnshort-md.md)] SDK.  
  
## See Also  
 [Access the Reporting Services WMI Provider](../tools/access-the-reporting-services-wmi-provider.md)   
 [Technical Reference &#40;SSRS&#41;](../technical-reference-ssrs.md)  
  
  