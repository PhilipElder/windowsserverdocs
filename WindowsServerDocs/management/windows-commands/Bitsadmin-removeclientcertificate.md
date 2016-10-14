---
title: Bitsadmin removeclientcertificate
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.technology: manage-windows-commands
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: b417c3e5-aadd-4fcc-968f-45d8b67ca516
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/12/2016
---

# Bitsadmin removeclientcertificate

>Applies To: Windows Server&reg; 2016, Windows Server&reg; 2012 R2, Windows Server&reg; 2012

Removes the client certificate from the job.

## Syntax

```
bitsadmin /RemoveClientCertificate <Job> 
```

## Parameters

|Parameter|Description|
|-------------|---------------|
|Job|The job's display name or GUID|

## <a name="BKMK_examples"></a>Examples
The following example removes the client certificate from the job named *myJob*.

```
C:\>Bitsadmin /RemoveClientCertificate myJob 
```

## Additional references
[Command-Line Syntax Key](Command-Line-Syntax-Key.md)

