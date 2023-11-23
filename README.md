# Blazor-404-redirect
Example template with a working 404 redirect when an invalid URL is entered.

## TL;DR
Add the following to your `Program.cs` file:
``` 

app.UseStatusCodePagesWithRedirects("/404");

app.Run();
```
Add a `_404.razor` page to your `Pages` folder.
```

@page "/404"
<h3>Show me 404</h3>
@code {
    
}

```