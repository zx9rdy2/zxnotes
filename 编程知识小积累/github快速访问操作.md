# github快速访问操作
## 一、找IP地址
1. 首先搜索站长工具（https://tool.chinaz.com/dns/）
2. DNS查询——>A类中输入github.com（点击查询）
3. 找到合适的IP地址

## 二、修改hosts文件
1. 在C盘中找到hosts并打开修改（C:\Windows\System32\drivers\etc）
   > （1）在左上角文件中，选择管理员打开
   > （2）输入cmd回车，在输入notepad hosts以打开hosts文件，在最后一行添加<mark>#      IP地址    github.com</mark>，并保存。

## 三、
1. win+R，再输入cmd打开
2. 输入ipconfig/flushdns。（刷新DNS配置）——>即可完成，就能快速打开github。打不开的话，再重复上述步骤以打开。
> 若ipconfig不显示。在控制面板中，找到**高级系统设置**，选择**修改环境变量**，输入%SystemRoot%\system32并保存即可显示ipconfig。