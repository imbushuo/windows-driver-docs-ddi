---
UID: NN:printerextension.IPrinterQueue2
title: IPrinterQueue2 (printerextension.h)
description: Represents a single printer queue.
old-location: print\iprinterqueue2.htm
tech.root: print
ms.date: 04/20/2018
keywords: ["IPrinterQueue2 interface"]
ms.keywords: IPrinterQueue2, IPrinterQueue2 interface [Print Devices], IPrinterQueue2 interface [Print Devices],described, print.iprinterqueue2, printerextension/IPrinterQueue2
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
 - IPrinterQueue2
 - printerextension/IPrinterQueue2
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Printerextension.h
api_name:
 - IPrinterQueue2
---

# IPrinterQueue2 interface


## -description

Represents a single printer queue. 

This interface extends <a href="/windows-hardware/drivers/ddi/printerextension/nn-printerextension-iprinterqueue">IPrinterQueue</a> and allows a user to manage print jobs and device maintenance from within a UWP  device app for printers, or from a printer extension.

## -inheritance

The <b xmlns:loc="https://microsoft.com/wdcml/l10n">IPrinterQueue2</b> interface inherits from <a href="/windows-hardware/drivers/ddi/printerextension/nn-printerextension-iprinterqueue">IPrinterQueue</a>. <b>IPrinterQueue2</b> also has these types of members:
<ul>
<li><a href="/">Methods</a></li>
</ul>

## -remarks

<b>IPrinterQueue2</b> also helps to make it possible to perform device maintenance and job management from a UWP  device app or from a printer extension. For more information, see <a href="/windows-hardware/drivers/print/device-maintenance">Device Maintenance</a> and <a href="/windows-hardware/drivers/print/job-management">Job Management</a>.

## -see-also

<a href="/windows-hardware/drivers/print/device-maintenance">Device Maintenance</a>



<a href="/windows-hardware/drivers/ddi/printerextension/nn-printerextension-iprinterqueue">IPrinterQueue</a>



<a href="/windows-hardware/drivers/print/job-management">Job Management</a>
