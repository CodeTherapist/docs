---
title: "CLRRuntimeHost Coclass"
ms.date: "03/30/2017"
api_name: 
  - "CLRRuntimeHost Coclass"
api_location: 
  - "mscoree.dll"
api_type: 
  - "COM"
f1_keywords: 
  - "CLRRuntimeHost"
helpviewer_keywords: 
  - "CLRRuntimeHost coclass [.NET Framework hosting]"
ms.assetid: 2ac9cbf5-8a2d-4e4f-8831-0dad8ef0a897
topic_type: 
  - "apiref"
author: "rpetrusha"
ms.author: "ronpet"
---
# CLRRuntimeHost Coclass
Provides interfaces for managing code execution by the runtime.  
  
## Syntax  
  
```  
coclass CLRRuntimeHost {  
    [default] interface  ICLRRuntimeHost;  
    interface            ICLRValidator;  
};  
```  
  
## Interfaces  
  
|Interface|Description|  
|---------------|-----------------|  
|[ICLRRuntimeHost Interface](../../../../docs/framework/unmanaged-api/hosting/iclrruntimehost-interface.md)|Provides methods for controlling the execution of applications by the runtime.|  
|[ICLRValidator Interface](../../../../docs/framework/unmanaged-api/hosting/iclrvalidator-interface.md)|Provides methods for validation of portable executable images and for detailed reporting of validation errors.|  
  
## Requirements  
 **Platforms:** See [System Requirements](../../../../docs/framework/get-started/system-requirements.md).  
  
 **Header:** MSCorEE.idl  
  
 **Library:** Included as a resource in MSCorEE.dll  
  
 **.NET Framework Versions:** [!INCLUDE[net_current_v20plus](../../../../includes/net-current-v20plus-md.md)]  
  
## See also
- [Hosting Coclasses](../../../../docs/framework/unmanaged-api/hosting/hosting-coclasses.md)
