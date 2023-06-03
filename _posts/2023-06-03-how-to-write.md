---
layout: post
header-img: "img/dolphin.gif" 
title: 视频播放模块测试
date: 2023-06-03 01：32：11 +0800
categories: blog
tags: [测试]
---

测试一下视频播放模块能不能正常运行。

npm install dplayer --save

<div id="dplayer"></div>

<script src="DPlayer.min.js"></script>

<script>
    const dp = new DPlayer({
        container: document.getElementById('dplayer'),
        video: {
            url: 'luhua.mp4',
        },
    });
</script>
