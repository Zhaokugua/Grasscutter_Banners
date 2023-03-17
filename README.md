# Grasscutter_Banners|割草机卡池文件

Json file collection for Grasscutter gacha Banners

收集割草机的卡池Json文件

to use the banners, select the one you want to use and place it inside "grasscutter/data" folder on your server installation.

要使用这些卡池文件，请选择任意一个下载下来然后放在“grasscutter/data”文件夹里面。

Remember to rename it to "Banners.json"

记得把文件重命名为“Banners.json”

Use "/reload" command in game to reload the banners.

你可以在游戏中使用"/reload"命令来重新加载卡池配置文件。

You're all welcome to submit a pull request and make a change on the project.

欢迎提交pr！


## Thanks|鸣谢:

[https://github.com/davidbeltrane01/grasscutters_banners_json](https://github.com/davidbeltrane01/grasscutters_banners_json)

[https://github.com/KeyPJ/genshin-gacha-banners](https://github.com/KeyPJ/genshin-gacha-banners)

[https://github.com/Grasscutters/Grasscutter](https://github.com/Grasscutters/Grasscutter)

[https://github.com/jie65535/GrasscutterCommandGenerator](https://github.com/jie65535/GrasscutterCommandGenerator)

## 后记：

修卡池的时候发现了一些经验。

如果卡池出现类似A022的字样不正常的时候，可能是gachaType写错了，需要修改正确之后才能显示。

以下是我尝试之后的可能结果，可能不一定准确但是这样确实外表看上去就是对的


>100 初行祈愿

>201 常驻祈愿

>301 角色活动祈愿1

>302 武器活动祈愿

>400 角色活动祈愿2


另外gachaType写对之后还可能出现卡池的标题消失的情况，这时候可能是titlePath的编号不对导致的。

比如2.1上半

"prefabPath":"GachaShowPanel_A054",

"titlePath":"UI_GACHA_SHOW_PANEL_A020_TITLE",

这里的titlePath里面必须是A020才能正确显示出“神铸赋形”这个武器池的标题，如果惯性思维还是填A054的话会导致标题区域空白
