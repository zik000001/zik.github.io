---
layout: post
header-img: "img/dolphin.gif" 
title: 视频播放模块测试
date: 2023-06-03 01：32：11 +0800
categories: blog
tags: [测试]
---

测试一下视频播放模块能不能正常运行。

<!-- 在你的HTML文件中，添加一个用于播放器的容器元素 -->
<div id="dplayer"></div>

<!-- 加载DPlayer的js文件 -->
<script src="DPlayer.min.js"></script>

<!-- 在js中初始化DPlayer -->
<script>
    const dp = new DPlayer({
        container: document.getElementById('dplayer'),
        video: {
            url: 'luhua.mp4',
        },
    });
</script>
