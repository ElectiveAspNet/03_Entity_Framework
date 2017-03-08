Add a file:

````
Views/_ViewImports.cshtml 

```` 

Put in that:

`````
@addTagHelper *, Microsoft.AspNetCore.Mvc.TagHelpers

`````


## List of taghelpers

asp-controller="Home" 
asp-action="Index"
asp-area=""

```` C#

<li><a asp-area="" asp-controller="Home" asp-action="Index">Home</a></li>

````
