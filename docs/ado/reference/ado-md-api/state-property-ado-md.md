---
description: "State Property (ADO MD)"
title: "State Property (ADO MD) | Microsoft Docs"
ms.prod: sql
ms.prod_service: connectivity
ms.technology: connectivity
ms.custom: ""
ms.date: "01/19/2017"
ms.reviewer: ""
ms.topic: conceptual
apitype: "COM"
f1_keywords: 
  - "State"
  - "Cellset::State"
helpviewer_keywords: 
  - "State property [ADO MD]"
ms.assetid: 06d480ca-9eb6-4570-a45d-a73539bddd32
author: rothja
ms.author: jroth
---
# State Property (ADO MD)
Indicates the current state of the cellset.  
  
## Return Values  
 Returns a **Long** integer indicating the current condition of the [Cellset](./cellset-object-ado-md.md) object and is read-only. The following values are valid: **adStateClosed** (0) and **adStateOpen** (1).  
  
## Remarks  
 To use the [ObjectStateEnum](../ado-api/objectstateenum.md) constant names, you must have the ADO type library referenced in your project. See [Using ADO with ADO MD](../../guide/multidimensional/using-ado-with-ado-md.md) for more information.  
  
## Applies To  
 [Cellset Object (ADO MD)](./cellset-object-ado-md.md)  
  
## See Also  
 [Close Method (ADO MD)](./close-method-ado-md.md)   
 [Open Method (ADO MD)](./open-method-ado-md.md)