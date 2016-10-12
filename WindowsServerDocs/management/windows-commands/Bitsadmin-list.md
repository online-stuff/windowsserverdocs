---
title: Bitsadmin list
description: "Windows Commands"
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.technology: manage-windows-commands
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 1416965e-e0e6-49cf-b1d4-b286d3cf8716
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/12/2016
---

# Bitsadmin list

>Applies To: Windows Server&reg; 2016, Windows Server&reg; 2012 R2, Windows Server&reg; 2012

Lists the transfer jobs owned by the current user.
## Syntax
```
bitsadmin /List [/allusers][/verbose]
```
## Parameters
|Parameter|Description|
|-------------|---------------|
|/Allusers|Optional—lists jobs for all users|
|/Verbose|Optional—provides detail information for each job.|
## Remarks
You must have administrator privileges to use the /allusers parameter
## <a name="BKMK_examples"></a>Examples
The following example retrieves information about jobs owned by the current user.
```
C:\>bitsadmin /List 
```
## Additional references
[Command-Line Syntax Key](Command-Line-Syntax-Key.md)