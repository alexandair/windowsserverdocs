---
title: extract
description: "Windows Commands topic for **** - "
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.technology: manage-windows-commands
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 20dab03e-f6e1-4eb8-b8a1-fd6f1d97ee83
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/12/2016
---
# extract

>Applies To: Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

## Syntax
```
extract [/Y] [/A] [/D | /E] [/L dir] cabinet [filename ...]
extract [/Y] source [newname]
extract [/Y] /C source destination
```
## Parameters
|Parameter|Description|
|-------|--------|
|cabinet|File contains two or more files.|
|filename|Name of the file to extract from the cabinet. Wild cards and multiple filenames (separated by blanks) may be used.|
|source|compressed file (a cabinet with only one file).|
|newname|New filename to give the extracted file. If not supplied, the original name is used.|
|/A|Process ALL cabinets. Follows cabinet chain starting in first cabinet mentioned.|
|/C|copy source file to destination (to copy from DMF disks).|
|/D|Display cabinet directory (use with filename to avoid extract).|
|/E|extract (use instead of *.\* to extract all files).|
|/L dir|Location to place extracted files (default is current directory).|
|/Y|Do not prompt before overwriting an existing file.|
#### additional references
[Command-Line Syntax Key](command-line-syntax-key.md)
