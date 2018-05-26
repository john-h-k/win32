---
title: TBM\_GETTOOLTIPS message
description: Retrieves the handle to the tooltip control assigned to the trackbar, if any.
ms.assetid: 30efef12-1aec-4635-94a7-1843db404c4f
keywords:
- TBM_GETTOOLTIPS message Windows Controls
topic_type:
- apiref
api_name:
- TBM_GETTOOLTIPS
api_location:
- Commctrl.h
api_type:
- HeaderDef
ms.date: 05/31/2018
ms.topic: article
ms.author: windowssdkdev
ms.prod: windows
ms.technology: desktop
---

# TBM\_GETTOOLTIPS message

Retrieves the handle to the tooltip control assigned to the trackbar, if any.

## Parameters

<dl> <dt>

*wParam* 
</dt> <dd>Must be zero.</dd> <dt>

*lParam* 
</dt> <dd>Must be zero.</dd> </dl>

## Return value

Returns the handle to the tooltip control assigned to the trackbar, or **NULL** if tooltips are not in use. If the trackbar control does not use the [**TBS\_TOOLTIPS**](trackbar-control-styles.md#tbs-tooltips) style, the return value is **NULL**.

## Requirements



|                                     |                                                                                       |
|-------------------------------------|---------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows Vista \[desktop apps only\]<br/>                                        |
| Minimum supported server<br/> | Windows Server 2003 \[desktop apps only\]<br/>                                  |
| Header<br/>                   | <dl> <dt>Commctrl.h</dt> </dl> |



 

 




