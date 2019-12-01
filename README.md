### ECNU-Jump

#### 预期目标

+ 1.修改游戏逻辑BUG
+ 2.增加辅助线功能
+ 3.增加学校元素方块
+ 4.方块上方添加对应的英文介绍
+ 5.规划一条路径，循环路径。



#### PC端展示:

- 下载源码后使用wing打开(直接将'跳一跳白鹭源码'文件夹拖到wing编辑器中即可)
- 点击调试运行(左上方小火箭左边的小爬虫按钮)或者直接在当前文件目录下使用命令:egret run

#### 微信开发工具展示

- 首先修改'跳一跳白鹭源码'下index.html中的一行代码

  ```
  data-scale-mode="showAll"
  修改为:
  data-scale-mode="fixedWidth"
  ```

- 修改 egretProperties.json(也可以去EgretLauncher项目下去直接设置发布模式,下面代码会自动修改)

  ```
  "target": {
      "current": "web"
    },
  修改为
  "target": {
      "current": "wxgame"
    },
  ```

- 之后在当前目录下使用命令:egret run



