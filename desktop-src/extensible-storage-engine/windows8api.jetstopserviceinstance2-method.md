---
title: Windows8Api.JetStopServiceInstance2 method  (Microsoft.Isam.Esent.Interop.Windows8)
TOCTitle: 'JetStopServiceInstance2 method '
ms:assetid: M:Microsoft.Isam.Esent.Interop.Windows8.Windows8Api.JetStopServiceInstance2(Microsoft.Isam.Esent.Interop.JET_INSTANCE,Microsoft.Isam.Esent.Interop.Windows8.StopServiceGrbit)
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.isam.esent.interop.windows8.windows8api.jetstopserviceinstance2(v=EXCHG.10)
ms:contentKeyID: 55104460
ms.date: 07/30/2014
ms.topic: article
f1_keywords:
- Microsoft.Isam.Esent.Interop.Windows8.Windows8Api.JetStopServiceInstance2
dev_langs:
- CSharp
- JScript
- VB
- other
api_name: 
- Microsoft.Isam.Esent.Interop.Windows8.Windows8Api.JetStopServiceInstance2
topic_type: 
- apiref
- kbSyntax
api_type: 
- Managed
api_location: 
- Microsoft.Isam.Esent.Interop.dll
ROBOTS: INDEX,FOLLOW

---

# Windows8Api.JetStopServiceInstance2 method

Prepares an instance for termination. Can also be used to resume a previous quiescing.

**Namespace:**  [Microsoft.Isam.Esent.Interop.Windows8](dn335439\(v=exchg.10\).md)  
**Assembly:**  Microsoft.Isam.Esent.Interop (in Microsoft.Isam.Esent.Interop.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub JetStopServiceInstance2 ( _
    instance As JET_INSTANCE, _
    grbit As StopServiceGrbit _
)
'Usage
Dim instance As JET_INSTANCE
Dim grbit As StopServiceGrbitWindows8Api.JetStopServiceInstance2(instance, _
    grbit)
```

``` csharp
public static void JetStopServiceInstance2(
    JET_INSTANCE instance,
    StopServiceGrbit grbit
)
```

#### Parameters

  - instance  
    Type: [Microsoft.Isam.Esent.Interop.JET_INSTANCE](hh564593\(v=exchg.10\).md)  
    
    The (running) instance to use.

<!-- end list -->

  - grbit  
    Type: [Microsoft.Isam.Esent.Interop.Windows8.StopServiceGrbit](dn335370\(v=exchg.10\).md)  
    
    The options to stop or resume the instance.

## See also

#### Reference

[Windows8Api class](dn335490\(v=exchg.10\).md)

[Windows8Api members](dn335373\(v=exchg.10\).md)

[Microsoft.Isam.Esent.Interop.Windows8 namespace](dn335439\(v=exchg.10\).md)

