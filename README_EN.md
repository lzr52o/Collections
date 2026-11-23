English · [简体中文](README.md) · [日本語](README_JA.md) · [한국어](README_KO.md) · [Türkçe](README_TR.md)

![Quantumult X Collection](header.png)

<div align="center">

# QuantumultX

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=0366D6&center=true&vCenter=true&width=600&lines=%E6%AC%A2%E8%BF%8E%E6%9D%A5%E5%88%B0+Quantumult+X+%E5%90%88%E9%9B%86%3B%E9%85%8D%E7%BD%AE+%C2%B7+%E8%84%9A%E6%9C%AC+%C2%B7+%E8%BF%9C%E7%A8%8B%3B%E7%82%B9%E5%87%BB%E9%93%BE%E6%8E%A5%E5%8D%B3%E5%8F%AF%E8%AE%A2%E9%98%85)

Configs · Scripts · Remote

![访问量](https://komarev.com/ghpvc/?username=lzr52o&color=0e75b6&style=flat)

</div>
## 📖 Usage Guide

QuantumultX is a collection of configs and scripts for Quantumult X: ready-made config files live in `configs/`, and matching unlock scripts live in `scripts/`. Subscribe with a link — no need to write rules yourself.

### What's in here

- [Collections.conf](https://raw.githubusercontent.com/lzr52o/QuantumultX/master/configs/Collections.conf): App unlock collection — rewrite rules that unlock memberships across many apps.
- [revenuecat-markbuy.qx.conf](https://raw.githubusercontent.com/lzr52o/QuantumultX/master/configs/revenuecat-markbuy.qx.conf): MarkBuy Pro, an all-in-one RevenueCat unlock.
- [unlock-collection.qx.conf](https://raw.githubusercontent.com/lzr52o/QuantumultX/master/configs/unlock-collection.qx.conf): Unlock collection, 24 scripts: ad removal, membership unlocks, price history, Netflix ratings, and the quiz answer helper.
- [v2ex-checkin.qx.conf](https://raw.githubusercontent.com/lzr52o/QuantumultX/master/configs/v2ex-checkin.qx.conf): Automatic daily check-in for V2EX.
- [weibo-enhanced.qx.conf](https://raw.githubusercontent.com/lzr52o/QuantumultX/master/configs/weibo-enhanced.qx.conf): Weibo assistant — removes ads and promoted posts from Weibo.

The 6 scripts in `scripts/` (Adapty, NotBoring, revenuecat.vip, vvebo, PhotoRetouch, TouchreTouch) are unlock scripts for individual apps. They are referenced automatically once you subscribe to a config above, so you usually don't need to add them one by one.

### What you need

- Quantumult X installed on your iPhone or iPad (a paid app on the App Store).
- Network access to GitHub (raw.githubusercontent.com).
- Unlock features need HTTPS decryption (MITM): install the certificate in Quantumult X, then trust it in iOS Settings → General → About → Certificate Trust Settings. Without it, scripts won't work.

### How to subscribe

1. Copy the link of the config you want above.
2. Open Quantumult X, tap "Settings" (bottom right) → "Profiles".
3. Tap the download icon (top right), paste the link, and tap "OK".
4. Once downloaded, tap the new profile to switch to it.

You can also open a config link in Safari and use the share menu to open it in Quantumult X.

### How to use a single script

1. Find the script you want in `scripts/` and copy its raw link, which looks like `https://raw.githubusercontent.com/lzr52o/QuantumultX/master/scripts/<script-name>`.
2. Open Quantumult X, tap "Settings" (bottom right) → "Rewrite".
3. Tap "+" (top right) to add a rewrite rule, paste the link as the script URL, and save.
4. Go back to the home screen and turn on the "Rewrite" switch.

### FAQ

- **Subscribed but nothing happens?** Check three things: did you switch to the new profile, is the "Rewrite" switch on, and is the certificate installed and trusted? If all three are fine, force-close the app and reopen it, or tap "Restore Purchases" and try again.
- **Can't open the link?** Make sure your network can reach GitHub; try opening the link in Safari first.
- **How do I update?** Configs are remote subscriptions — tap the profile in Quantumult X → "Profiles" to refresh to the latest version. No need to subscribe again.
- **How does the V2EX check-in work?** After subscribing to v2ex-checkin.qx.conf, replace `.*` after `User` in the config with your own V2EX username, then open your V2EX profile page once so it can grab your cookie. After that it checks in automatically at 00:10 every day.
- **Netflix ratings not showing?** The Netflix rating in the unlock collection needs an IMDb API key — fill in `ImdbApikeyCacheKey` in BoxJs.
- **Weibo ads still there?** When using the Weibo assistant, turn off the "Compatibility Enhancement" switch in Quantumult X first.

## ⚠️ Usage Notice

This repository is for personal learning and subscription use only. **Reposting, re-uploading, and redistribution are prohibited, as is commercial use.** See [LICENSE](./LICENSE) for details.


## 📊 Statistics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=lzr52o&show_icons=true&theme=radical" width="46%" /><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=lzr52o&layout=compact&theme=radical" width="50%" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=lzr52o&theme=radical" width="96%" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=lzr52o&theme=github-compact" width="100%" />

</div>

## 🛠️ Tech Stack

<div align="center">

![Skill Icons](https://skillicons.dev/icons?i=js,py,git,github,cloudflare,apple,vscode&theme=dark)

</div>

## 😄 Daily Sentence

<div align="center">

<img src="https://www.dmoe.cc/random.php" width="160" height="140" alt="Random anime image" /><img src="https://daily-sentence.lzr52o.workers.dev/sentence" width="440" height="140" alt="Daily sentence" /><img src="https://www.dmoe.cc/random.php?v=2" width="160" height="140" alt="Random anime image" />

</div>

## 🎮 Contribution Graph

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://contrib-rotate.lzr52o.workers.dev/rotate?theme=dark" />
  <source media="(prefers-color-scheme: light)" srcset="https://contrib-rotate.lzr52o.workers.dev/rotate?theme=light" />
  <img alt="Contribution graph" src="https://contrib-rotate.lzr52o.workers.dev/rotate?theme=light" />
</picture>

</div>


![Footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=120&section=footer&text=Quantumult+X+%E5%90%88%E9%9B%86&fontSize=24&fontColor=ffffff)

