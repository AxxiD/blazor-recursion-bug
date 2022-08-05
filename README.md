# Blazor Recursion Bug - Sample

This project demonstrates a bug with blazor where the page becomes unresponsive and makes the page completely unusable until it is closed or another page is loaded.

This is the default Blazor WASM template stripped of some pages and with the bug page.

## How it works

1. Create a new Blazor WASM project
2. Add a new page called `MyTestPage.razor`
3. Add `@layout MyTestPage` at the top of this new file
4. Run and open the app (`dotnet run`)
5. then go to the new page
6. ???
7. tab freezes / page becomes unusable until memory is full (watch Task Manager)

## Interesting files in this repo

- BlazorRecursionBugApp/Pages/MyTestPage.razor
