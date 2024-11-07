---
author: Sat Naing
pubDatetime: 2023-09-27T15:22:00Z
modDatetime: 2024-10-07T09:12:47.400Z
title: How to Fix Meta Ads Manager Problems on Safari
slug: how-to-fix-meta-ads-manager-on-safari
featured: true
draft: false
tags:
  - docs
  - meta-ads
description: Fixing Meta Ads Manager problem on Safari
---

Apple has [released a new feature](https://medium.com/r/?url=https%3A%2F%2Fsupport.apple.com%2Fen-us%2FHT213895) profile for Safari in Sonoma a day ago. And this feature might be a dealbreaker for someone who restrained his desire for a long time. But It may be challenging for digital marketers that frequently use Meta Ads Manager in Safari as their primary browser. You might encounter a slow response while using Ads Manager.

![ads manager 1](https://i.ibb.co.com/yXkWSC3/ads-manager-1.gif)

The issue I have encountered so far is the infinite loading of Ad Account list, as you can see on the image Above. This problem occurs because you might have a lot of Ad Account in your business manager profile, as this problem isn't shown on the other business manager that only has a few ad account.

So how to solve this problem? Of course, we don't want to delete our Ad Account, right?

To solve this problem, please follow these steps

Enable Developer settings in `Safari > Settings > Advanced` and then check the "show feature for web developers" as image shown below.

<a href="https://ibb.co.com/Dr9hpjB"><img src="https://i.ibb.co.com/phfcykH/1-s6-Ii6-RV0ix-ZSTWD-TSKew.png" alt="1-s6-Ii6-RV0ix-ZSTWD-TSKew" border="0"></a>

Then open your Meta Ads Manager, and right click or tap with two fingers and hold on trackpad, and then click `view page source`

<a href="https://ibb.co.com/R72fNMg"><img src="https://i.ibb.co.com/LvSmrq0/1-O1w-J8i335sprj-UMHlp-GY-w.png" alt="1-O1w-J8i335sprj-UMHlp-GY-w" border="0"></a>

A new split window in the bottom will appears, right click and open a new window on script with URL that look like this "static.xx.fbcdn.net".

Click again Safari > Settings for `static.xx.fbcdn.net`

<a href="https://ibb.co.com/vhZGrtJ"><img src="https://i.ibb.co.com/1M85pS9/1-4un-KL3wl-Vz8itx-GHKQ-k3-A.png" alt="1-4un-KL3wl-Vz8itx-GHKQ-k3-A" border="0"></a>

A new pop-up will shows up, and then uncheck the "Enable content blockers".

<a href="https://ibb.co.com/k1skVHp"><img src="https://i.ibb.co.com/5FgtXMd/1-DEVo2-7-ZNivcv1nhbe-4-Q.png" alt="1-DEVo2-7-ZNivcv1nhbe-4-Q" border="0"></a>

Also, don't forget to uncheck content blocker for Meta Ads Manager page.

<a href="https://ibb.co.com/DgQWF1X"><img src="https://i.ibb.co.com/rfH0hQP/1-sao3-J-oix0-XP2838-X90-Fqg.png" alt="1-sao3-J-oix0-XP2838-X90-Fqg" border="0"></a>

By following the comprehensive guide in this tutorial, you'll be better equipped to tackle Ads Manager errors on Safari and keep your ad campaigns running smoothly. Happy advertising!
