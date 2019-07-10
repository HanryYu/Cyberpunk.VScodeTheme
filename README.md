# VSCode赛博朋克主题适配计划
## 项目简介
此内容由VSCode主题SynthWave '84而产生，适配VSCode多个常用主题。
## 主题效果预览
- Panda Theme
	
	[https://marketplace.visualstudio.com/items?itemName=tinkertrain.theme-panda]()
	
	*Before:*
	![image](https://raw.githubusercontent.com/FishionYu/Rayyu-sPic/master/img/20190705145427.jpg)
	
	![](https://raw.githubusercontent.com/FishionYu/Rayyu-sPic/master/img/20190706225954.jpg){:height="50%" width="50%"}
	
	*After*
	
	![](https://raw.githubusercontent.com/FishionYu/Rayyu-sPic/master/img/20190706225955.jpg){:height="50%" width="50%"}
## 安装指南
### 首先下载并安装
- 各已适配的主题(效果预览含有链接)
- 本项目的与主题对应的CSS文件(推荐整体下载到一个文件夹内便于替换)
- 安装Custom CSS and JS Loader VSCode插件[https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css]()
### 启用文字发光效果
	注意，以下操作存在风险。为避免意外，请先用 Sync 插件保存你的配置。

首先先启用相应的主题，执行VSCode首选项-\>颜色主题，选择相应的即可。

要想启用文字发光效果，VSCode里面主要是一个插件 Custom CSS and JS加载自定义CSS实现的。

启用*Costom CSS and JS*后，打开VSCode首选项-\>设置，打开*setting.json*，找到或插入以下内容：
`”vscode_custom_css.imports": []`

这个内容中的方括号用来写入所需导入的CSS文件地址，路径应以*file:///*开头。

**示例：**

如果我使用的Panda主题，Panda.css文件在*/Users/用户/Documents/Develop/GitHub/Cyberpunk.vscodeTheme/panda.css*，那么

` "vscode_custom_css.imports": [`

`"file:///Users/用户/Documents/Develop/GitHub/Cyberpunk.vscodeTheme/panda.css"`
` ]`

保存后按 *Ctrl + Shift + P *或者 *Shift + ⌘ + P*，选择 *Enable custom CSS and JS*。VSCode 会提示重启，重启后发光特效应该就生效了。

此时，VSCode 可能会提示 “VSCode 已损坏”，点击不再提醒即可(无任何影响)。

	注意，VSCode每次更新后，都需要重新执行Enable custom CSS and JS的操作

### 关闭特效
只需要按 *Ctrl + Shift + P* 或者 *Shift + ⌘ + P*，选择 *disable custom CSS and JS*然后重启就可以了。
## 适配进度
- Panda Theme http://progressed.io/bar/95
- Ayu Dark http://progressed.io/bar/20
- AtomOneDark http://progressed.io/bar/40
- ……





