---
UID: NN:wudfddi.IWDFFileHandleTargetFactory
title: IWDFFileHandleTargetFactory (wudfddi.h)
description: The IWDFFileHandleTargetFactory interface is a factory interface that is used to create a file-handle-based target device object.
old-location: wdf\iwdffilehandletargetfactory.htm
tech.root: wdf
ms.date: 02/26/2018
keywords: ["IWDFFileHandleTargetFactory interface"]
ms.keywords: IWDFFileHandleTargetFactory, IWDFFileHandleTargetFactory interface, IWDFFileHandleTargetFactory interface,described, UMDFDeviceObjectRef_01a7fcc5-c259-4bad-b44c-9a20eeae1751.xml, umdf.iwdffilehandletargetfactory, wdf.iwdffilehandletargetfactory, wudfddi/IWDFFileHandleTargetFactory
req.header: wudfddi.h
req.include-header: Wudfddi.h
req.target-type: Desktop
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 1.5
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: Unavailable in UMDF 2.0 and later.
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: WUDFx.dll
req.irql: 
targetos: Windows
req.typenames: 
f1_keywords:
 - IWDFFileHandleTargetFactory
 - wudfddi/IWDFFileHandleTargetFactory
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - WUDFx.dll
api_name:
 - IWDFFileHandleTargetFactory
---

# IWDFFileHandleTargetFactory interface


## -description

<p class="CCE_Message">[<b>Warning:</b> UMDF 2 is the latest version of UMDF and supersedes UMDF 1.  All new UMDF drivers should be written using UMDF 2.  No new features are being added to UMDF 1 and there is limited support for UMDF 1 on newer versions of Windows 10.  Universal Windows drivers must use UMDF 2.  For more info, see <a href="/windows-hardware/drivers/wdf/getting-started-with-umdf-version-2">Getting Started with UMDF</a>.]

The <b>IWDFFileHandleTargetFactory</b> interface is a factory interface that is used to create a file-handle-based target device object.

## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">IWDFFileHandleTargetFactory</b> interface inherits from the <a href="/windows/win32/api/unknwn/nn-unknwn-iunknown">IUnknown</a> interface. <b>IWDFFileHandleTargetFactory</b> also has these types of members:
<ul>
<li><a href="/">Methods</a></li>
</ul>

## -remarks

Drivers obtain the <b>IWDFFileHandleTargetFactory</b> interface by calling <b>IWDFDevice::QueryInterface</b>.
