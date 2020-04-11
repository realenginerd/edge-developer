---
description: Host web content in your Win32 app with the Microsoft Edge WebView2 control
title: Microsoft Edge WebView2 for Win32 apps
author: MSEdgeTeam
ms.author: msedgedevrel
ms.date: 12/09/2019
ms.topic: reference
ms.prod: microsoft-edge
ms.technology: webview
keywords: IWebView2, IWebView2WebView, webview2, webview, win32 apps, win32, edge
---

# interface IWebView2ProcessFailedEventArgs 

> [!NOTE]
> This interface may be altered or unavailable for releases after SDK version 0.8.355. Please refer to [WebView2 API browser](../../../webview2-api-browser.md) for the latest API reference.

```
interface IWebView2ProcessFailedEventArgs
  : public IUnknown
```

Event args for the ProcessFailed event.

## Summary

 Members                        | Descriptions
--------------------------------|---------------------------------------------
[get_ProcessFailedKind](#get_processfailedkind) | The kind of process failure that has occurred.

## Members

#### get_ProcessFailedKind 

The kind of process failure that has occurred.

> public HRESULT [get_ProcessFailedKind](#get_processfailedkind)(WEBVIEW2_PROCESS_FAILED_KIND * processFailedKind)
