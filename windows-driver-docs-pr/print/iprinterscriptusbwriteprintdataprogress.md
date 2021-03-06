---
title: IPrinterScriptUsbWritePrintDataProgress interface
author: windows-driver-content
description: The IPrinterScriptUsbWritePrintDataProgress interface is passed as a parameter in the writePrintData JavaScript function call.
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
ms.assetid: E22725DA-2BD5-4FBC-A3E4-A3C5678A9E57
keywords: ["IPrinterScriptUsbWritePrintDataProgress interface Print Devices", "IPrinterScriptUsbWritePrintDataProgress interface Print Devices , described"]
topic_type:
- apiref
api_name:
- IPrinterScriptUsbWritePrintDataProgress
api_type:
- COM
ms.localizationpriority: medium
---

# IPrinterScriptUsbWritePrintDataProgress interface


The IPrinterScriptUsbWritePrintDataProgress interface is passed as a parameter in the **writePrintData** JavaScript function call.

Members
-------

The **IPrinterScriptUsbWritePrintDataProgress** interface inherits from the [**IUnknown**](https://msdn.microsoft.com/library/windows/desktop/ms680509) interface. **IPrinterScriptUsbWritePrintDataProgress** also has these types of members:

-   [Methods](#methods)

### <span id="methods"></span>Methods

The **IPrinterScriptUsbWritePrintDataProgress** interface has these methods.

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Method</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>[<strong>ProcessedByteCount</strong>](iprinterscriptusbwriteprintdataprogress-processedbytecount.md)</td>
<td><p>Returns the number of bytes that the IHV JavaScript function has processed by the time this method was called.</p></td>
</tr>
<tr class="even">
<td>[<strong>ProcessedByteCount</strong>](iprinterscriptusbwriteprintdataprogress-processedbytecount-in.md)</td>
<td><p>Sets the number of bytes that the IHV JavaScript function has processed at the time this method was called.</p></td>
</tr>
</tbody>
</table>

 

 

 




