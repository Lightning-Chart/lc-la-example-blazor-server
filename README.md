# LCLA Blazor Server Example

Real-time XY chart with streaming sine/cosine data.

Clone this standalone example with:

```bash
git clone https://github.com/Lightning-Chart/lc-la-example-blazor-server.git
cd lc-la-example-blazor-server
```

## Prerequisites

- .NET 8 SDK
- LightningChart JS license key ([get one here](https://lightningchart.com/js-charts/))

## Build and Run

1. Configure your application with a free LightningChart JS trial key or existing commercial key. This example reads `LCJS_LICENSE_KEY`; deployment licenses can also use `LCJS_APP_TITLE` and `LCJS_COMPANY`.

2. Run the example:
   ```
   dotnet run
   ```

3. Open https://localhost:5001 (or the URL shown in terminal) and navigate to "LCLA Chart".

4. Click "Start Streaming" to see real-time data.
