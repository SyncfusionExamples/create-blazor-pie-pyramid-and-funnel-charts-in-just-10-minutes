# Create Blazor Pie, Pyramid, and Funnel Charts in Just 10 Minutes

## Overview

This sample demonstrates how to create and configure Syncfusion Blazor Accumulation Charts in a hosted Blazor WebAssembly application. The solution showcases Pie, Pyramid, and Funnel chart visualizations using shared data collections and accumulation-series rendering. The sample illustrates how to bind data to chart components, configure different accumulation chart types, display legends, and enhance chart readability through data labels and tooltips.

The implementation is organized as a hosted Blazor WebAssembly solution with separate Client, Server, and Shared projects.

## Key Features

- Demonstrates Syncfusion Blazor Accumulation Charts.
- Configures accumulation series to render Pie, Pyramid, and Funnel chart visualizations.
- Shows how chart data can be populated from shared data collections.
- Demonstrates changing chart series types within the same charting framework.
- Enables legends for category identification and chart interpretation.
- Enables data labels to display values directly within chart segments.
- Uses tooltips to provide additional information during user interaction.
- Uses a hosted Blazor WebAssembly architecture consisting of Client, Server, and Shared projects.
- Demonstrates chart rendering scenarios documented in the Syncfusion Accumulation Chart documentation.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open `PiePyramidAndFunnelChart.sln`.
3. Restore all NuGet packages.
4. Set the hosted application startup project if required.
5. Build the solution.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the repository root containing the solution.

```bash
dotnet restore
dotnet run
```

4. Open the local application URL displayed after the application starts.

## Project Structure

- `Client/Pages/` — contains the Razor page implementing the Pie, Pyramid, and Funnel chart samples.
- Additional files within the Client project support chart configuration, sample data binding, legends, tooltips, and data-label rendering.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For official documentation related to this feature, see https://help.syncfusion.com/chart-sdk/blazor/accumulation-chart/getting-started

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.