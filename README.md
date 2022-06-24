# Zhenxun_bot_HorseRace
适配真寻的赛马小插件，支持自定义事件

插件依赖 [nonebot-plugin-htmlrender](https://github.com/kexue-z/nonebot-plugin-htmlrender) 插件来渲染图片，使用前需要检查 playwright 相关的依赖是否正常安装；同时为确保字体正常渲染，需要系统中存在中文字体

### 真寻bot的插件安装方式
真寻安装是请将该插件下载并将nonebot_plugin_htmlrender与HorseRace放于同一插件目录

以下指令请在poetry shell   # 进入虚拟环境后运行
pip3 install markdown
pip3 install Jinja2


### 使用方式

    第一位玩家发起活动，指令：赛马创建
    加入赛马活动指令：赛马加入 [你的马儿名称]
    开始指令：赛马开始
    赛马超时重置指令：赛马重置

    管理员指令：赛马暂停/赛马清空
                    赛马事件重载

### 自定义事件包方式                   
事件包为gbk编码（别问，问就是复制一个事件包然后清空再编辑）
详细信息请参考：
事件添加相关.txt
事件详细模板.txt
