---
title: BDA Node Category GUIDs
description: BDA Node Category GUIDs
ms.assetid: cf439881-d20d-4efc-8ea3-3752e117b14d
ms.author: windowsdriverdev
ms.date: 11/28/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
---

# BDA Node Category GUIDs


## <span id="ddk_bda_node_category_guids_ks"></span><span id="DDK_BDA_NODE_CATEGORY_GUIDS_KS"></span>


A BDA minidriver uses the BDA node category GUIDs to specify the types of BDA nodes that are available to create. A BDA minidriver assigns one of these GUIDs in the variable to which the **Type** member of a [**KSNODE\_DESCRIPTOR**](https://msdn.microsoft.com/library/windows/hardware/ff563473) structure points. The *Bdamedia.h* header file defines these GUIDs.

The network provider uses the KSPROPERTY\_BDA\_NODE\_TYPES property of the [KSPROPSETID\_BdaTopology](kspropsetid-bdatopology.md) property set to retrieve a list of nodes types available from the BDA minidriver. This list of node types is an array of KSNODE\_DESCRIPTOR structures.

The following node category GUIDs are available in BDA:

<span id="KSNODE_BDA_RF_TUNER"></span><span id="ksnode_bda_rf_tuner"></span>KSNODE\_BDA\_RF\_TUNER  
A BDA minidriver assigns this GUID to specify a BDA radio frequency tuner node for cable, satellite, or terrestrial broadcast.

<span id="KSNODE_BDA_ANALOG_DEMODULATOR"></span><span id="ksnode_bda_analog_demodulator"></span>KSNODE\_BDA\_ANALOG\_DEMODULATOR  
A BDA minidriver assigns this GUID to specify a BDA analog-type demodulator node.

<span id="KSNODE_BDA_QAM_DEMODULATOR"></span><span id="ksnode_bda_qam_demodulator"></span>KSNODE\_BDA\_QAM\_DEMODULATOR  
A BDA minidriver assigns this GUID to specify a BDA QAM-type demodulator node for Digital Video Broadcast (DVB)-cable demodulators.

<span id="KSNODE_BDA_QPSK_DEMODULATOR"></span><span id="ksnode_bda_qpsk_demodulator"></span>KSNODE\_BDA\_QPSK\_DEMODULATOR  
A BDA minidriver assigns this GUID to specify a BDA QPSK-type demodulator node for DVB-satellite demodulators.

<span id="KSNODE_BDA_8VSB_DEMODULATOR"></span><span id="ksnode_bda_8vsb_demodulator"></span>KSNODE\_BDA\_8VSB\_DEMODULATOR  
A BDA minidriver assigns this GUID to specify a BDA 8VSB-type demodulator node for Advanced Television Systems Committee (ATSC)-terrestrial demodulators.

<span id="KSNODE_BDA_COFDM_DEMODULATOR"></span><span id="ksnode_bda_cofdm_demodulator"></span>KSNODE\_BDA\_COFDM\_DEMODULATOR  
A BDA minidriver assigns this GUID to specify a BDA COFDM-type demodulator node for DVB-terrestrial demodulators.

<span id="KSNODE_BDA_OPENCABLE_POD"></span><span id="ksnode_bda_opencable_pod"></span>KSNODE\_BDA\_OPENCABLE\_POD  
A BDA minidriver assigns this GUID to specify a BDA open-cable POD node.

<span id="KSNODE_BDA_COMMON_CA_POD"></span><span id="ksnode_bda_common_ca_pod"></span>KSNODE\_BDA\_COMMON\_CA\_POD  
A BDA minidriver assigns this GUID to specify a BDA common conditional access POD node.

<span id="KSNODE_BDA_PID_FILTER"></span><span id="ksnode_bda_pid_filter"></span>KSNODE\_BDA\_PID\_FILTER  
A BDA minidriver assigns this GUID to specify a BDA packet identifier (PID) filter node.

<span id="KSNODE_BDA_IP_SINK"></span><span id="ksnode_bda_ip_sink"></span>KSNODE\_BDA\_IP\_SINK  
A BDA minidriver assigns this GUID to specify a BDA IP sink node.

<span id="KSNODE_BDA_ISDB_T_DEMODULATOR"></span><span id="ksnode_bda_isdb_t_demodulator"></span>KSNODE\_BDA\_ISDB\_T\_DEMODULATOR  
A BDA minidriver assigns this GUID to specify a BDA ISDB-type demodulator node for DVB-terrestrial demodulators.

<span id="KSNODE_BDA_ISDB_S_DEMODULATOR"></span><span id="ksnode_bda_isdb_s_demodulator"></span>KSNODE\_BDA\_ISDB\_S\_DEMODULATOR  
A BDA minidriver assigns this GUID to specify a BDA ISDB-type demodulator node for DVB-satellite demodulators.

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bstream\stream%5D:%20BDA%20Node%20Category%20GUIDs%20%20RELEASE:%20%2811/22/2017%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")




