---
UID: NN:portabledevicetypes.IPortableDeviceValues
title: IPortableDeviceValues (portabledevicetypes.h)
description: The IPortableDeviceValues interface holds a collection of PROPERTYKEY/PROPVARIANT pairs.
old-location: wpddk\iportabledevicevalues.htm
tech.root: wpd_dk
ms.date: 02/15/2018
keywords: ["IPortableDeviceValues interface"]
ms.keywords: IPortableDeviceValues, IPortableDeviceValues interface, IPortableDeviceValues interface,described, IPortableDeviceValuesInterface, portabledevicetypes/IPortableDeviceValues, wpddk.iportabledevicevalues
req.header: portabledevicetypes.h
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
ms.custom: RS5
f1_keywords:
 - IPortableDeviceValues
 - portabledevicetypes/IPortableDeviceValues
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - PortableDeviceTypes.h
api_name:
 - IPortableDeviceValues
---

# IPortableDeviceValues interface


## -description

The <b>IPortableDeviceValues</b> interface holds a collection of <b>PROPERTYKEY</b>/<b>PROPVARIANT</b> pairs. Values in the collection do not need to be all the same <b>VARTYPE</b>. Values are stored as key-value pairs; each key must be unique in the collection. Clients can search for items by <b>PROPERTYKEY</b> or zero-based index. Data values are stored as <b>PROPVARIANT</b> structures. You can add or retrieve values of any type by using the generic methods <b>SetValue</b> and <b>GetValue</b>, or you add items by using the method specific to the type of data added.

The Get... methods require the caller to release any retrieved values appropriately. The Set... methods copy the value into the collection.

When an IPortableDeviceValues interface is released, it calls Clear, which frees the memory that was allocated for all its members appropriately

This interface can be retrieved from a method or, if a new object is required, call CoCreate with CLSID_PortableDeviceValues.

## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">IPortableDeviceValues</b> interface inherits from the <a href="/windows/win32/api/unknwn/nn-unknwn-iunknown">IUnknown</a> interface. <b>IPortableDeviceValues</b> also has these types of members:
<ul>
<li><a href="/">Methods</a></li>
</ul>

## -see-also

<a href="/previous-versions/windows/hardware/drivers/ff597553(v=vs.85)">Collection Interfaces</a>
