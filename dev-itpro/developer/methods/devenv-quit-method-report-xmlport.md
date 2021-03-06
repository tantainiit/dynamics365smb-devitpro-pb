---
title: "QUIT Method (Report, XMLport)"
ms.custom: na
ms.date: 04/01/2019
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.service: dynamics365-business-central
ms.assetid: 5ec8d038-e2b8-433a-9b33-8096ade4bae9
caps.latest.revision: 7
manager: edupont
redirect_url: /dynamics365/business-central/dev-itpro/developer/methods-auto/library
---

 

# QUIT Method (Report, XMLport)
Aborts the processing of a report or XMLport.  
  
## Syntax  
  
```  
  
QUIT  
```  
  
## Remarks  
 When you use the QUIT method, the report or XMLport is exited without committing any changes that were made to the database during the execution. The [OnPostReport Trigger](../triggers/devenv-OnPostReport-Trigger.md) or [OnPostXMLport Trigger](../triggers/devenv-OnPostXMLport-Trigger.md) trigger will not be called.  
  
## Example  
 The following example shows how to use the QUIT method to abort an execution without committing any changes that were made during the processing.  
  
```  
  
// Do some database processing.  
CurrReport.QUIT;  
  
```  
  
## See Also  
 [Report Data Type](../datatypes/devenv-Report-Data-Type.md)   
 [XMLport Data Type](../datatypes/devenv-XMLport-Data-Type.md)