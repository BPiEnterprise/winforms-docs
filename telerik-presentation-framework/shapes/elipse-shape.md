---
title: Ellipse Shape
page_title: Ellipse Shape| UI for WinForms Documentation
description: This article shows how you can create and use the supported shapes.
slug: winforms/telerik-presentation-framework/ellipse-shape
tags: ellipse-shape
published: True
position: 1
---

# Ellipse Shape

The following image shows the ellipse shape applied to a RadPanel:

![ellipse-shape001](images/ellipse-shape001.png)

The following code shows how you can create and apply a __EllipseShape__:


{{source=..\SamplesCS\TPF\Shapes\ShapesCode.cs region=Ellipse}}  
{{source=..\SamplesVB\TPF\Shapes\ShapesCode.vb region=Ellipse}}
````C#
EllipseShape ellipseShape = new EllipseShape();
radPanel1.PanelElement.Shape = ellipseShape;

````
````VB.NET
Dim ellipseShape As New EllipseShape()
radPanel1.PanelElement.Shape = ellipseShape

````  
 
{{endregion}} 

