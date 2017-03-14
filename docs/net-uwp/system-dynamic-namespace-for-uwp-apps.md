---
title: "System.Dynamic namespace for UWP apps | Microsoft Docs"
ms.custom: ""
ms.date: "12/14/2016"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: c9db3f97-6589-4ff1-8cb2-86c7b0c10a9f
caps.latest.revision: 5
author: "msatranjr"
ms.author: "misatran"
manager: "markl"
---
# System.Dynamic namespace for UWP apps
The `System.Dynamic` namespace provides classes and interfaces that support the dynamic language runtime (DLR).  
  
 This topic displays the types in the `System.Dynamic` namespace that are included in .NET for UWP apps. Note that .NET for UWP apps does not include all the members of each type. For information about individual types, see the linked topics. The documentation for a type indicates which members are included in .NET for UWP apps.  
  
## System.Dynamic namespace  
  
|Types supported in .NET for UWP apps|Description|  
|------------------------------------------------------------------------------------------|-----------------|  
|<xref:System.Dynamic.BinaryOperationBinder>|Represents the binary dynamic operation at the call site, providing the binding semantic and the details about the operation.|  
|<xref:System.Dynamic.BindingRestrictions>|Represents a set of binding restrictions on the DynamicMetaObject under which the dynamic binding is valid.|  
|<xref:System.Dynamic.CallInfo>|Describes arguments in the dynamic binding process.|  
|<xref:System.Dynamic.ConvertBinder>|Represents the convert dynamic operation at the call site, providing the binding semantic and the details about the operation.|  
|<xref:System.Dynamic.CreateInstanceBinder>|Represents the dynamic create operation at the call site, providing the binding semantic and the details about the operation.|  
|<xref:System.Dynamic.DeleteIndexBinder>|Represents the dynamic delete index operation at the call site, providing the binding semantic and the details about the operation.|  
|<xref:System.Dynamic.DeleteMemberBinder>|Represents the dynamic delete member operation at the call site, providing the binding semantic and the details about the operation.|  
|<xref:System.Dynamic.DynamicMetaObject>|Represents the dynamic binding and a binding logic of an object participating in the dynamic binding.|  
|<xref:System.Dynamic.DynamicMetaObjectBinder>|Represents the dynamic call site binder that participates in the DynamicMetaObject binding protocol.|  
|<xref:System.Dynamic.DynamicObject>|Provides a base class for specifying dynamic behavior at run time. This class must be inherited from; you cannot instantiate it directly.|  
|<xref:System.Dynamic.ExpandoObject>|Represents an object whose members can be dynamically added and removed at run time.|  
|<xref:System.Dynamic.GetIndexBinder>|Represents the dynamic get index operation at the call site, providing the binding semantic and the details about the operation.|  
|<xref:System.Dynamic.GetMemberBinder>|Represents the dynamic get member operation at the call site, providing the binding semantic and the details about the operation.|  
|<xref:System.Dynamic.IDynamicMetaObjectProvider>|Represents a dynamic object, that can have its operations bound at runtime.|  
|<xref:System.Dynamic.IInvokeOnGetBinder>|Represents information about a dynamic get member operation that indicates if the get member should invoke properties when they perform the get operation.|  
|<xref:System.Dynamic.InvokeBinder>|Represents the invoke dynamic operation at the call site, providing the binding semantic and the details about the operation.|  
|<xref:System.Dynamic.InvokeMemberBinder>|Represents the invoke member dynamic operation at the call site, providing the binding semantic and the details about the operation.|  
|<xref:System.Dynamic.SetIndexBinder>|Represents the dynamic set index operation at the call site, providing the binding semantic and the details about the operation.|  
|<xref:System.Dynamic.SetMemberBinder>|Represents the dynamic set member operation at the call site, providing the binding semantic and the details about the operation.|  
|<xref:System.Dynamic.UnaryOperationBinder>|Represents the unary dynamic operation at the call site, providing the binding semantic and the details about the operation.|  
  
## See Also  
 [.NET for Windows apps](../net-uwp/dotnet-for-windows-apps.md)