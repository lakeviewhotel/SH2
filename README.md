# Silent Hill 2 Localization


### 目前使用过的游戏镜像版本

* PC: Silent Hill 2 (USA)<br />
* PC: Silent Hill 2: Director's Cut (Europe)<br />
* PS2: Silent Hill 2: Director's Cut (Europe)<br />
* PS2: Silent Hill 2: Saigo no Uta (Japan)<br />
* XBOX360: Silent Hill HD Collection (Japan)<br />
<br />

# 本地化工具介绍
以下全部工具打包下载：[sh2tools](https://pan.baidu.com/s/11bJbceBYoMrYtS0nrUg4lA)<br />
密码: ktv8

### 游戏镜像破解工具（可选）

* sh2ex by Nisto<br />
导出**PS2**镜像中的游戏资源。使用说明请至[此处](https://github.com/Nisto/sh2ex)。
 
* iso extract / xbdecompress<br />
iso extract用于导出**XBOX360**镜像中的游戏资源。<br />
资源导出后，需要通过xbdecompress.exe对游戏资源进行解压后才可以查看。<br />
小tip：比如想要导出sh2_360\data\pic\font下的font000.tex，可以在解压时把.tex改成.dds，这样就可以直接用任何dds贴图查看器打开这张贴图了。
 <br />
 
### 文本工具
 
* Ultimate SH-MES Recompilator by WarMaker<br />
 导出/编辑/导入 .mes文本文件。
 
 基本使用说明（详细版说明在[这里](http://hometown.sh/forum/viewtopic.php?f=2&t=7996)）<br /><br />
![alt text](https://raw.githubusercontent.com/lakeviewhotel/SH2/master/ultiMES%20screenshot.jpg)<br />
1. 将.mes文件放入**src**文件夹；
2. 点击**导出**按钮；
3. 被导出的文本会在**txt**文件夹中生成文本文件；
4. 修改保存好文本后，按**导入**按钮；
5. 在**dst**文件夹中找到新的.mes文件。


* Silent Hill Text Converter (SH2 & 4) by John_Modest<br />
导出/编辑/导入 .mes文本文件。
 
* SH Resourse Editor by John_Modest<br />
 导出/编辑/导入 .mes文本文件。除文本外，此工具支持导出寂静岭2-3代的音频文件。
 <br />
 
### 文本贴图工具

* DX8 to DX9 convertor v0.035 / Texmod<br />
搭配这两样工具，可以实现导出游戏中的各种贴图。这里主要目的是为了修改测试文本贴图。

1. 将DX8 to DX9 convertor中的文件放入游戏根目录，以便运行只支持DX9游戏的Texmod；<br />
可能会出现的bug：播放CG影片时RGB出错。

2. 打开与设置Texmod，通过Texmod运行游戏，导出游戏贴图；
3. 修改贴图，制作/使用贴图包；
4. 再次用Texmod运行游戏，测试。<br />
此工具的缺点是游戏要在Texmod的环境下运行，所以这里只当做测试用。

* SH234 Font Extractor by belek666<br />
每次从sh2pc.exe中导出一个字符，输出格式为tga贴图。<br />
不确定对汉化有任何帮助。我已经将可导出的字符全部导出，放在了这个工具的根目录。
 <br />
 
### 游戏贴图工具

* Silent Hill Texture Explorer (SH2-3) by John_Modest<br />
此工具可以导出游戏中的大部分贴图，用来汉化游戏中的地图/艺术字等等。
<br /><br />
 
### 其他语言本地化补丁

* 俄语
* 波兰语
* 阿拉伯语

我会把这些本地化补丁一并打包在工具合集里，以便大家参考。
<br /><br />


### 原版/破解版sh2pc.exe
包含美版/欧版无修改与破解后的sh2pc.exe文件。 <br />
美版：v1.0，v1.1 <br />
欧版：Director's Cut
 <br /><br />



### .mes文件包

导出自PS2游戏镜像，Silent Hill 2: Director's Cut (SLES-51156, v1.02)，包含英语、法语、德语、意大利语、西班牙语与日语，作为汉化备份。<br />

2018.05.16更新：
单独的日文mes文件包，已将所有_j.mes重命名为_e.mes。<br /><br />

以上全部工具打包下载：[sh2tools](https://pan.baidu.com/s/11bJbceBYoMrYtS0nrUg4lA)<br />
密码: ktv8
