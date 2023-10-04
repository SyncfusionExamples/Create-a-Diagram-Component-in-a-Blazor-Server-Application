# Create a Diagram Component in a Blazor Server Application

This example explains how to create a Blazor application, add the Syncfusion Blazor package, and add the Syncfusion Blazor Diagram component to the Blazor server application. It also explains how to create a simple flowchart using nodes and connectors.

## Prerequisites

* Visual Studio 2022

## How to run the project

* Checkout this project to a location in your disk.
* Open the solution file using the Visual Studio 2022.
* Restore the NuGet packages by rebuilding the solution.
* Run the project.

## Overview

The [Blazor Diagram](https://www.syncfusion.com/blazor-components/blazor-diagram) is a feature-rich library for visualizing and creating diagrams. It supports creating flowcharts, organizational charts, mind maps, and BPMN charts either through code or a visual interface.

## Flowchart

The Blazor Diagram component provides all the standard flowchart shapes as ready-made objects to build flowcharts, making it is easy to add them to a diagram surface in a single call.

{:.list-unstyled}
* [Learn more about blazor flowchart diagram features](https://www.syncfusion.com/blazor-components/blazor-diagram/blazor-library-flowchart)

## Organizational chart

Built-in automatic layout algorithm specifically made for organizational charts to arrange the parent and child node positions automatically.

{:.list-unstyled}
* [Learn more about Blazor organizational chart features](https://www.syncfusion.com/blazor-components/blazor-diagram/blazor-library-organizational-chart)

## Mind map

The built-in automatic layout algorithm is also built for mind map diagrams, which allows you to define which node should be at the center and which nodes should be placed around the center node in the diagram surface.

{:.list-unstyled}
* [Learn more about Blazor mind map diagram features](https://www.syncfusion.com/blazor-components/blazor-diagram/blazor-library-mind-map)

## Nodes

Visualize any graphical object using nodes, which can be arranged and manipulated at the same time on a Blazor diagram page. They allow the following:

* Use many predefined standard shapes
* Create and add custom shapes easily.
* Fully customize the appearance of a node.
* Design a node UI template and reuse it across multiple nodes.

## Connectors
A connector represents a relationship between two nodes. Some of the key features like connector types, bridging, and more.

### Types
The Blazor Diagram component provides straight, orthogonal, polyline, and curved connector types. You can choose any of these based on the type of Blazor diagram or relationship between the connected nodes.

### Bridging or line jumps
Use bridging (line jumps) to illustrate a connector’s route, making it easy to read where connectors overlap each other in a dense diagram.

### Arrowheads
Use different types of predefined arrowheads to illustrate flow direction in flowchart diagrams. You can also build your own custom arrowheads.

### Appearance
Like nodes, the connector look and feel can also be customized any way you want. The Blazor Diagram component provides a rich set of properties through which you can customize connector color, thickness, dash and dot appearance, rounded corners, and even decorators.

## Ports (connection points)
Attach connectors to specific places on a node through different types of ports or connecting points.

## Labels
Additional information can be shown by adding text or labels on nodes and connectors.

### Edit
You can add and edit text at runtime and mark it read-only if it should not be edited.

### Multiple labels
Add any number of labels and align them individually.

### Alignment
Labels include sophisticated alignment options: Place inside or outside a node, or at the source or target end of a connector. Automatically align when a node or connector moves.

## Interactive features
Use interactive features to improve the editing experience of a Blazor diagram at runtime. Furthermore, you can easily edit a Blazor diagram with mouse, touchscreen, or keyboard interfaces. 

### Select and drag
Select one or more nodes, connectors, or annotations and edit them using thumbs or handlers.

### Resize
You can resize a node in eight different directions and lock a node’s aspect ratios to keep its shape. You can also resize multiple objects at the same time.

### Rotate
Rotate selected nodes from 0 to 360 degrees.

### Undo and redo
Don’t worry when you edit by mistake—undo and redo commands help to easily correct recent changes.

### Clipboard
Cut, copy, paste, or duplicate selected objects within and across Blazor diagrams.

### Z-order
When multiple objects overlap, the z-order controls which object is at the top and which is at the bottom.

### Snap
Precisely align nodes, connectors, and annotations easily while dragging just by snapping to the nearest gridlines or objects.

### Grouping
You can combine multiple nodes into a group and then interact with them as a single object. Nested groups are also possible with our Blazor Diagram control.

### Quick commands
Frequently used commands like delete, connect, and duplicate can be shown as buttons near a selector. This makes it easy for users to quickly perform those operations instead of searching for the correct buttons in a toolbox.

## Alignment
Our Blazor Diagram library has predefined alignment commands that enable you to align the selected objects nodes and connectors with respect to the selection boundary.

### Spacing commands
Spacing commands enable you to place selected objects on the Blazor diagram at equal intervals from each other.

### Sizing commands
Use sizing commands to equally size selected nodes with respect to the first selected object.

### Align commands
All the nodes or connectors in the selection list can be aligned at the left, right, or center horizontally, or aligned at the top, bottom, or middle vertically with respect to the selection boundary.

## Automatic layout
Use automatic layouts to arrange nodes automatically based on a predefined layout algorithm. Features built-in hierarchical tree, radial tree, and symmetric layouts.

## Ruler
Rulers allow you to measure the distance of nodes or connectors from the origin of the page. This is especially useful in creating scale models.

## Symbol palette
Includes a gallery of stencils, reusable symbols, and nodes that can be dragged onto the surface of a Blazor diagram.

## Overview panel
The overview panel allows you to improve the navigation experience when exploring large Blazor diagrams. It displays a small preview of the full Blazor diagram page that allows users to zoom and pan within it.

## Drawing tools
Draw all kinds of built-in nodes and connect them with connectors interactively by just clicking and dragging on the drawing area.

## Zoom and pan tools
View a large diagram closely or assume a wider view by zooming in and out. Also, navigate from one region of a diagram to another by panning across the Blazor diagram.

## Data binding

Populate Blazor diagrams with nodes and connectors created and positioned based on data from data sources. In addition, data in any format can be easily converted, mapped, and consumed in the Blazor diagram by setting a few properties, without having to write any code. The Blazor Diagram library also supports loading data from a list or IEnumerable collection.

## Exporting
You can export the Blazor diagram to different image files such as PNG, JPEG, BMP, and SVG.

## Printing
Print Blazor diagrams from the browser. You can also customize the page size, orientation, and page margin, and fit a Blazor diagram to a single page.

## Serialization
You can save your Blazor diagram state in JSON format and load it back later for further editing using the serializer.

## Miscellaneous
In addition to all the features listed thus far, there many more that enhance the diagramming experience.

### Gridlines
Gridlines provide guidance when trying to align objects.

### Page layout
Give a page-like appearance to the drawing surface using page size, orientation, and margins.

### Tooltip
Use tooltips to provide additional information about a node.

### Context menu
Easily map frequently used commands to the context menu.

## Related Links

[Learn about more Blazor Diagram](https://www.syncfusion.com/blazor-components/blazor-diagram?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples) <br/><br/>
[Download Free Trial](https://www.syncfusion.com/downloads/blazor-components?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples) <br/><br/>
[Pricing](https://www.syncfusion.com/sales/products?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples) <br/><br/>
[Documentation](https://blazor.syncfusion.com/documentation/diagram/?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples) <br/><br/>
[Online Examples](https://blazor.syncfusion.com/demos/diagram/flowchart?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples) <br/><br/>
[Community Forums](https://www.syncfusion.com/forums/blazor-components/diagram?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples) <br/><br/>
[Suggest a feature](https://www.syncfusion.com/feedback/blazor-components?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples)

## About Syncfusion Blazor Components
The Syncfusion's [Blazor component](https://www.syncfusion.com/blazor-components?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples) library offers over 70 UI components to work with Blazor server-side and client-side (Blazor WebAssembly) projects seamlessly. In addition to Diagram, we provide popular Blazor Components such as [DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples),[Charts](https://www.syncfusion.com/blazor-components/blazor-charts?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples) [Scheduler](https://www.syncfusion.com/blazor-components/blazor-scheduler?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples), [File Upload](https://www.syncfusion.com/blazor-components/blazor-file-upload?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples), [Word Processor](https://www.syncfusion.com/blazor-components/blazor-word-processor?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples), and more.

## About Syncfusion
Founded in 2001 and headquartered in Research Triangle Park, N.C., Syncfusion has more than 23,000+ customers and more than 1 million users, including large financial institutions, Fortune 500 companies, and global IT consultancies.
 
Today, we provide 1600+ controls and frameworks for web
([Blazor](https://www.syncfusion.com/blazor-components?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples),
[ASP.NET
Core](https://www.syncfusion.com/aspnet-core-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples),
[ASP.NET
MVC](https://www.syncfusion.com/aspnet-mvc-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples),
[ASP.NET
WebForms](https://www.syncfusion.com/jquery/aspnet-webforms-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples),
[JavaScript](https://www.syncfusion.com/javascript-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples),
[Angular](https://www.syncfusion.com/angular-ui-components?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples),
[React](https://www.syncfusion.com/react-ui-components?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples),
[Vue](https://www.syncfusion.com/vue-ui-components?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples),
and
[Flutter](https://www.syncfusion.com/flutter-widgets?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples)),
mobile
([Xamarin](https://www.syncfusion.com/xamarin-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples),
[Flutter](https://www.syncfusion.com/flutter-widgets?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples),
[UWP](https://www.syncfusion.com/uwp-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples),
and
[JavaScript](https://www.syncfusion.com/javascript-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples)),
and desktop development ([Windows
Forms](https://www.syncfusion.com/winforms-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples),
[WPF](https://www.syncfusion.com/wpf-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples),
[WinUI(Preview)](https://www.syncfusion.com/winui-controls?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples)
and
[UWP](https://www.syncfusion.com/uwp-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples)).
We provide ready-to-deploy enterprise software for dashboards, reports,
data integration, and big data processing. Many customers have saved
millions in licensing fees by deploying our software.

<hr style="height:0.3px;border:none;color:lightgrey;background-color:lightgrey;" />

<p align="center">
  <a href="mailto:sales@syncfusion.com?Subject=Syncfusion Blazor Diagram - Github" target="_top">sales@syncfusion.com</a> | <a href="https://www.syncfusion.com?utm_source=github&utm_medium=listing&utm_campaign=blazor-diagram-github-samples">www.syncfusion.com</a> | 1-888-9 DOTNET <br>
</p>
