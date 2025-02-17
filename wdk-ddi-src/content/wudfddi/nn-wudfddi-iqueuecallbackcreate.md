---
UID: NN:wudfddi.IQueueCallbackCreate
title: IQueueCallbackCreate (wudfddi.h)
description: An I/O queue notifies a driver when an open file request is available for the driver.
old-location: wdf\iqueuecallbackcreate.htm
tech.root: wdf
ms.date: 02/26/2018
keywords: ["IQueueCallbackCreate interface"]
ms.keywords: IQueueCallbackCreate, IQueueCallbackCreate interface, IQueueCallbackCreate interface,described, UMDFQueueObjectRef_dfb85326-329e-4d5b-9889-1894c53e4cb7.xml, umdf.iqueuecallbackcreate, wdf.iqueuecallbackcreate, wudfddi/IQueueCallbackCreate
req.header: wudfddi.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
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
 - IQueueCallbackCreate
 - wudfddi/IQueueCallbackCreate
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - wudfddi.h
api_name:
 - IQueueCallbackCreate
---

# IQueueCallbackCreate interface


## -description

<p class="CCE_Message">[<b>Warning:</b> UMDF 2 is the latest version of UMDF and supersedes UMDF 1.  All new UMDF drivers should be written using UMDF 2.  No new features are being added to UMDF 1 and there is limited support for UMDF 1 on newer versions of Windows 10.  Universal Windows drivers must use UMDF 2.  For more info, see <a href="/windows-hardware/drivers/wdf/getting-started-with-umdf-version-2">Getting Started with UMDF</a>.]

An I/O queue notifies a driver when an open file request is available for the driver. The I/O queue notifies the driver in response to an application calling the Microsoft Win32 <b>CreateFile</b> function. The driver can handle the notification by registering the <b>IQueueCallbackCreate</b> interface.

## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">IQueueCallbackCreate</b> interface inherits from the <a href="/windows/win32/api/unknwn/nn-unknwn-iunknown">IUnknown</a> interface. <b>IQueueCallbackCreate</b> also has these types of members:
<ul>
<li><a href="/">Methods</a></li>
</ul>

## -remarks

A driver registers the <b>IQueueCallbackCreate</b> interface when it calls the <a href="/windows-hardware/drivers/ddi/wudfddi/nf-wudfddi-iwdfdevice-createioqueue">IWDFDevice::CreateIoQueue</a> method to create an I/O queue or to configure the default I/O queue. For more information about creating or configuring an I/O queue, see <a href="/windows-hardware/drivers/wdf/configuring-dispatch-mode-for-an-i-o-queue">Configuring Dispatch Mode for an I/O Queue</a>.
