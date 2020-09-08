[Link al Artículo que acompana este Post](https://www.red-gate.com/simple-talk/dotnet/c-programming/build-a-rest-api-in-net-core/?utm_source=simpletalkdotnet&utm_medium=pubemail&utm_content=20200908-slota1&utm_term=simpletalkmain)

Notes:

```shell
> dotnet new sln
> dotnet new webapi --no-https
> dotnet sln add .
```

In-memory database provider:

```shell
> dotnet add package Microsoft.EntityFrameworkCore.InMemory
```

API versioning:

```shell
> dotnet add package Microsoft.AspNetCore.Mvc.Versioning
```

Swagger:

```shell
> dotnet add package Swashbuckle.AspNetCore
```

NLog:

```shell
> dotnet add package NLog.Web.AspNetCore
```

JsonDocumentPatch:

```shell
> dotnet add package Microsoft.AspNetCore.Mvc.NewtonsoftJson
```
