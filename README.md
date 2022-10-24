# KKS-Translation
 恋活2中文粉丝翻译项目

## 目录
* [前置插件](#前置插件)
* [翻译安装](#翻译安装)
* [参与翻译](#参与翻译)
* [文本翻译](#文本翻译)
* [资源翻译](#资源翻译)
* [常见问题](#常见问题)

## 前置插件
- [BepInEx 5.4.x+]()
- [BepisPlugin for KKS]()
- [XUnity.AutoTranslator]()
- [KKS_TextResourceRedirector]()
- [KKS_KKS_Subtitles]()

## 翻译安装
1. 确保已安装所有前置插件。
2. 
3. 解压zip文件并移动到你游戏目录下的BepInEx文件夹(游戏可执行文件所在的文件夹)。

## 参与翻译
每一行翻译都如下所示。  
```
日文原文=中文译文
```  
示例：
```
比嘉 ひかり=比嘉 光
```
所有的翻译文件都在`BepInEx/Translation/zh-CN`文件夹下

## 文本翻译

## 资源翻译
`RedirectedResource`文件夹是游戏的主要翻译文件夹，所以需要特别对待。  
在每个文件夹中都有一个名为`translation.txt`的文件，这是翻译所在的文件。  
每个`translation.txt`文件都有需要翻译的日文文本。每行文本在开始都被注释，所以它不会被加载。为了文本在游戏中能正确显示，请将翻译放在等号右侧，并删除开头的`//`。不要编辑日文文本，否则翻译将不起作用。示例：  
翻译前：
```
//ホテル=
```
翻译后：
```
//ホテル=酒店
```
### RedirectedResource目录结构
|文件夹|描述|
|---|---|
|`action/list/clubinfo`| |
|`action/list/monologue`| |
|`action/list/prayinfo`|祈祷|
|`action/list/shopinfo`|商店|
|`action/list/topic`|话题|
|`action/list/sound/se/env`|环境音效|
|`action/list/sound/se/footstep`|脚步音效|
|`action/list/wherelive`||
|`adv/scenario`||
|`communication/*/communication_*`||
|`communication/*/communicationnpc_*`|NPC对话|
|`communication/*/optiondisplayitems_*`|对话选项|
|`communication/*/tips_*`||
|`communication/*/topiclisten_*`||
|`communication/*/topicpersonalitygroup_*`|
|`communication/*/topictalkcommon*`||
|`communication/*/topictalkrare*`||
|`custom/customscenelist`||
|`etcetra/list/config`||
|`etcetra/list/nickname`||
|`h/list/*/animationinfo_*`||
|`h/list/*/personality_voice*`|H字幕|
|`h/list/*/result_topic*`||
|`list/characustom`||
|`list/random_namr`|随机姓名|
|`list/mapinfo`|地图名称|
|`list/mapthumbnailinfo`||

### 个性
#### 角色个性  
|ID|日文|中文|
|---|---|---|
|00||
|01||
|02||
|03||
|04||
|05||
|06||
|07||
|08||
|09||
|10||
|11||
|12||
|13||
|14||
|15||
|16||
|17||
|18||
|19||
|20||
|21||
|22||
|23||
|24||
|25||
|26||
|27||
|28||
|29||
|30||
|31||
|32||
|33||
|34||
|35||
|36||
|37||
|38||
|39||
|40||
|41||
|42||
|43||

### 个性资产路径
|类型||
|---|---|
|对话(ADV)|`adv/scenario/c##/*`|
|对话(交流)|`communication/info_*/*_##`|
||`etcetra/list/nickname/*/c##`|
||`h/list/*/personalitypersonality_voice_c##_*`|

## 常见问题