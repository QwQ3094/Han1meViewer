# Han1meViewer

![Han1meViewer](https://socialify.git.ci/YenalyLiew/Han1meViewer/image?description=1&descriptionEditable=A%20unofficial%20Hanime1.me%20Application%20for%20Android.&font=KoHo&forks=1&issues=1&language=1&logo=https%3A%2F%2Fuser-images.githubusercontent.com%2F33484515%2F265243370-ade44b35-cfc8-4061-b42a-18bbada38a6d.svg&name=1&owner=1&pattern=Plus&pulls=1&stargazers=1&theme=Dark)

这是一个 [Hanime1](https://hanime1.me/) Android 平台的非官方浏览器。

本项目仅用于学习和交流，不可闭源，严禁商用。

An unofficial Hanime1.me Application for Android.

This project is intended solely for learning and communication purposes. Commercial use is strictly prohibited.

![download times](https://img.shields.io/github/downloads/YenalyLiew/Han1meViewer/total)

------

## 功能

- 主页

  - [x] 头图

  - [x] 推荐

- 新番新闻

  - [x] 月度切换
  - [x] 评论
    - [x] 子评论

- 用户
  - [x] 登入（暂不支持谷歌登录）
  - [x] 登出

- 搜索
  - [x] 高级搜索

- 影片
  - [x] 播放
  - [x] 添加/移除到喜欢列表
  - [x] 添加/移除到稍后观看
  - [x] 添加/移除到播放清单
  - [x] 下载
  - [x] 分享
  - [x] 同系列影片
  - [x] 推荐栏
  - [x] TAG
    - [x] 查看
    - [ ] 修改（做不了，有人机验证）

  - [x] 评论
    - [x] 子评论

- 喜欢列表
  - [x] 删除

- 稍后观看
  - [x] 删除

- 播放清单
  - [x] 修改清单
  - [x] 添加清单
  - [x] 删除清单
  - [x] 删除影片

- 漫画（不打算做）

## 痛点解决

如果你经常用官网，你会发现官网播放影片有一大缺陷：

1. 无法拖拽调整进度

这一点，对于咱们看的**时间敏感型**影片是不可忍受的。特别是当你点击屏幕底下的那个向右快进按钮时，却点到进度条起始部分，是真的🤬！！！

但是本软件不存在这些问题噢。

## 存在问题

本软件和网站深度绑定，如果网站不能用，软件 100% 用不了。除非你下载过影片，那可以看。

不能用日本节点，这是网站自带的拦截。

只要网站添加了 CloudFlare 防护，软件就不能用。

只要该网站大改，我就得花很长时间去重解析网页，这个时候软件就不能用。

~~PS：你还真给我大改了。。~~

## 更新内容

### v0.10.5

**[新增]** 终于有图标了，感谢 [rurires](https://github.com/rurires) 提供！

### v0.10.4

**[修复]** 影片界面调节音量崩溃。

### v0.10.3

**[新增]** 影片可以倍速了，全屏右上角！11种速度任你选择！

### v0.10.2

**[修复]** 打开搜索页面后，加载新的一页会跳回顶部，且错误提示经常抽风。

### v0.10.1

**[修复]** 打开搜索页面，当搜索页面为空或搜索失败时崩溃。

### v0.10.0

**[最新修复]** 打开搜索页面和影片界面崩溃，出现在旧 v0.10.0 版本中。

**[新增]** 播放清单。支持添加、删除、修改等一系列操作。创建播放清单在原网页中是在影片界面添加，而在本软件里更改为在播放清单界面添加。

**[新增]** 转官方网页下载。有些在本软件中无法解析的影片可以转到官方下载页面进行独立下载。

**[新增]** 主页头图显示。

**[改动]** 清单页面删除操作由从右向左滑动修改为长按。

**[优化]** 部分页面的 UI，清单页面影片布局修改为和官网一样的竖版。

**[修复]** 页面刷新后刷新标志不消失。在清单页面删除某项后再次回到该页面又复现。

### v0.9.0

下载界面新增“正在下载”，有进度显示，有通知（前提开通知权限），单线程下载但绝对够用。

影片界面添加厂商信息和“转到网页”按钮。

修复点击 tag 无法进入搜索界面的问题。

部分界面细微调整。

### v0.8.0

修复日期错误 bug，修复视频界面列表全为“现正播放”的 bug。

为增加流畅度，首页纵向视频排列改成横向，可能以后又会改回来。

搜索界面更改搜索栏，之前的太难用了。

标签可折叠。

新增点赞、点踩，且收藏，点赞点踩都会有显示了。

若视频长宽比小于 1 则全屏后为竖屏，反之则为横屏。

### v0.6.0

修复 bug，增加对部分视频的解析。

但目前有个 bug 没修：日期问题。所以你可能发现不少 1970-01-01，特别是在下载页面，那个我以后再搞，目前能用即可。

PS：一年前加了 CloudFlare 防护，然后又把前端改了，当时太忙就索性不搞了。最近暑假闲来无事，发现 CloudFlare 突然没了，索性重新搞了一遍，不过目前还会有一些 bug，但是基本使用还是可以的。而且他们主页改动巨大，但我还是套用的之前的模板，你可能会发现主页和网页版主页可能对应不上，但是不影响。

### v0.5.2

修复“没有登录失败的校验”的问题。

### v0.5.1

修复搜索栏逻辑问题。

### v0.5.0

调整部分 UI。适配 Android 13 通知权限。

修复删除下载影片后列表不能及时更新的问题。修复搜索栏部分逻辑。

修复从全屏切换分辨率后再返回正常界面，影片重置的问题。

修复新番导览日期显示错误的问题。

修改分辨率排列顺序，影片从最高画质开始播放，画质从高到低排列。

增加影片滑动阻尼系数，避免滑动过多导致不能微调。

### v0.4.1

修复未登入前无法查看评论的问题。

### v0.4.0

新增评论功能，包括影片评论，评论回复，子评论回复，但暂不支持点赞点踩。

新增清理缓存（快取）功能。

优化搜索体验，修复了一些小问题。

### v0.3.0

新增更新功能，不过依赖于 Github 的 API，可能有次数限制。

修复搜索时选择 Tag 后保存再打开变成全选的 bug。

优化用户体验。

### v0.2

修复旋转屏幕列表单列显示错乱的问题。

实现了下载功能，支持新番导览小图点击后打开大图的功能，支持保存。未测试过能否断点续传，貌似没实现，如果下载一半关闭程序可能会有 bug 产生，所以建议下载完了再关闭。

最低可用安卓版本从 Android 6.0 修改为 Android 7.0。

### v0.1

第一个版本，实现了基本使用，如观看视频，搜索，添加到历史记录等，暂不支持下载功能。

------

~~这里应该还有东西，以后再写！~~

