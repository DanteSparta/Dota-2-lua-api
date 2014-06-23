##DOTA2 API SNIPPETS DOTA2 API自动补全

A plugin of Sublime Text 2 snippets to be used with dota2 lua, Most snippets are tobe userd specfically with .lua
这是一个SUBLIME TEXT的插件，用来给DOTA2的LUA代码进行自动补全和代码提示，几乎所有的代码在.lua的文件中都可以使用。

### Installation 安装方法:

Download the zip file and extract the {dota2 lua api} Folder into Sublime Text2 {Preferences} -> {Browse Packages} ... Directory.
下载ZIP文件，在SUBLIME TEXT里面点击 Preferences -> Browse Packages，将ZIP文件中的dota2 lua api文件夹拷贝至打开的文件夹。

### Tab Triggers TAB命令:

TAB命令能够进行自动补全，和代码提示。
- " CreateParticleForPlayer " => " CreateParticleForPlayer(string particleName,int ParticleAttach,Entity owningEntity,Player viewingPlayer) "
- 枚举字段名还支持中文。
- " MODIFIER " => " MODIFIER_ATTRIBUTE_MULTIPLE "
- "生命"      => "伤害类型-生命移除"  =>  "DAMAGE_TYPE_HP_REMOVAL"


### Further Plan 下一步计划：
- Make it support SChinese etc.
- 进一步制作中文及更多语言支持。
