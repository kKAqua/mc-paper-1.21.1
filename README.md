# Minecraft Paper 1.21.1
- **启动脚本在start.sh**
# Minecraft Server Plugin Commands
- **以下常用指令不定期更新，想到啥写啥= =**
## QuickShop-Hikari 
### 商店创建与管理
- **创建商店**：手里拿着商品，面对箱子
  ```plaintext
  /qs create <price>
- **删除商店**：
  ```plaintext
  /qs remove
- **切换收购/出售模式**：
  ```plaintext
  /qs buy/sell
- **管理商店**：
  ```plaintext
  鼠标右键告示牌，按T进行操作
## Residence 
### 创建和管理领地
- **木锄选区**：
  ```plaintext
  鼠标左键点击方块1选作第一个点
  鼠标右键点击方块2选作第二个点，
  选区即为：以方块1和方块2为对角点的立方体区域
- **选区领地扩展（面朝要扩的方向）**：
  ```plaintext
  /res select expand <number>
- **创建领地**：
  ```plaintext
  /res create <name>
- **删除领地**：
  ```plaintext
  /res remove <name>
- **查看领地信息**：
  ```plaintext
  /res info
- **设置领地权限**：
  ```plaintext
  /res set <name> <flag> <true/false>

  或直接人站在领地内

  /res set
- **设置领地进出提示信息**：
  ```plaintext
  /res messages
- **管理员控制权限**：
  ```plaintext
  /resadmin set
- **管理员转移领地所有权(转让后领地权限会重制默认)**：
  ```plaintext
  /resadmin setowner <region> <player>
  
### 子领地管理
- **创建子领地**：
  ```plaintext
  /res subzone <main region> <subzone name>
- **设置子领地为出租**：
  ```plaintext
  /res market rentable <main region>.<subzone name> <price> <time>
- **查看市场正在出租/出售的领地**：
  ```plaintext
  /res market list rent/sell
## LuckPerms
### 组和权限管理
- **创建组**：
  ```plaintext
  /lp creategroup <group>
- **删除组**：
  ```plaintext
  /lp deletegroup <group>
- **为组添加权限**：
  ```plaintext
  /lp group <group> permission set <permission> true/false
- **网页端**：
  ```plaintext
  /lp editor
### 用户和组管理
- **将玩家添加到组**：
  ```plaintext
  /lp user <username> parent add <group>
- **将玩家移出组**：
  ```plaintext
  /lp user <username> parent remove <group>
## EssentialsX 
### 基础功能
- **tp被覆写了，替代可用**：
  ```plaintext
  /minecraft:tp
- **查看余额**：
  ```plaintext
  /balance
- **查看经济排行榜**：
  ```plaintext  
  /baltop
- **设置家**：
  ```plaintext
  /sethome
- **请求传送**：
  ```plaintext
  /tpa <player>
### 管理员指令
- **禁用/启用飞行**：
  ```plaintext
  /fly
## 假人操作指令
### 基本功能
- **在玩家所在位置召唤一个假人**：
```plaintext
  /fp spawn
- **删除假人**：
```plaintext
  /fp kill
- **选中准心指向假人**：
```plaintext
  /fp select
- **查看假人配置**：
```plaintext
  /fp config
按T打开聊天面板可用鼠标进行点击配置

