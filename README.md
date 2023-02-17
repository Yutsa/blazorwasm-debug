# How to debug Blazor WebAssembly Hosted

There are two VS Code launch configurations.

Start by launching `Launch and Debug Standalone Blazor WebAssembly App` to run the app and the debug for
the client code.

Then launch `Debug Server` to debug the server code. You can run both at the same time and have the debugger working on VS Code.

## Issues with certificate on Linux ?

[https://learn.microsoft.com/en-us/aspnet/core/security/enforcing-ssl?view=aspnetcore-7.0&tabs=visual-studio%2Clinux-ubuntu#trust-https-certificate-on-linux](Microsoft doc for Linux certificates).