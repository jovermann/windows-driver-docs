---
title: Pedometer data fields
description: This topic provides information about the data fields that are specific to the pedometer.
ms.assetid: 35E52085-9727-465D-B6EF-D95974423CD5
ms.author: windowsdriverdev
ms.date: 01/04/2018
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
---

# Pedometer data fields


This topic provides information about the data fields that are specific to the pedometer.

The following table shows the data fields. For more information about the data types shown in the **Type** column, see [MSDN PROPVARIANT structure](http://go.microsoft.com/fwlink/p/?linkid=313395).

<table>
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th>Property key</th>
<th>Type</th>
<th>Required/Optional</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>PKEY_SensorData_PedometerStepType</p></td>
<td><p>VT_UI4</p></td>
<td><p>Required</p></td>
<td><p>The step type, expressed as a [<strong>PEDOMETER_STEP_TYPE</strong>](https://msdn.microsoft.com/library/windows/hardware/dn957077) value.</p></td>
</tr>
<tr class="even">
<td><p>PKEY_SensorData_PedometerStepCount</p></td>
<td><p>VT_UI4</p></td>
<td><p>Required</p></td>
<td><p>The number of steps detected.</p></td>
</tr>
<tr class="odd">
<td><p>PKEY_SensorData_PedometerStepDuration_Ms</p></td>
<td><p>VT_I8</p></td>
<td><p>Required</p></td>
<td><p>The duration over which the pedometer counted steps. This value is expressed in milliseconds.</p></td>
</tr>
<tr class="even">
<td><p>PKEY_SensorData_PedometerReset</p></td>
<td><p>VT_BOOL</p></td>
<td><p>Required</p></td>
<td><p>Indicates that the pedometer has been reset.</p></td>
</tr>
</tbody>
</table>

 

## <span id="related_topics"></span>Related topics


[MSDN PROPVARIANT structure](http://go.microsoft.com/fwlink/p/?linkid=313395)

[**PEDOMETER\_STEP\_TYPE**](https://msdn.microsoft.com/library/windows/hardware/dn957077)

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bsensors\sensors%5D:%20Pedometer%20data%20fields%20%20RELEASE:%20%2811/18/2017%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")





