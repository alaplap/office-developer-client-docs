---
title: "ShapePermeableY Cell (Shape Layout Section)"
 
 
manager: soliver
ms.date: 03/09/2015
ms.audience: Developer
ms.topic: reference
f1_keywords:
- Vis_DSS.chm82251666
 
ms.localizationpriority: medium
ms.assetid: 90701ecf-3d34-2eac-9ee9-7965e16c0f7c
description: "Determines whether a connector can route vertically through a shape."
---

# ShapePermeableY Cell (Shape Layout Section)

Determines whether a connector can route vertically through a shape.
  
|**Value**|**Description**|
|:-----|:-----|
|TRUE  <br/> |Enable connectors to route vertically through a shape. |
|FALSE  <br/> |Do not let connectors route vertically through a shape. |
   
## Remarks

You can also set the value of this cell on the **Placement** tab in the **Behavior** dialog box (with a shape selected, on the [Developer](run-in-developer-mode-display-the-developer-tab.md) tab, in the **Shape Design** group, click **Behavior**, and then click the **Placement** tab). 
  
In versions earlier than Visio 2000, you set this behavior by using the ObjInteract cell in the Miscellaneous section.
  
To get a reference to the ShapePermeableY cell by name from another formula, or from a program using the **CellsU** property, use: 
  
|||
|:-----|:-----|
|Cell name:  <br/> |ShapePermeableY  <br/> |
   
To get a reference to the ShapePermeableY cell by index from a program, use the **CellsSRC** property with the following arguments: 
  
|||
|:-----|:-----|
|Section index:  <br/> |**visSectionObject** <br/> |
|Row index:  <br/> |**visRowShapeLayout** <br/> |
|Cell index:  <br/> |**visSLOPermY** <br/> |
   

