---
UID: NF:iwstdec.IAMWstDecoder.GetDrawBackgroundMode
title: IAMWstDecoder::GetDrawBackgroundMode (iwstdec.h)
description: Downstream filters use the GetDrawBackgroundMode method to determine whether the caption text background is opaque or transparent.
helpviewer_keywords: ["GetDrawBackgroundMode","GetDrawBackgroundMode method [DirectShow]","GetDrawBackgroundMode method [DirectShow]","IAMWstDecoder interface","IAMWstDecoder interface [DirectShow]","GetDrawBackgroundMode method","IAMWstDecoder.GetDrawBackgroundMode","IAMWstDecoder::GetDrawBackgroundMode","IAMWstDecoderGetDrawBackgroundMode","dshow.iamwstdecoder_getdrawbackgroundmode","iwstdec/IAMWstDecoder::GetDrawBackgroundMode"]
old-location: dshow\iamwstdecoder_getdrawbackgroundmode.htm
tech.root: dshow
ms.assetid: c5bf3a83-5f74-4ef1-81b6-6c99e3832725
ms.date: 4/26/2023
ms.keywords: GetDrawBackgroundMode, GetDrawBackgroundMode method [DirectShow], GetDrawBackgroundMode method [DirectShow],IAMWstDecoder interface, IAMWstDecoder interface [DirectShow],GetDrawBackgroundMode method, IAMWstDecoder.GetDrawBackgroundMode, IAMWstDecoder::GetDrawBackgroundMode, IAMWstDecoderGetDrawBackgroundMode, dshow.iamwstdecoder_getdrawbackgroundmode, iwstdec/IAMWstDecoder::GetDrawBackgroundMode
req.header: iwstdec.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows XP [desktop apps only]
req.target-min-winversvr: Windows Server 2003 [desktop apps only]
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
 - IAMWstDecoder::GetDrawBackgroundMode
 - iwstdec/IAMWstDecoder::GetDrawBackgroundMode
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
 - IAMWstDecoder.GetDrawBackgroundMode
---

# IAMWstDecoder::GetDrawBackgroundMode


## -description

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

Downstream filters use the <code>GetDrawBackgroundMode</code> method to determine whether the caption text background is opaque or transparent.

## -parameters

### -param lpMode [out]

Receives a member of the <a href="/previous-versions/windows/desktop/api/iwstdec/ne-iwstdec-am_wst_drawbgmode">AM_WST_DRAWBGMODE</a> enumeration. This parameter receives one of the following values.

<table>
<tr>
<th>Value
                </th>
<th>Description
                </th>
</tr>
<tr>
<td>AM_WST_DRAWBGMODE_Opaque</td>
<td>Caption text background is opaque.</td>
</tr>
<tr>
<td>AM_WST_DRAWBGMODE_Transparent</td>
<td>Caption text background is transparent.</td>
</tr>
</table>

## -returns

When the method succeeds, it returns S_OK. Otherwise, it returns an <b>HRESULT</b> error code.

## -see-also

<a href="/windows/desktop/DirectShow/error-and-success-codes">Error and Success Codes</a>



<a href="/windows/desktop/api/iwstdec/nn-iwstdec-iamwstdecoder">IAMWstDecoder Interface</a>