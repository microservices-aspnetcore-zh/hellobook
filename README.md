# Hello Book

这是书中的第一个示例。在这个示例中，先输入 `dotnet new` 并创建了一个空的项目。在书中，我们添加了 ASP.NET 依赖，还修改了 `Program.cs`、创建了 `Startup.cs` 来创建一个简单的“Hello World”中间件。

运行示例的方法：

```
$ dotnet restore
```

然后：

```
$ dotnet run
```

要调用中间件，并查看结果，直接访问 `curl http://localhost:5000/any/url`


-----------

译者注：

在这个中文版的仓库中，我将 .NET Core 版本升级到了 2.2，且同时升级了各个对应的依赖包。