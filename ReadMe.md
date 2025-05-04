### Exceptions not thrown and handled by ErrorBoundary the same way when using <InputFile> and <input type="file">
This project was created from scratch using Blazor Web App template, interactiveServer, Global
I wrapped the router in an ErrorBoundary and modified the Counter.razor to throw exceptions using <InputFile> and <input type="file">
- Exceptions thrown by <InputFile> are reflected in the browser console but never reach the ErrorBoundary
- Exceptions thrown by <input type="file"> are not reflected in the browser console but do reach the ErrorBoundary