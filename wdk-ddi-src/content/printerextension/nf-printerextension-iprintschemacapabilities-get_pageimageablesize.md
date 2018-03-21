---
UID: NF:printerextension.IPrintSchemaCapabilities.get_PageImageableSize
title: IPrintSchemaCapabilities::get_PageImageableSize method
author: windows-driver-content
description: Gets the imageable area information of the printer.
old-location: print\iprintschemacapabilities_pageimageablesize.htm
old-project: print
ms.assetid: 5FA7613C-8714-481D-8439-9F3334D2E9E5
ms.author: windowsdriverdev
ms.date: 2/26/2018
ms.keywords: IPrintSchemaCapabilities, IPrintSchemaCapabilities interface [Print Devices], PageImageableSize property, IPrintSchemaCapabilities.PageImageableSize, IPrintSchemaCapabilities::get_PageImageableSize, PageImageableSize property [Print Devices], PageImageableSize property [Print Devices], IPrintSchemaCapabilities interface, get_PageImageableSize, get_PageImageableSize,IPrintSchemaCapabilities.get_PageImageableSize, print.iprintschemacapabilities_pageimageablesize, printerextension/IPrintSchemaCapabilities::PageImageableSize, printerextension/IPrintSchemaCapabilities::get_PageImageableSize
ms.prod: windows-hardware
ms.technology: windows-devices
ms.topic: method
req.header: printerextension.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 8
req.target-min-winversvr: Windows Server 2012
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
topic_type:
-	APIRef
-	kbSyntax
api_type:
-	COM
api_location:
-	Printerextension.h
api_name:
-	IPrintSchemaCapabilities.PageImageableSize
-	IPrintSchemaCapabilities.get_PageImageableSize
product: Windows
targetos: Windows
req.typenames: PrintSchemaSelectionType
req.product: Windows 10 or later.
---

# IPrintSchemaCapabilities::get_PageImageableSize method


## -description


Gets the imageable area information of the printer.

This property is read-only.


## -syntax


````
HRESULT get_PageImageableSize(
  [out, retval] IPrintSchemaPageImageableSize **ppPageImageableSize
);
````


## -parameters


## -see-also

<a href="..\printerextension\nn-printerextension-iprintschemapageimageablesize.md">IPrintSchemaPageImageableSize</a>



<a href="..\printerextension\nn-printerextension-iprintschemacapabilities.md">IPrintSchemaCapabilities</a>



 

 

