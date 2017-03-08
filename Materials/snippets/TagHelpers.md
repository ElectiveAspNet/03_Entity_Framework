Add a file:

````
Views/_ViewImports.cshtml 

```` 

Put in that:

`````
@addTagHelper *, Microsoft.AspNetCore.Mvc.TagHelpers

`````

```` JSON

"Microsoft.AspNetCore.Razor.Tools": {
      "version": "1.0.0-preview2-final",
      "type": "build"
}

````  



## List of taghelpers

asp-controller="Home" 
asp-action="Index"
asp-area=""

```` C#

<li><a asp-area="" asp-controller="Home" asp-action="Index">Home</a></li>

````
