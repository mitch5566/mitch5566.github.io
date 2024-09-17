# waveforecastttt
 test for fulls

>xx練習


```json
"DefaultConnection": "Server=192.168.118.128;User ID=;Password=;Database=cakeweb"
```

參考
https://ithelp.ithome.com.tw/m/articles/10201977

```bash 
dotnet build ./bbcal/bbcal.csproj

dotnet add package Microsoft.EntityFrameworkCore

dotnet add package Microsoft.EntityFrameworkCore.Tools
dotnet add package Microsoft.EntityFrameworkCore.Design
dotnet add package Pomelo.EntityFrameworkCore.MySql

// 忘
dotnet add package MySqlConnector.DependencyInjection


/////sql用這個
dotnet add package Microsoft.EntityFrameworkCore.SqlServer


dotnet new class -n ApplicationDbcontext -o Data

dotnet ef migrations add AddCategoryTableToDb
dotnet ef migrations add SeedCategoryTable


dotnet ef database update
dotnet new class -n CategoryController -o Controllers

```
