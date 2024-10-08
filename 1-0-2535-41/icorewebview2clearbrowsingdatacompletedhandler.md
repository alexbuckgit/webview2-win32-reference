---
description: The caller implements this interface to receive the ClearBrowsingData result.
title: WebView2 Win32 C++ ICoreWebView2ClearBrowsingDataCompletedHandler
ms.date: 07/31/2024
keywords: IWebView2, IWebView2WebView, webview2, webview, win32 apps, win32, edge, ICoreWebView2, ICoreWebView2Controller, browser control, edge html, ICoreWebView2ClearBrowsingDataCompletedHandler
topic_type: 
- APIRef
api_name:
- ICoreWebView2ClearBrowsingDataCompletedHandler
- ICoreWebView2ClearBrowsingDataCompletedHandler.Invoke
api_type:
- COM
api_location:
- embeddedbrowserwebview.dll
---

# interface ICoreWebView2ClearBrowsingDataCompletedHandler

[!INCLUDE [deprecation-note](../includes/deprecation-note.md)]

```
interface ICoreWebView2ClearBrowsingDataCompletedHandler
  : public IUnknown
```

The caller implements this interface to receive the ClearBrowsingData result.

## Summary

 Members                        | Descriptions
--------------------------------|---------------------------------------------
[Invoke](#invoke) | Provide the completion status of the corresponding asynchronous method.

## Applies to

Product                         | Introduced
--------------------------------|---------------------------------------------
WebView2 Win32            |    1.0.1245.22
WebView2 Win32 Prerelease |    1.0.1248

## Members

#### Invoke

Provide the completion status of the corresponding asynchronous method.

> public HRESULT [Invoke](#invoke)(HRESULT errorCode)

