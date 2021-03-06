---
title: "Delete Method"
ms.author: solsen
ms.custom: na
ms.date: 04/01/2019
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.service: "dynamics365-business-central"
ms.assetid: 620f0e32-eadc-43e9-8f6e-8fc0b12c3aaf
caps.latest.revision: 9
manager: edupont
author: SusanneWindfeldPedersen
redirect_url: /dynamics365/business-central/dev-itpro/developer/methods-auto/library
---
<!--This topic is deprected, see redirection URL-->

 

# Delete Method
Sends a DELETE request to delete the resource identified by the request URL.

```
[Ok := ] HttpClient.Delete(Path, Response)
```

## Parameters
*Path*  
&emsp;Type: [String](../datatypes/devenv-text-data-type.md)

*Response*  
&emsp;Type: [HttpReponseMessage](httpresponsemessage-class.md)

## Return value
*Ok*  
&emsp;Type: [Boolean](../datatypes/devenv-boolean-data-type.md)

&emsp;**True** if the operation was successful; otherwise, **false**.

Accessing the [HttpContent](httpclient-class.md) property of [HttpResponseMessage](httpresponsemessage-class.md) in a case when the request fails will result in an error.

## See Also
[HttpClient](httpclient-class.md)  
[HttpReponseMessage](httpresponsemessage-class.md)  
[HTTP, JSON, TextBuilder, and XML API](../devenv-restapi-overview.md)  
[Getting Started with AL](../devenv-get-started.md)  
[Developing Extensions](../devenv-dev-overview.md)  

