# 基于Python的飞机大战游戏
## 一、游戏基本设定
### 1.1 游戏设定
1. 每消灭1架小飞机得1000分，中飞机5000分，大飞机10000分
2. 每10秒有一个随机的道具补给，分为两种道具，全屏炸弹和超级子弹 
3. 全屏炸弹最多只能存放3枚，超级子弹可以维持15秒钟的效果 
4. 游戏将根据分数来逐步提高难度，难度的提高表现为飞机数量的增多或速度的加快 
5. 为中飞机和大飞机增加了血槽的显示，可以直观的显示敌机被消灭的进度
6. 游戏结束后会显示历史最高分数
### 1.2 我方设定
1. 我方有3次机会，每次被敌人消灭，新诞生的飞机会有3秒钟的安全期 
2. 我方的子弹的射程并非全屏，而大概是屏幕长度的80% 
### 1.3 敌方设定
1. 敌方共有大中小3款飞机，分为高中低3种速度 
2. 消灭小飞机需要1发子弹，中飞机需要10发，大飞机需要20发子弹
## 二、代码文件说明
|   文件名    |               说明               |
| :---------: | :------------------------------: |
|  __main__   | 主文件，若想开始游戏请运行此文件 |
| __myplane__ |         我方飞机相关设定         |
|  __enemy__  |         敌方飞机相关设定         |
| __bullet__  |             子弹设定             |
| __supply__  |             补给设定             |
