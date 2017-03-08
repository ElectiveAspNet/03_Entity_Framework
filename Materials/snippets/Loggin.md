````JSON
"Microsoft.Extensions.Logging": "1.1.0",
"Microsoft.Extensions.Logging.Console": "1.1.0"
````     

```` C#

public void Configure(IApplicationBuilder app, ILoggerFactory loggerFactory)
{
    loggerFactory.AddConsole();

    ....

```` 




