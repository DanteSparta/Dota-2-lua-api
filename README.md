DOTA2 API SNIPPETS<br />DOTA2 API 函数自动补全
=========================================

    A plugin of Sublime Text 2 snippets to be used with dota2 lua
    Most snippets are tobe userd specfically with .lua
<br />
    
    这是一个DOTA2的LUA自动补全插件，能够在SUBLIME TEXT 2中使用。
    对于.LUA文件，能够进行函数名的自动补全

Installation:<br />使用方法
-----------------------------------------

    Download the zip file and extract the 【dota2 lua api】
    Folder into Sublime Text2 【Preferences】 -> 【Browse Packages】
    ... Directory.

    下载ZIP文档，将在SUBLIME TEXT里面点击Preferences-> Browse Packag
    es，在这个文件夹里面新建一个dota2 lua api文件夹，复制ZIP文档内的
    内容到dota2 lua api文件夹里面.

Tab Triggers:<br />TAB自动补全
-----------------------------------------

    " CreateParticleForPlayer " => " CreateParticleForPlayer(string 
    particleName,int ParticleAttach,Entity owningEntity,Player
    viewingPlayer) "
    
    在SUBLIME TEXT 2 里面输入CreatePar之类的，按回车或TAB，会自动
    补全为CreateParticleForPlayer(string particleName,int
    ParticleAttach,Entity owningEntity,Player viewingPlayer)，
    要取消自动补全，按ESC即可。

    " MODIFIER " => " MODIFIER_ATTRIBUTE_MULTIPLE "
 
    可以使用中文名来进行函数提示，在SUBLIME TEXT 2里面输入生命，
    会提示伤害类型-生命移除，按TAB则会自动补全为 DAMAGE_TYPE_HP_REMOVAL


Further Plan<br />下一步计划
-----------------------------------------

    Make it support SChinese etc.
    补全更多的API函数和中文支持。
