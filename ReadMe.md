### Where did my Exception ended up?
This sample project demonstrates that Exceptions are not always caught by ErrorBoundary and can just fail silently.
This project was created from scratch using Blazor Web App template, interactiveServer, Global
I simply modified the Counter.razor and wrapped the router in an ErrorBoundary.
- The Exception thrown when clicking the button is caught by the ErrorBoundary as expected.
- The Exception thrown shows up in the browser console but is not caught by ErrorBoundary !?