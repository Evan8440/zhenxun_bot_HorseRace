最新更新：
2022.07.12： 延时函数time.sleep 换成 await asyncio.sleep
            禁止同名马参赛，禁止"."开头或者结尾的马参赛（会导致位置显示混淆视听）
            更改插件分类

2022.06.24：更正事件文件为utf-8格式，更正读取格式为utf-8

2022.06.24：修正了跨群赛马的问题


# Zhenxun_bot_HorseRace
适配真寻的赛马小插件，支持自定义事件

首先感谢[赫尔不是中二病](https://gitee.com/heerkaisair/horse-race-ami/)及其项目提供的帮助（哦，我的上帝这玩意怎么要.Net 4.8，还不是python的）

然后就写了这个赛马-青春版-真寻专用版  

插件依赖 [nonebot-plugin-htmlrender](https://github.com/kexue-z/nonebot-plugin-htmlrender) 插件来渲染图片，使用前需要检查 playwright 相关的依赖是否正常安装；同时为确保字体正常渲染，需要系统中存在中文字体

### 真寻bot的插件安装方式

真寻安装是请将该插件下载并将nonebot_plugin_htmlrender与HorseRace放于同一插件目录

P.S.(nonebot_plugin_htmlrender_main里有个文件夹叫nonebot_plugin_htmlrender，别再问为啥依赖装了但是还是依赖报错了，天天都有人问这个问题)

nonebot_plugin_htmlrender在真寻中缺失依赖为 markdown 和 Jinja2

安装方式：以下指令请在poetry shell   # 进入虚拟环境后运行

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

### 给此项目 上传事件包
进入events目录，将事件包内容整个复制进去后，确认并提交pr

![3~}A`0{P7%DCBC X2KV5~)B](https://user-images.githubusercontent.com/108109327/175483369-1fccb3d6-b82e-4299-9ecb-21aa576c4c17.png)

![image](https://user-images.githubusercontent.com/108109327/175483630-5cee9121-559b-4332-8908-1fabb6ce73e3.png)

![image](https://user-images.githubusercontent.com/108109327/175483676-6ec142cc-caf5-45fb-8c6b-746b4d8232cb.png)

![image](https://user-images.githubusercontent.com/108109327/175483871-7d822294-1fef-4b14-9221-031d0da678d6.png)





