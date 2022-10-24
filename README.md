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
- [BepInEx 5.4.x+](https://github.com/BepInEx/BepInEx/releases/)
- [BepisPlugin for KKS](https://github.com/bbepis/BepisPlugins/releases)
- [XUnity.AutoTranslator](https://github.com/bbepis/XUnity.AutoTranslator)
- [KKS_TextResourceRedirector](https://github.com/IllusionMods/TranslationTools#textresourceredirector)
- [KKS_KKS_Subtitles](https://github.com/IllusionMods/KK_Plugins#subtitles)

## 翻译安装
1. 确保已安装所有前置插件。
2. 点击`code`按钮，并在下拉菜单中点击`Download Zip`。
3. 解压zip文件并将`/KKS-Translation-main`下的文件移动到你游戏目录下的BepInEx文件夹(游戏可执行文件所在的文件夹)。

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

### 修改AutoTranslator配置文件


### 如何添加或改进翻译
- 
- 

## 文本翻译

## 资源翻译
`RedirectedResource`文件夹是游戏的主要翻译文件夹，所以需要特别对待。  
在每个文件夹中都有一个名为`translation.txt`的文件，这是翻译所在的文件。  
每个`translation.txt`文件都有需要翻译的日文文本。每行文本在开始都被注释，所以它不会被加载。为了文本在游戏中能正确显示，请将翻译放在等号右侧，并删除开头的`//`。不要编辑日文文本，否则翻译将不起作用。示例：  
翻译前：
```
//比嘉 ひかり=
```
翻译后：
```
//比嘉 ひかり=比嘉 光
```
### RedirectedResource目录结构
|文件夹|描述|
|---|---|
|`action/list/clubinfo`|入住目的|
|`action/list/monologue`|独白|
|`action/list/prayinfo`|祈祷|
|`action/list/shopinfo`|商店|
|`action/list/topic`|话题|
|`action/list/sound/se/env`|环境音效|
|`action/list/sound/se/footstep`|脚步音效|
|`action/list/wherelive`||
|`adv/scenario`||
|`communication/*/communication_*`|女主对话|
|`communication/*/communicationnpc_*`|NPC对话|
|`communication/*/optiondisplayitems_*`|对话选项|
|`communication/*/tips_*`|提示对话|
|`communication/*/topiclisten_*`|聆听对话|
|`communication/*/topicpersonalitygroup_*`|
|`communication/*/topictalkcommon*`|话题对话|
|`communication/*/topictalkrare*`|话题对话|
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
|00|セクシー||
|01|お嬢様||
|02|高飛車||
|03|後輩キャラ||
|04|ミステリアス||
|05|電波||
|06|大和撫子|
|07|ボーイッシュ||
|08|純真無垢||
|09|単純||
|10|邪気眼||
|11|母性的||
|12|姉御肌||
|13|ギャル||
|14|不良少女||
|15|野生的||
|16|意識高いクール||
|17|ひねくれ||
|18|不幸少女||
|19|文学少女||
|20|モジモジ||
|21|正統派ヒロイン||
|22|ミーハー||
|23|オタク女子||
|24|ヤンデレ||
|25|ものぐさ||
|26|無口||
|27|意地っ張り||
|28|のじゃっ子|
|29|素直クール|
|30|気さく|
|31|勝ち気|
|32|誠実|
|33|艶やか|
|34|帰国子女|
|35|方言娘|
|36|Sッ気|
|37|無感情|
|38|几帳面|
|39|島っ娘|
|40|高潔|
|41|ボクっ娘|
|42|天真爛漫|
|43|ノリノリ|

### 个性资产路径
|类型||
|---|---|
|对话(ADV)|`adv/scenario/c##/*`|
|对话(交流)|`communication/info_*/*_##`|
||`etcetra/list/nickname/*/c##`|
||`h/list/*/personalitypersonality_voice_c##_*`|

## 常见问题