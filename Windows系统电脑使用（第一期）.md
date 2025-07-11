相信很多和我一样的同志，在一开始接触Windows电脑的时候对于磁盘管理（主要是C盘），以及其他很多使用没有清晰的概念。今天（2025.4.30），我花了一些时间，整理了一下关于在使用Windows的时候，关于磁盘管理，使用技巧（好用的软件）等方面的内容。

## 关于C盘
### 一、养成良好习惯
- 下载各种软件时尽量装在其他盘（除非软件有特殊要求需要装在C盘）
- 各种软件的默认文件下载位置和缓存存储位置在安装的时候顺手改到其他盘（提醒一下有些软件不会在磁盘里自动新建对应文件夹，建议自己手动建一个文件夹，以防磁盘文件混乱）
- 定期清理缓存（下面会提到具体方法）


### 二、清理方法
#### 一些我看过的视频或者教程链接
- [【最详细C盘清理,小白也能懂!C盘扩容指南,终极电脑优化教程帮你避坑【强烈建议收藏】新春科技特辑】]（https://www.bilibili.com/video/BV1X7Fge3ETL?vd_source=4fd6c4265e65c0785c912874692a3971）
下面的内容大部分从视频中截取，有自己使用的部分软件和感受。
#### 清理临时文件
详细在上面的视频中第一部分，不多赘述。
⚠️ 建议不要把桌面从C盘改成其他盘，会导致很多不可知的报错和使用困难，也可能会降低文件打开速度（C盘是SSD固态）。不如养成良好的整理桌面的习惯，大文件放在其他盘（也可以采用快捷方式放在桌面），常用的小文件和快捷方式放在桌面。

#### 存储设置
详细在上面视频中第二部分

#### 关闭休眠（个人不推荐）
详细在上面视频中第三部分（可以看看弹幕关闭休眠后出现的问题）

#### 软件工具
- SpaceSniffer
- Dism++（这里建议下载一个图吧工具箱，下面会提到）
- Windows Cleaner（软件很好，但是对于没有太多计算机基础的同志，在安装的时候会有点小困难）GitHub项目链接🔗：https://github.com/darkmatter2048/WindowsCleaner
- BCUninstaller：GitHub项目链接🔗：https://github.com/Klocman/Bulk-Crap-Uninstaller
- IObituninstaller&IObitunlocker：这两个亲测好用！（先入为主的印象）
- Revo Uninstaller

### 三、C盘扩容
**氪金**：有钱直接换大固态，然后重装系统。
**对于C盘和D盘在同一个物理盘**：可以使用傲梅分区助手（亲测有效）或者Disk Genius，对磁盘重新分区。⚠️：分区有风险，选择需谨慎，要做好备份。


## 关于电脑使用
### 软件推荐
PowerSettingsExplorer：一款修改Windows电源计划的软件，可以直接看到Windows隐藏的无数电源计划设置。（三角洲玩家必备😁：由于企鹅反作弊会修改电源计划）https://blog.csdn.net/nettsz/article/details/146050197 或者 https://www.mediafire.com/file/wt37sbsejk7iepm/PowerSettingsExplorer.zip （注意不要付费！！！）

QuickLook：一款快速预览文件和项目的软件，很好用！（让Windows具备Mac预览体验）：在Microsoft Store里有，其他正版网站都有。

Everything：鉴于Windows自带的文件名查找速度极为缓慢，这款软件就问世了，大大加速了查找文件的速度。（另附：图吧工具箱中有）官方链接🔗：https://www.voidtools.com/zh-cn/downloads/

Anytxt Searcher：一款补足了Everything的软件，可以查找包含特定文本内容的各类文件。

图吧工具箱：神中神软件，功能极多，包含很多实用工具。https://www.tbtool.cn/