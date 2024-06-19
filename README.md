# Vorn.Aaas.Client.Wasm
```csharp
using Microsoft.AspNetCore.Components.WebAssembly.Hosting;
using Vorn.Aaas.Client.Wasm;

WebAssemblyHostBuilder builder = WebAssemblyHostBuilder.CreateDefault(args);
builder.AddAaasClientWasm();
await builder.Build().RunAsync();
```