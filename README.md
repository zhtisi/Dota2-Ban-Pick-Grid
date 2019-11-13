# Dota2-Ban-Pick-Grid
# Dota2自定义英雄选择视图(custom hero grid)
这个小项目旨在收集DOTA2的自定义英雄视图，如有助于选人和禁用的BP图等。


## DOTA2导入自定义视图的方式
Dota2导入这样的自定义英雄视图的方式非常简单，将自定义视图的json文件粘贴到你的Steam安装路径下的userdata\(你的数字编号)\570\remote\cfg 目录下即可


## 举例说明
举个例子，我进入"BP图-贴吧-永远的倪大侠"目录，查看预览图preview.png，发现做的超级棒，于是想使用他。

![image](https://github.com/zhtisi/Dota2-Ban-Pick-Grid/blob/master/BP%E5%9B%BE-%E8%B4%B4%E5%90%A7-%E6%B0%B8%E8%BF%9C%E7%9A%84%E5%80%AA%E5%A4%A7%E4%BE%A0/preview.png)

第一步，在github上下载，在想要下载的json文件上，右键 -> 链接另存为，然后保存到自己电脑上。
![image](https://github.com/zhtisi/Dota2-Ban-Pick-Grid/blob/master/save.png)

第二步，找到自己的cfg目录，比如我的steam安装在D:\Game\Steam，我的数字编号是136xxxxxx，所以我进入D:\Game\Steam\userdata\136xxxxxx\570\remote\cfg，把下载好的hero_grid_config.json粘贴到这里。粘贴前请先退出Dota2！
![image](https://github.com/zhtisi/Dota2-Ban-Pick-Grid/blob/master/directory.png)


第三步，打开dota2，享受自定义英雄视图~
![image](https://github.com/zhtisi/Dota2-Ban-Pick-Grid/blob/master/choose_view.png)

## 注意
    如果你过去已经有自定义视图，并且希望保留过去的自定义视图。请先备份一份本地的hero_grid_config.json文件。接下来打开本地的hero_grid_config.json文件（使用任意文本编辑器即可），然后打开想要的这个项目中的json文件，接下来复制这个项目中的json文件的"configs":[] 这部分里中括号内部的内容（以大括号开始，大括号结束的部分）。 在本地的hero_grid_config.json文件内，"configs":[] 部分最后的那个中括号前，输入一个英文逗号，然后再粘贴，保存，即可同时拥有多个视图。
    如果出现了异常，那么退出Dota2，再把备份的本地的hero_grid_config.json文件覆盖回原来的位置，即可恢复。
