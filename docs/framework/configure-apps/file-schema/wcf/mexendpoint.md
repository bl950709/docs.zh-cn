---
title: <mexEndpoint>
ms.date: 03/30/2017
ms.assetid: c9823060-0a5d-4f9d-99d4-4d113b758247
ms.openlocfilehash: e8f0e0fa2ea1606bf980fd6fa1fcd47f12c3b540
ms.sourcegitcommit: 5b475c1855b32cf78d2d1bbb4295e4c236f39464
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/24/2020
ms.locfileid: "91204744"
---
# \<mexEndpoint>

此配置元素定义具有固定 IMetadataExchange 协定的标准终结点。 由于所有元数据交换终结点都指定 IMetadataExchange 作为其协定，因此可以使用此标准终结点，而不必定义您自己的终结点。  
  
[**\<configuration>**](../configuration-element.md)\
&nbsp;&nbsp;[**\<system.serviceModel>**](system-servicemodel.md)\
&nbsp;&nbsp;&nbsp;&nbsp;[**\<standardEndpoints>**](standardendpoints.md)\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**\<mexEndpoint>**  
  
## <a name="syntax"></a>语法  
  
```xml  
<system.serviceModel>
  <standardEndpoints>
    <mexEndpoint>
      <standardEndpoint name="String" />
    </mexEndpoint>
  </standardEndpoints>
</system.serviceModel>
```  
  
## <a name="attributes-and-elements"></a>特性和元素  

 下列各节描述了特性、子元素和父元素。  
  
### <a name="attributes"></a>特性  
  
|属性|说明|  
|---------------|-----------------|  
|name|一个字符串，指定标准终结点的配置的名称。 此名称在服务终结点的 `endpointConfiguration` 特性中用于将标准终结点链接到其配置。|  
  
### <a name="child-elements"></a>子元素  

 无。  
  
### <a name="parent-elements"></a>父元素  
  
|元素|描述|  
|-------------|-----------------|  
|[\<standardEndpoints>](standardendpoints.md)|具有一个或多个固定属性（地址、绑定和协定）的预定义终结点的标准终结点集合。|
