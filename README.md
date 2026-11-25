[English](README_EN.md) · 简体中文 · [日本語](README_JA.md) · [한국어](README_KO.md) · [Türkçe](README_TR.md)

![Quantumult X 合集](header.png)

<div align="center">

# QuantumultX

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=0366D6&center=true&vCenter=true&width=600&lines=%E6%AC%A2%E8%BF%8E%E6%9D%A5%E5%88%B0+Quantumult+X+%E5%90%88%E9%9B%86%3B%E9%85%8D%E7%BD%AE+%C2%B7+%E8%84%9A%E6%9C%AC+%C2%B7+%E8%BF%9C%E7%A8%8B%3B%E7%82%B9%E5%87%BB%E9%93%BE%E6%8E%A5%E5%8D%B3%E5%8F%AF%E8%AE%A2%E9%98%85)

配置 · 脚本 · 远程

![访问量](https://komarev.com/ghpvc/?username=lzr52o&color=0e75b6&style=flat)

</div>
## 📖 使用说明

QuantumultX 是 Quantumult X 的配置与脚本合集：`configs/` 里是现成的配置文件，`scripts/` 里是配套的解锁脚本，点链接就能订阅，不用自己写规则。

### 这里有什么

- [Collections.conf](https://raw.githubusercontent.com/lzr52o/QuantumultX/master/configs/Collections.conf)：App 解锁合集，一批应用的会员解锁重写规则。
- [revenuecat-markbuy.qx.conf](https://raw.githubusercontent.com/lzr52o/QuantumultX/master/configs/revenuecat-markbuy.qx.conf)：MarkBuy Pro，RevenueCat 多合一解锁。
- [unlock-collection.qx.conf](https://raw.githubusercontent.com/lzr52o/QuantumultX/master/configs/unlock-collection.qx.conf)：解锁合集，24 个脚本：去广告、解锁会员、历史价格、Netflix 评分、头脑吃鸡答题助手。
- [v2ex-checkin.qx.conf](https://raw.githubusercontent.com/lzr52o/QuantumultX/master/configs/v2ex-checkin.qx.conf)：V2EX 每日自动签到。
- [weibo-enhanced.qx.conf](https://raw.githubusercontent.com/lzr52o/QuantumultX/master/configs/weibo-enhanced.qx.conf)：微博助手，去广告、去推广。

`scripts/` 下的 6 个脚本（Adapty、NotBoring、revenuecat.vip、vvebo、PhotoRetouch、TouchreTouch）是各应用的解锁脚本，订阅上面的配置后会自动引用，一般不用单独加。

### 需要什么

- iPhone 或 iPad 上装好 Quantumult X（App Store 里的付费应用）。
- 网络能打开 GitHub（raw.githubusercontent.com）。
- 解锁类功能要开 HTTPS 解密（MITM）：先在 Quantumult X 里安装证书，再去系统「设置 → 通用 → 关于本机 → 证书信任设置」里信任它，否则脚本不生效。

### 怎么订阅

1. 复制上面想用的配置链接。
2. 打开 Quantumult X，点右下角「设置」→「配置文件」。
3. 点右上角的下载图标，粘贴链接，点「确定」。
4. 下载完后点一下这个配置，切换过去就能用。

也可以在 Safari 里打开配置链接，再用分享菜单选「在 Quantumult X 中打开」。

### 怎么单独用一个脚本

1. 在 `scripts/` 里找到要用的脚本，复制它的 raw 链接，格式是 `https://raw.githubusercontent.com/lzr52o/QuantumultX/master/scripts/脚本名`。
2. 打开 Quantumult X，点右下角「设置」→「重写」。
3. 点右上角「+」新建一条重写规则，把链接填进脚本地址里，保存。
4. 回到首页，把「重写」开关打开。

### 常见问题

- **订阅了但没生效？** 先看三点：配置切过去了没有；首页「重写」开关开着没有；证书装好并信任了没有。都没问题就把 App 关了重开，或点一下「恢复购买」再试。
- **链接打不开？** 先确认网络能打开 GitHub，也可以先在 Safari 里打开链接试试。
- **怎么更新？** 配置是远程订阅的，在 Quantumult X「配置文件」里点一下就能刷新到最新版，不用重新订阅。
- **V2EX 签到怎么用？** 订阅 v2ex-checkin.qx.conf 后，把配置里 `User` 后面的 `.*` 改成你自己的 V2EX 用户名，首次打开一次 V2EX 个人主页让它抓到 Cookie，之后每天 00:10 自动签到。
- **Netflix 评分不显示？** 解锁合集里的 Netflix 评分要 IMDb API key，在 BoxJs 里填 `ImdbApikeyCacheKey` 才能显示。
- **微博广告去不掉？** 用微博助手时，先把 Quantumult X 里的「兼容性增强」开关关掉。

## ⚠️ 使用声明

本仓库仅供个人学习、订阅使用。**禁止转载、搬运、二次分发，禁止商用**，详见 [LICENSE](./LICENSE)。


## 📊 数据统计

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=lzr52o&show_icons=true&theme=radical&custom_title=Lucky%27s%20GitHub%20Stats" width="46%" /><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=lzr52o&layout=compact&theme=radical" width="50%" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=lzr52o&theme=radical" width="96%" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=lzr52o&theme=github-compact" width="100%" />

</div>

## 🛠️ 技术栈

<div align="center">

![Skill Icons](https://skillicons.dev/icons?i=js,py,git,github,cloudflare,apple,vscode&theme=dark)

</div>

## 😄 每日一句

<div align="center">

<img src="https://www.dmoe.cc/random.php" width="160" height="140" alt="二次元随机图" /><img src="https://daily-sentence.lzr52o.workers.dev/sentence" width="440" height="140" alt="每日一句" /><img src="https://www.dmoe.cc/random.php?v=2" width="160" height="140" alt="二次元随机图" />

</div>

## 🎮 贡献图

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://contrib-rotate.lzr52o.workers.dev/rotate?theme=dark" />
  <source media="(prefers-color-scheme: light)" srcset="https://contrib-rotate.lzr52o.workers.dev/rotate?theme=light" />
  <img alt="贡献图" src="https://contrib-rotate.lzr52o.workers.dev/rotate?theme=light" />
</picture>

</div>


## 🙏 致谢

本库收录的脚本与模块均来自以下原作者，感谢他们的辛苦付出：

[chxm1023](https://github.com/chxm1023)、[ddgksf2013（墨鱼）](https://github.com/ddgksf2013)、[NobyDa](https://github.com/NobyDa)、[yichahucha](https://github.com/yichahucha)、[ddm1023](https://github.com/ddm1023)、[彭于晏](https://github.com/fenyaprilia)、[WeiGiegie](https://github.com/WeiGiegie)、[bin64](https://github.com/bin64)、[凉心（52Lxcloud）](https://github.com/52Lxcloud)、[Alex0510](https://github.com/Alex0510)、[Choler](https://github.com/Choler)、[chavyleung](https://github.com/chavyleung)、Liquor030、YG、[leey668](https://github.com/leey668)、[wf021325](https://github.com/wf021325)、[zmqcherish](https://github.com/zmqcherish)

## ⚠️ 免责声明

本库仅供个人学习交流使用，所有脚本与模块的版权归原作者所有；禁止转载、搬运、镜像、二次分发与商用；禁止去除原作者信息；如有侵权请通过 Telegram 私聊机器人 [@ccccccccoBot](https://t.me/ccccccccoBot) 联系删除。


![Footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=120&section=footer&text=Quantumult+X+%E5%90%88%E9%9B%86&fontSize=24&fontColor=ffffff)

