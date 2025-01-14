---
UID: NF:mpconfig.IMixerPinConfig.SetStreamTransparent
title: IMixerPinConfig::SetStreamTransparent (mpconfig.h)
description: The SetStreamTransparent method sets the stream to transparent.
helpviewer_keywords: ["IMixerPinConfig interface [DirectShow]","SetStreamTransparent method","IMixerPinConfig.SetStreamTransparent","IMixerPinConfig::SetStreamTransparent","IMixerPinConfigSetStreamTransparent","SetStreamTransparent","SetStreamTransparent method [DirectShow]","SetStreamTransparent method [DirectShow]","IMixerPinConfig interface","dshow.imixerpinconfig_setstreamtransparent","mpconfig/IMixerPinConfig::SetStreamTransparent"]
old-location: dshow\imixerpinconfig_setstreamtransparent.htm
tech.root: dshow
ms.assetid: d1f60a35-ffef-4ebb-b331-558772310bcb
ms.date: 4/26/2023
ms.keywords: IMixerPinConfig interface [DirectShow],SetStreamTransparent method, IMixerPinConfig.SetStreamTransparent, IMixerPinConfig::SetStreamTransparent, IMixerPinConfigSetStreamTransparent, SetStreamTransparent, SetStreamTransparent method [DirectShow], SetStreamTransparent method [DirectShow],IMixerPinConfig interface, dshow.imixerpinconfig_setstreamtransparent, mpconfig/IMixerPinConfig::SetStreamTransparent
req.header: mpconfig.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps only]
req.target-min-winversvr: Windows 2000 Server [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Strmiids.lib
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - IMixerPinConfig::SetStreamTransparent
 - mpconfig/IMixerPinConfig::SetStreamTransparent
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Strmiids.lib
 - Strmiids.dll
api_name:
 - IMixerPinConfig.SetStreamTransparent
---

# IMixerPinConfig::SetStreamTransparent


## -description

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

The <code>SetStreamTransparent</code> method sets the stream to transparent.

## -parameters

### -param bStreamTransparent [in]

Value specifying the transparency of the stream. Pass in <b>TRUE</b> to indicate stream is transparent; <b>FALSE</b> to indicate not a transparent stream.

## -returns

Returns an <b>HRESULT</b> value.

## -see-also

<a href="/windows/desktop/DirectShow/error-and-success-codes">Error and Success Codes</a>



<a href="/windows/desktop/api/mpconfig/nn-mpconfig-imixerpinconfig">IMixerPinConfig Interface</a>



<a href="/windows/desktop/api/mpconfig/nf-mpconfig-imixerpinconfig-getstreamtransparent">IMixerPinConfig::GetStreamTransparent</a>