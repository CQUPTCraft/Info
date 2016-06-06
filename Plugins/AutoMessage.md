### AutoMessage

>**记得在普通玩家权限组添加`automessage.receive.[消息组名]` 使普通玩家能接收消息** 
>
>注意不要使用全角符号
>
```YAML
automessage.commands.reload:
Reload 权限
automessage.commands.update:
有新版本时升级
automessage.commands.add:
创建一个新的消息列表或添加新的消息
automessage.commands.edit:
编辑消息列表内的消息
automessage.commands.remove:
移除一条消息或者移除特定消息内的一行
automessage.commands.enabled:
开关一条消息. 依旧可以编辑消息;但是不会被广播.
automessage.commands.interval:
设置播放消息时候的间隔.
automessage.commands.random:
设置广播消息的方式. Random随机广播或者non-random来简单循环.
automessage.commands.prefix:
设置所有消息的前缀.
automessage.commands.suffix:
设置所有消息的后缀.
automessage.commands.broadcast:
广播特定消息组.
automessage.commands.list:
列出所有消息组 or 消息组里面的所有消息.
automessage.receive.message-list:
接收某个消息组. 用配置文件中的消息组名替换掉message-list.
```