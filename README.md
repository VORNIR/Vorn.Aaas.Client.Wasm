# Vorn.Aaas.Client.Wasm
This razor library is designed for web assembly part of web applications which act as clients who get authentication as a service from AaaS server.
```bash
dotnet add package Vorn.Aaas.Client.Wasm
```
```csharp
var builder = WebAssemblyHostBuilder.CreateDefault(args);
builder.AddAaasClientWasm();
await builder.Build().RunAsync();
```

**Note**: The host must be setted up with [Vorn.Aaas.Host.Wasm](https://github.com/VORNIR/Vorn.Aaas.Client.Host.Wasm).
