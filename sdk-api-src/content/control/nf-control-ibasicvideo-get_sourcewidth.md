---
UID: NF:control.IBasicVideo.get_SourceWidth
title: IBasicVideo::get_SourceWidth (control.h)
description: The get_SourceWidth method retrieves the width of the source rectangle.
helpviewer_keywords: ["IBasicVideo interface [DirectShow]","get_SourceWidth method","IBasicVideo.get_SourceWidth","IBasicVideo::get_SourceWidth","IBasicVideoget_SourceWidth","control/IBasicVideo::get_SourceWidth","dshow.ibasicvideo_get_sourcewidth","get_SourceWidth","get_SourceWidth method [DirectShow]","get_SourceWidth method [DirectShow]","IBasicVideo interface"]
old-location: dshow\ibasicvideo_get_sourcewidth.htm
tech.root: dshow
ms.assetid: 6c6f7e01-5f93-4277-b664-c5be0ea42004
ms.date: 4/26/2023
ms.keywords: IBasicVideo interface [DirectShow],get_SourceWidth method, IBasicVideo.get_SourceWidth, IBasicVideo::get_SourceWidth, IBasicVideoget_SourceWidth, control/IBasicVideo::get_SourceWidth, dshow.ibasicvideo_get_sourcewidth, get_SourceWidth, get_SourceWidth method [DirectShow], get_SourceWidth method [DirectShow],IBasicVideo interface
req.header: control.h
req.include-header: Dshow.h
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
 - IBasicVideo::get_SourceWidth
 - control/IBasicVideo::get_SourceWidth
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
 - IBasicVideo.get_SourceWidth
---

# IBasicVideo::get_SourceWidth


## -description

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

The <code>get_SourceWidth</code> method retrieves the width of the source rectangle.

## -parameters

### -param pSourceWidth [out]

Pointer to a variable that receives the width, in pixels.

## -returns

Returns an <b>HRESULT</b> value.

## -see-also

<a href="/windows/desktop/DirectShow/error-and-success-codes">Error and Success Codes</a>



<a href="/windows/desktop/api/control/nn-control-ibasicvideo">IBasicVideo Interface</a>