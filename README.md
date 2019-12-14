# Search搜索导航

**简洁的搜索导航网页，采用原生js编写，即拿及用，可选择不同的搜索引擎，展示网址收藏，查看天气，本地设置，无聊时玩玩小游戏...**

**练手作，最近发现原生js写的太少了，好多东西都快忘了，欢迎给我提意见优化代码**

**顺便一提也想练练ES6语法**

### 预计添加的功能：

1. 多引擎搜索（默认必应）

   预计添加的引擎：

   - 谷歌✅
   - 必应✅
   - 百度✅
   - 搜狗✅
   - ......

2. 常用网址导航

   网址分类：

   - 常用网站❎
   - 视频网站❎
   - 开发网站❎
   - 设计网站❎
   - ......

3. 天气

   调用第三方接口❎

4. 设置

   本地设置（导入，导出）

   - 配色❎

   - 背景❎

   - ......

5. 小游戏

   - 别踩白块❎
   - 贪吃蛇❎
   - 打砖块❎
   - ......
   
6. 随机名言

### 侧边栏切换:

 **效果：**点击星星打开游戏列表，点击旗帜打开收藏网址，点击齿轮设置页面，点击空白部分关闭侧边栏

###  数据格式：

1. #### 搜索引擎相关数据：

   ┌engine（搜索引擎数据）

   ├─name（搜索引擎名称）

   ├─value（搜索引擎值，默认为英文名称）

   ├─href（搜索引擎链接）

   ├─icon（搜索引擎图标）

   └─select（选中状态，默认选中必应搜索）

2. #### 收藏网址相关数据：

   ┌website（收藏网址数据）

   ├─name（网址分类标题）

   ├─value（分类英文名）

   └─content（网址分类内容）

   ​	├─name（网站名称）

   ​	├─href（网站链接）

   ​	└─icon（网站图标）

### 命名规则：

1. 功能名 + 具体名
2. id一般为驼峰命名
3. class一般为中间加 “ - ” 命名

### 后续计划：

1. 使用jQuery重写代码
2. 使用vue重写代码
3. 使用nodejs部署服务器
4. 账号登陆同步书签设置及其他信息功能