---
title: "JsonObject.Contains(Text) Method"
description: "Verifies if a JsonObject contains a property with a given key."
ms.author: solsen
ms.date: 08/26/2024
ms.topic: reference
author: SusanneWindfeldPedersen
ms.reviewer: solsen
---
[//]: # (START>DO_NOT_EDIT)
[//]: # (IMPORTANT:Do not edit any of the content between here and the END>DO_NOT_EDIT.)
[//]: # (Any modifications should be made in the .xml files in the ModernDev repo.)
# JsonObject.Contains(Text) Method
> **Version**: _Available or changed with runtime version 1.0._

Verifies if a JsonObject contains a property with a given key.


## Syntax
```AL
Ok :=   JsonObject.Contains(Key: Text)
```
## Parameters
*JsonObject*  
&emsp;Type: [JsonObject](jsonobject-data-type.md)  
An instance of the [JsonObject](jsonobject-data-type.md) data type.  

*Key*  
&emsp;Type: [Text](../text/text-data-type.md)  
  


## Return Value
*Ok*  
&emsp;Type: [Boolean](../boolean/boolean-data-type.md)  
**true** if the object contains a property with the given key; otherwise, **false**.


[//]: # (IMPORTANT: END>DO_NOT_EDIT)
## Related information
[JsonObject Data Type](jsonobject-data-type.md)  
[Get Started with AL](../../devenv-get-started.md)  
[Developing Extensions](../../devenv-dev-overview.md)