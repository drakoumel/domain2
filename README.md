## solution to electricity counter

- if you want to execute it you will need [dotnet-core](https://www.microsoft.com/net/learn/get-started/)

- depending on your platform you will need to execute the [migrations first](https://docs.microsoft.com/en-us/ef/core/managing-schemas/migrations/)

- to run the tests you need to run `dotnet xunit`

### the only change that has been made is the callable path to the routes, as CamelCase is the preferred naming convention.
### Inside you can also find a postman file to test the end points.
### Swagger is also available under [http://localhost:60409/swagger/](http://localhost:60409/swagger/) 
### it uses local-sql-db which I think requires extra installation.
