---
title: "ICorProfilerCallback::ExceptionOSHandlerEnter Method | Microsoft Docs"
ms.custom: ""
ms.date: "03/30/2017"
ms.prod: ".net-framework-4.6"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "dotnet-clr"
ms.tgt_pltfrm: ""
ms.topic: "reference"
apiname: 
  - "ICorProfilerCallback.ExceptionOSHandlerEnter"
apilocation: 
  - "mscorwks.dll"
apitype: "COM"
f1_keywords: 
  - "ICorProfilerCallback::ExceptionOSHandlerEnter"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "ExceptionOSHandlerEnter method [.NET Framework profiling]"
  - "ICorProfilerCallback::ExceptionOSHandlerEnter method [.NET Framework profiling]"
ms.assetid: 09238b9b-9359-4780-89dc-2f5e4f57920e
caps.latest.revision: 11
author: "mairaw"
ms.author: "mairaw"
manager: "wpickett"
---
# ICorProfilerCallback::ExceptionOSHandlerEnter Method
Not implemented. A profiler that needs unmanaged exception information must obtain this information through other means.  
  
## Syntax  
  
```  
HRESULT ExceptionOSHandlerEnter(  
    [in] UINT_PTR __unused);  
```  
  
## Requirements  
 **Platforms:** See [System Requirements](../../../../docs/framework/get-started/system-requirements.md).  
  
 **Header:** CorProf.idl, CorProf.h  
  
 **Library:** CorGuids.lib  
  
 **.NET Framework Versions:** [!INCLUDE[net_current_v20plus](../../../../includes/net-current-v20plus-md.md)]  
  
## See Also  
 [ICorProfilerCallback Interface](../../../../docs/framework/unmanaged-api/profiling/icorprofilercallback-interface.md)