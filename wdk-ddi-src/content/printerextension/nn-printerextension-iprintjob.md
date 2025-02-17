---
UID: NN:printerextension.IPrintJob
title: IPrintJob (printerextension.h)
description: Contains properties that represent a print job.
old-location: print\iprintjob.htm
tech.root: print
ms.date: 04/20/2018
keywords: ["IPrintJob interface"]
ms.keywords: IPrintJob, IPrintJob interface [Print Devices], IPrintJob interface [Print Devices],described, print.iprintjob, printerextension/IPrintJob
req.header: printerextension.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 8.1
req.target-min-winversvr: Windows Server 2012 R2
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
f1_keywords:
 - IPrintJob
 - printerextension/IPrintJob
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Printerextension.h
api_name:
 - IPrintJob
---

# IPrintJob interface


## -description

Contains properties that represent a print job.

This interface also provides a method that allows a print job to be cancelled.

## -inheritance

The <b xmlns:loc="https://microsoft.com/wdcml/l10n">IPrintJob</b> interface inherits from the <a href="/windows/win32/api/unknwn/nn-unknwn-iunknown">IUnknown</a> interface. <b>IPrintJob</b> also has these types of members:
<ul>
<li><a href="/">Methods</a></li>
<li><a href="/">Properties</a></li>
</ul>

## -remarks

The <b>IPrintJob</b> interface provides a wrapper around select properties of the spooler’s <a href="/windows/win32/printdocs/job-info-1">JOB_INFO_1</a> structure.

<b>IPrintJob</b> also helps to make it possible to perform job management from a UWP device app or from a printer extension. For more information, see <a href="/windows-hardware/drivers/print/job-management">Job Management</a>.

## -see-also

<a href="/windows/win32/printdocs/job-info-1">JOB_INFO_1</a>



<a href="/windows-hardware/drivers/print/job-management">Job Management</a>
