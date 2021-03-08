# Blazor issue with focus trap

This shows an issue with Blazor, causing an exception when switching pages.

The application is the basic starter template Blazor WebAssembly, with added MudBlazor to Index page.
Once started, choose another page from the meny, e.g. Counter, then switch back to Index page and we have the exception.

This sample links to the related issue [Exception thrown if FocusAsync() and @onfocusin are used in custom input element at the same time - blazor Wasm](https://github.com/dotnet/aspnetcore/issues/30070)
