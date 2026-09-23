# Different Editing Modes in Blazor Tree Grids

## Overview

This sample demonstrates how to bind data to the Syncfusion [Blazor TreeGrid](https://www.syncfusion.com/blazor-components`) component in a hosted Blazor WebAssembly application. The example showcases two common data-binding approaches: binding hierarchical records from a local collection and retrieving data from remote service endpoints. These approaches help developers understand how to display and manage hierarchical business data using both client-side and server-backed sources within the same application architecture.

**Documentation**: https://blazor.syncfusion.com/documentation/treegrid/edit 

**Online example**: https://blazor.syncfusion.com/demos/tree-grid/inline-editing

## Key Features

- Demonstrates binding hierarchical local collection data to the TreeGrid.
- Demonstrates loading TreeGrid data from remote service URLs.
- Shows parent-child hierarchical record relationships in a tree structure.
- Uses a hosted Blazor WebAssembly solution with separate Client, Server, and Shared projects.
- Illustrates TreeGrid data presentation using local and service-based data sources.
- Demonstrates handling hierarchical data records that can be expanded and collapsed within the TreeGrid.
- Provides sample models shared between client and server projects for data binding scenarios.
- Includes server-side endpoints used to supply TreeGrid data to the Blazor WebAssembly client.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the solution file:

   `BindingTreeListData.sln`

3. Restore NuGet packages.
4. Build the solution.
5. Set the hosted server project as the startup project if required.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the repository root containing the solution file.

```bash
dotnet restore
dotnet run
```

## Project Structure

`Client/Pages/Index.razor` — Primary sample page containing the Syncfusion TreeGrid editing implementation, editing mode configuration, toolbar actions, CRUD workflow setup, and command-column functionality.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official documentation: https://help.syncfusion.com/grid-sdk/blazor/tree-grid/editing/edit

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
