* 清空数据库


```mysql
USE coreprotect;
DROP DATABASE coreprotect;
CREATE DATABASE coreprotect;
USE authme;
TRUNCATE TABLE authme;
USE wemarried;
TRUNCATE TABLE marriage_marriages;
TRUNCATE TABLE marriage_players;
TRUNCATE TABLE marriage_version;
```

* 删除World和附属数据（末地、地狱）


* 设置用户组权限
  * 添加AutoMessgae
  * 设置为builder组而不是默认组
  * 添加skin权限`skinsrestorer.playercmds` 


- 配置ArmorHUD
  - 设置默认状态为on
  - 汉化language.yml

* 配置AuthME
  * 对应数据库用户密码
  * 数据库权限
  * 清除logo和Sqlite文件
  * 修改welcome.txt
* AutoMessage
  * 修改消息内容


* ColorMOTD
  * 修改消息内容




- CoreProtect
  - 对应数据库用户密码
  - 数据库权限
- Essentials

config.yml

```yaml
locale: zh
	是否运行build & use
	build: false
	use: false
blacklist:
	placement: 10,11
	use: 
新手
newbies:
	欢迎信息
	announce-format: '欢迎{DISPLAYNAME}来到MC@CQUPT'【&dWelcome {DISPLAYNAME}&d to the server!】
	spawnpoint: none【newbies】
	kit: ''【tools】
```

* LockettePro
  * 修改语言
  * 打开uuid支持




* 配置Marriage

  *  修改数据库配置

  * 关闭自动清理

  * ```ya
    auto-purge:
    	enabled: false
    ```


- PermissionsEX
  - 配置玩家权限
- RPGItems-Reload
  - 设置中文
- WorldEdit
  - 开启日志记录


- 清除GroupManager的user.yml
- 设置spawn不可破坏
- 修改MOTD
- 检查汉化文件