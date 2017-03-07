# Entity Framework
## Dependencies added to project.json file

Add:
````JSON     
    "Microsoft.EntityFrameworkCore.Sqlite": "1.1.1",
        "Microsoft.EntityFrameworkCore.Tools": {
          "version": "1.1.0-preview4-final",
          "type": "build"
    }
````      
and     

````JSON     
    "tools": {
      "Microsoft.EntityFrameworkCore.Tools": "1.0.0-preview2-final"
    }
````  

So it will look like this:    

project.json
````JSON 
{
  "version": "1.0.0-*",
  "buildOptions": {
    "debugType": "portable",
    "emitEntryPoint": true, 
    "preserveCompilationContext": true
  },
  "dependencies": {},
  "frameworks": {
    "netcoreapp1.1": {
      "dependencies": {
        "Microsoft.NETCore.App": {
          "type": "platform",
          "version": "1.1.0"
        }, 
        "Microsoft.AspNetCore.Server.Kestrel" : "1.1.0",
        "Microsoft.AspNetCore.Mvc": "1.1.0",
        "Microsoft.EntityFrameworkCore.Sqlite": "1.1.1",
        "Microsoft.EntityFrameworkCore.Tools": {
          "version": "1.1.0-preview4-final",
          "type": "build"
    }
      },
      "imports": "dnxcore50"
    }
  }, 
  "tools": {
    "Microsoft.EntityFrameworkCore.Tools": "1.0.0-preview2-final"
  }
}
````   
