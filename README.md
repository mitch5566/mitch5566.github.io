# waveforecastttt
 test for fulls

>dotnet 專案
>xx練習 練習用防失智

```json
"DefaultConnection": "Server=192.168.118.128;User ID=;Password=;Database=cakeweb"
```

>參考
https://ithelp.ithome.com.tw/m/articles/10201977

```bash 
dotnet build ./bbcal/bbcal.csproj

dotnet add package Microsoft.EntityFrameworkCore

dotnet add package Microsoft.EntityFrameworkCore.Tools
dotnet add package Microsoft.EntityFrameworkCore.Design
//ef包
dotnet add package Pomelo.EntityFrameworkCore.MySql






//直接sql開發要用這個 不一定 跟上面擇一或共存??
dotnet add package MySqlConnector.DependencyInjection
/////sql server用這個 
dotnet add package Microsoft.EntityFrameworkCore.SqlServer






dotnet new class -n ApplicationDbcontext -o Data
dotnet ef migrations add AddCategoryTableToDb
dotnet ef migrations add SeedCategoryTable

dotnet ef database update
dotnet new class -n CategoryController -o Controllers
```


```BASH
ssh mi@192
systemctl status nginx

 sudo mysql -u root -p

sudo service mysql status

修改bind-address為你的public IP:

mysql> select user from mysql.user; 
bind-address   = 192.16
重新啟動mysql:
systemctl restart mysql

```



```bash 
scp bin\Release\net8.0\linux-x64\publish\* mibaba1@ :/var/www/xxxx
```



