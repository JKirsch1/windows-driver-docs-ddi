<<<<<<< HEAD:wdk-ddi-src/content/nblhash/nf-nblhash-net_buffer_list_get_hash_value.md
---
UID: NF:nblhash.NET_BUFFER_LIST_GET_HASH_VALUE
title: NET_BUFFER_LIST_GET_HASH_VALUE
ms.date: 11/30/2020
ms.topic: language-reference
targetos: Windows
description: The NET_BUFFER_LIST_GET_HASH_VALUE macro gets the hash value information from a NET_BUFFER_LIST structure.
tech.root: netvista
req.assembly: 
req.construct-type: function
req.ddi-compliance: 
req.dll: 
req.header: ndis/nblhash.h
req.idl: 
req.include-header: ndis.h
req.irql: 
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.namespace: 
req.redist: 
req.target-min-winverclnt: Supported in NDIS 6.0 and later.
req.target-min-winversvr: 
req.target-type: Universal
req.type-library: 
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - nblhash.h
api_name:
 - NET_BUFFER_LIST_GET_HASH_VALUE
f1_keywords:
 - NET_BUFFER_LIST_GET_HASH_VALUE
 - nblhash/NET_BUFFER_LIST_GET_HASH_VALUE
dev_langs:
 - c++
---

# NET_BUFFER_LIST_GET_HASH_VALUE macro


## -description

The **NET_BUFFER_LIST_GET_HASH_VALUE** macro gets the hash value information from a [**NET_BUFFER_LIST**](../nbl/ns-nbl-net_buffer_list.md) structure.

## -parameters

### -param _NBL

A pointer to a **NET_BUFFER_LIST** structure.

## -returns

**NET_BUFFER_LIST_GET_HASH_VALUE** returns the hash value formatted as a ULONG.

## -remarks

For more information about the hash value, see [RSS Hashing Functions](/windows-hardware/drivers/network/rss-hashing-functions).

## -see-also

[**NET_BUFFER_LIST**](../nbl/ns-nbl-net_buffer_list.md)
=======
---
UID: NF:ndis.NET_BUFFER_LIST_GET_HASH_VALUE
title: NET_BUFFER_LIST_GET_HASH_VALUE macro (ndis.h)
description: The NET_BUFFER_LIST_GET_HASH_VALUE macro gets the hash value information from a NET_BUFFER_LIST structure.
tech.root: netvista
ms.date: 04/13/2018
keywords: ["NET_BUFFER_LIST_GET_HASH_VALUE macro"]
ms.keywords: NET_BUFFER_LIST_GET_HASH_VALUE
req.header: ndis.h
req.include-header: 
req.target-type: Universal
req.target-min-winverclnt: Supported in NDIS 6.0 and later.
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.lib: 
req.dll: 
req.irql: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
targetos: Windows
f1_keywords:
 - NET_BUFFER_LIST_GET_HASH_VALUE
 - ndis/NET_BUFFER_LIST_GET_HASH_VALUE
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - ndis.h
api_name:
 - NET_BUFFER_LIST_GET_HASH_VALUE
---

# NET_BUFFER_LIST_GET_HASH_VALUE macro


## -description

The **NET_BUFFER_LIST_GET_HASH_VALUE** macro gets the hash value information from a [**NET_BUFFER_LIST**](ns-ndis-_net_buffer_list.md) structure.

## -parameters

### -param _NBL

A pointer to a **NET_BUFFER_LIST** structure.

## -returns

**NET_BUFFER_LIST_GET_HASH_VALUE** returns the hash value formatted as a ULONG.

## -remarks

For more information about the hash value, see [RSS Hashing Functions](/windows-hardware/drivers/network/rss-hashing-functions).

## -see-also

[**NET_BUFFER_LIST**](ns-ndis-_net_buffer_list.md)
>>>>>>> release-iron:wdk-ddi-src/content/ndis/nf-ndis-net_buffer_list_get_hash_value.md