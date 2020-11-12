---
title: "JetBrains"
date: 2020-11-13T00:14:11+08:00
draft: false
---

- datagrip
    - url后面增加即可解决 `?serverTimezone=Asia/Shanghai&characterEncoding=utf8`
        - 出自 https://songzixian.com/windowstooluse/769.html

- jetBrains 30 天重置
    - http://idea.npegeek.com/limitless.html    （写了几个不同平台的脚本）（会被检测到）
    - https://www.quora.com/Is-there-a-way-to-extends-trial-period-of-Jetbrains-IDE
    - https://tsukie.com/en/technologies/how-to-reset-trial-time-for-jetbrains-products/
    - 我的操作 rm -rf %APPDATA%/JetBrains/* 
        - wdtmd 这法子不能用了
- jetBrains 注册码
    - http://idea.medeming.com/jihuoma/
- jetBrains 清除注册表（regedit ）
    - HKEY_CURRENT_USER\Software\JavaSoft
        - HKEY_CURRENT_USER\Software\JetBrains 下只有 tollbox ，so，不是这个