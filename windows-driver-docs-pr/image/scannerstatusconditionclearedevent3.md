---
title: ScannerStatusConditionClearedEvent
description: ScannerStatusConditionClearedEvent
ms.assetid: fa8c44d0-21aa-401c-a45b-9a8be4766378
keywords: ["ScannerStatusConditionClearedEvent"]
ms.author: windowsdriverdev
ms.date: 11/28/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
---

# ScannerStatusConditionClearedEvent


The scanner sends the **ScannerStatusConditionClearedEvent** event to the control point when a previously reported **DeviceCondition** has been cleared. The body of the **ScannerStatusConditionClearedEvent** element consists of the **DeviceConditonId** element for the condition that has been cleared and the **ConditionClearTime** element that specifies when the condition was cleared.

The **ScannerStatusConditionClearedEvent** element supports the following sub-element:

[ScannerStatusConditionClearedEvent.DeviceConditonCleared](scannerstatusconditionclearedevent-deviceconditoncleared.md)

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bimage\image%5D:%20ScannerStatusConditionClearedEvent%20%20RELEASE:%20%2811/8/2017%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")




