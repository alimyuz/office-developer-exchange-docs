---
title: "GetAppManifestsResponseMessage"
 
 
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
ms.assetid: 815908f1-4223-42d8-92dc-f8bdfc6b5df8
description: "The GetAppManifestsResponseMessage element specifies the response message for a GetAppManifests request."
---

# GetAppManifestsResponseMessage

The **GetAppManifestsResponseMessage** element specifies the response message for a **GetAppManifests** request. 
  
```XML
<GetAppManifestsResponseMessage ResponseClass=" Success | Warning | Error ">
    <MessageText/>
    <ResponseCode/>
    <DescriptiveLinkKey/>
    <MessageXml/>
</GetAppManifestsResponseMessage>
```

 **ResponseMessageType**
## Attributes and elements

The following sections describe attributes, child elements, and parent elements.
  
### Attributes

|**Attribute**|**Description**|
|:-----|:-----|
|ResponseClass  <br/> |Indicates the class of the response.  <br/> |
   
#### ResponseClass

|**Value**|**Description**|
|:-----|:-----|
|Success  <br/> |Indicates success.  <br/> |
|Warning  <br/> |Indicates a warning.  <br/> |
|Error  <br/> |Indicates an error.  <br/> |
   
### Child elements

|**Element**|**Description**|
|:-----|:-----|
|[DescriptiveLinkKey](descriptivelinkkey.md) <br/> |Currently unused and reserved for future use.  <br/> |
|[MessageText](messagetext.md) <br/> |Provides a text description of the status of the response.  <br/> |
|[MessageXml](messagexml.md) <br/> |Provides additional error response information.  <br/> |
|[ResponseCode](responsecode.md) <br/> |Provides status information about the request.  <br/> |
   
### Parent elements

|**Element**|**Description**|
|:-----|:-----|
|[ResponseMessages](responsemessages.md) <br/> |Contains the response messages for an Exchange Web Services request.  <br/> |
   
## Remarks

This element was introduced in Exchange Server 2013.
  
The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.
  
## Element information

|**Name**|**Value**|
|:-----|:-----|
|Namespace  <br/> |https://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|Schema Name  <br/> |Message schema  <br/> |
|Validation File  <br/> |messages.xsd  <br/> |
|Can Be Empty  <br/> ||
   
## See also

- [EWS XML elements in Exchange](ews-xml-elements-in-exchange.md)
