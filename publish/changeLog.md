### 新增

- 新增多语言设置，目前软件内置了简体中文、繁体中文、英语三种语言，欢迎提交PR翻译更多语言！
- 新增无法打开外部歌单FAQ
- 新增启动参数`search`，使用例子：`.\lx-music-desktop.exe -search="突然的自我 - 伍佰"`
- 新增音频输出设置
- 新增软件内的包括字体在内的界面内容大小调整，现在当窗口大小切换到“较小/大/较大”时，软件内的元素将会适当减小或加大，窗口大小的“小”与“中”内的元素将保持之前的大小暂不做改变
- 新增音源别名，默认将显示别名，想要显示回原名可到设置切换（免责声明：别名仅是本软件用于描述各音源的标签，其名字归版权方所有）
- 新增发现新版本更新失败弹窗的忽略提醒按钮，忽略提醒后，以后同一个版本再失败时将不会弹窗提醒，但仍可到设置-版本更新手动点开更新弹窗查看或恢复提醒
- 新增热搜词，默认关闭，可到设置开启
- 新增历史搜索记录，默认关闭，可到设置开启（右击单个历史记录标签可移除所点击的记录）

### 优化

- 优化月里嫦娥皮肤侧栏鼠标悬浮颜色
- 优化播放进度条的动画效果
- 现在添加下载任务时，后面添加的任务会在列表顶部插入
- 优化歌单打开机制，现在歌单加载失败时会提示加载失败了，并且支持直接打开企鹅、酷我手机分享出来的歌单了
- 优化右上角最小化/关闭按钮布局

### 修复

- 修复歌单详情处于加载状态时无法返回的问题
- 修复鼠标右击复制列表内容时会复制音质标签的问题
- 修复`0.6.2`及以前的版本导出的“所有数据”内的歌曲列表无法导入的问题
- 修复下载列表在某些情况下无法取消全选的问题

### 其他

- 更新Electron到 8.1.1