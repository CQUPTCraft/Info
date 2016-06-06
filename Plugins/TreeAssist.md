## TreeAssist

如果你砍倒or烧倒一棵树，这个插件可以帮你再种一棵相同的树。这个插件也可以在你用配置文件中规定的工具砍倒树根处时帮你砍倒整棵树。

#### Features

- 在树被砍倒或者烧倒的时候重新种植
- 砍倒了一棵桦树？插件可以帮你重新种一棵桦树。支持所有树种。
- 当你破坏了树根的时候自动破坏整棵树
- 树叶消失得更快

#### Config

- ​		。有关 .yml 格式如果你有任何问题，请尝试使用 notepad++。
- 你可以添加任何工具到`配置文件->工具`中。使用'AIR'来使用拳头为工具（喂。
- 如果你想使用整合包或者扩展mod的工具，请使用Item ID。

#### Commands

- **/treeassist toggle** -  允许玩家自己开关砍树插件
- **/treeassist global** - 砍树插件全局开关
- **/treeassist reload** - 重新载入配置文件
- **/treeassist protecttool** - 获得一个工具去保护特定树种
- **/treeassist noreplace** - 在一个周期内停止自动补种
- **/treeassist purge** [worldname`世界名字`|global`全局`] - 重置data.yml
- **/treeassist addtool** - 将你手中的工具添加到`配置->工具`中
- **/treeassist removetool** - 将你手中的工具从`配置->工具`中删除