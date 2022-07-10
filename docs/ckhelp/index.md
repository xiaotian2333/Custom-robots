# 米游社Cookie 配置帮助

>私聊机器人前先加好友！

>Cookie 是米游社的登录凭证（仅可登录网页版米游社，无法登录游戏）。
运营者确保不会泄露你的 Cookie，若不信任本机器人，请勿配置。

配置成功机器人可以获取更多数据

如：查询体力，查询原石，原石统计，米游社自动签到


## 安卓
1. 下载安装 [Via 浏览器](https://viayoo.com/zh-cn/)，应用商店搜索也有。

>如果你是在QQ/微信内打开本网页，请在右上角点击在浏览器打开

![VIA浏览器](/img/VIA浏览器.png "VIA浏览器图标")

2. 打开 Via 浏览器，打开网页版米游社 https://bbs.mihoyo.com/ys/ 。然后登录米游社。

![登陆米游社](/img/登陆米游社.png "登陆米游社")

3. 复制下面代码，点击浏览器最上面的地址栏，删掉网址，粘贴代码，点击右边箭头确认。

~~~ JavaScript
    javascript:(function () { prompt("", document.cookie); })();
~~~

![复制代码](/img/复制代码.png "复制代码")

4. 然后就会弹出弹窗，长按红框里面内容，全选复制所有内容。

![复制全部内容](/img/复制全部内容.png "复制全部内容")

5. 最后将复制内容私聊发送机器人，不能私聊可以加机器好友。

![发给机器人](/img/发给机器人.jpg "发给机器人")


## IOS
>整个过程中提示的权限都要允许

1. 打开链接 https://www.icloud.com/shortcuts/6b76ba13c7be40b69580169507f7034e 获取快捷指令，点"添加到快捷指令"。

![获取快捷指令](/img/获取快捷指令.png "获取快捷指令")

2. 在快捷指令APP中点击这个快捷指令，提示将打开米游社，选择“好”之后会拉起 Safari，在打开的页面中登录。（也可以手动打开 Safari，登录米游社后往下继续操作。）

3. 登录好之后，点下面的“共享”按钮，拉到最下面，选“米游社Cookie获取”。

![使用快捷指令](/img/使用快捷指令.png "使用快捷指令")

4. 然后会弹出是否复制到剪贴板，选择允许，就会自动复制到剪贴板了，私聊粘贴发送给机器人，不能私聊可以加机器好友。 


## 电脑
>此处使用`EDGE浏览器`示例，其他浏览器操作类似

1. 打开浏览器，按`CTRL+SHIFT+N`打开InPrivate 浏览（无痕/隐身模式），然后打开网页版米游社 https://bbs.mihoyo.com/ys/ 。

2. 登录米游社。`登录后不能点退出，点了退出就会失效。最好用无痕模式获取`。

3. 然后按`CTRL+D`,在弹出的窗口点击更多。

![点击更多](/img/点击更多.png "点击更多")

4.在弹出的窗口粘贴以下代码

~~~ JavaScript
    javascript:(function () { prompt("", document.cookie); })();
~~~

![粘贴后点保存](/img/粘贴后点保存.png "粘贴后点保存")

5.然后在点击刚才保存的标签。

6.在弹出的窗口右键，点击复制。

![右键点复制](/img/右键点复制.png "右键点复制")

7.发给机器人就可以啦~

## 注意

● 登录过久的用户无法获取**完整cookie**，可以**退出重登**，然后再获取，以支持签到功能

● 获取完后退出登录cookie就会失效

● 多账号的可以用无痕模式获取

by:大海

2022年7月10日