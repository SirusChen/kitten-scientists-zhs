# 小猫科学家

<p align="center"><img src="https://i.imgur.com/AWHGIGH.jpg" /></p>


小猫科学家（KS）是一个自动化脚本，提供给好玩的网页模拟建设游戏[猫国建设者](https://zhaolinxu.github.io/cat-zh/)。

### 安装方法一

双击鼠标选中下面的JavaScript代码，复制，然后在浏览器上创建一个新书签，并将代码粘贴在地址栏里面：

### 中文版：

    javascript:(function(){var d=document,s=d.createElement('script');s.src='https://zhaolinxu.github.io/kitten-scientists-zhs/kitten-scientists.user.js';d.body.appendChild(s);})();

### 英文版：

    javascript:(function(){var d=document,s=d.createElement('script');s.src='https://rawgit.com/cameroncondry/cbc-kitten-scientists/master/kitten-scientists.user.js';d.body.appendChild(s);})();

如图：

<img src="help.png" alt="" />

以后每次玩游戏，直接在游戏界面点这个书签，就会直接加载小猫科学家进来。

### 安装方法二

双击选中代码，然后复制：

    document.body.appendChild(document.createElement('script')).src='https://zhaolinxu.github.io/kitten-scientists-zhs/kitten-scientists.user.js';

如图：

<img src="help2.jpg" alt="F12大法截图" />

### 安装方法三

您还可以用户名管理员的身份，永久安装小猫科学家。

- 在 **Firefox**浏览器, 你可以安装插件 [Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/).
- 在 **Chrome** 和 **Opera**浏览器, 你可以安装插件[Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo).

然后，你可以 [点击打开脚本](https://zhaolinxu.github.io/kitten-scientists-zhs/kitten-scientists.user.js) ，然后你应该可以看到安装提示。 

## 功能

- Several UI adjustments (depending on selected theme).
- Automates:
    - 建筑
    - 工艺
    - 狩猎
    - 赞美太阳
    - 举办节日

### 建筑

By default, buildings are built if their required resources are at 75% of their storage capacity. For space structures,
the default threshold is 95%.

### 工艺

Craftable resources are crafted when the resources required for the craft are at 95% of their storage capacity.
 
Additionally, you can set a *consumption rate* (60% by default). This defines how much of the available resources can be
used for crafting.

### 贸易

Trades happen when the traded resource is at 95% of the storage capacity. The trades are optimized to only happen during
seasons when the trade is most effective.

### 狩猎

Hunts when catpower is at 95% capacity and builds luxury items before the hunt is sent.

### 赞美太阳

Praises when faith is at 99% capacity.

### 游戏日志

Automatically observes astronomical events.

## Contributors

If you would like to contribute to the Kitten Scientists, then you can do so in these ways:

- Submit issues or bugs you find, or functionality that would improve the project.
- Fork the repository, add some functionality, then submit a pull request.

Thanks to these past and present contributors!

- [adituv](https://github.com/adituv)
- [Azulan](https://www.reddit.com/user/Azulan)
- [carver](https://github.com/carver)
- [coderpatsy](https://github.com/coderpatsy)
- [DirCattus](https://www.reddit.com/user/DirCattus)
- [DrGaellon](https://github.com/DrGaellon)
- [enki1337](https://github.com/enki1337)
- [FancyRabbitt](https://www.reddit.com/user/FancyRabbitt)
- [gnidan](https://github.com/gnidan)
- [jacob-keller](https://github.com/jacob-keller)
- [jcranmer](https://github.com/jcranmer)
- [magus424](https://github.com/magus424)
- [mammothb](https://github.com/mammothb)
- [Mewnine](https://www.reddit.com/user/Mewnine)
- [mjdillon](https://github.com/mjdillon)
- [mmccubbing](https://github.com/mmccubbing)
- [oliversalzburg](https://github.com/oliversalzburg)
- [pefoley2](https://www.reddit.com/user/pefoley2)
- [sapid](https://github.com/sapid)
- [sjdrodge](https://github.com/sjdrodge)
- [SphtMarathon](https://www.reddit.com/user/SphtMarathon)
- [trini](https://github.com/trini)
