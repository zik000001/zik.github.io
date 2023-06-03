---
layout: post
header-img: "img/dolphin.gif" 
title: 视频播放模块测试
date: 2023-06-03 01：32：11 +0800
categories: blog
tags: [测试]
---

测试一下视频播放模块能不能正常运行。


 <script>
                                                var downurls = "&#30435;&#31105;〜&#30007;の&#24615;&#22900;○になった&#31169;〜&#30342;&#26376;ひかる$https://github.com/zik000001/zik.github.io/blob/master/_posts/luhua.mp4#https://github.com/zik000001/zik.github.io/blob/master/_posts/luhua.mp4";
                                                var httpurl = "https://github.com/zik000001/zik.github.io/blob/master/_posts/luhua.mp4";
                                                var downserver = "";
                                                var downarr = downurls.split('#');
                                                var downinfo, ys_url, thunder_url, qq_url, yb_url, str;
                                                for (i = 0; i < downarr.length - 1; i++) {
                                                    downinfo = downarr[i].split('$');
                                                    ys_url = urlconvert(downinfo[1], 'ys');
                                                    thunder_url = urlconvert(ys_url, 'xl');
                                                    qq_url = urlconvert(ys_url, 'qq');
                                                    yb_url = thunder_url;
                                                    if (ys_url.indexOf('ed2k') > -1 || ys_url.indexOf('magnet') > -1) {
                                                        yb_url = encodeURIComponent(decodeURIComponent(ys_url));
                                                    }
                                                    str = '<div class="download"><input style="outline-style: none ;border: 1px solid #ccc; border-radius: 3px;padding: 10px;width: 50%;font-size: 14px;"type="text" value="' + thunder_url + '"> <a id="thUrlid' + downinfo[0] + '" href="' + thunder_url + '" thunderHref="' + thunder_url + '" thunderPid="38042" thunderResTitle="">&#36805;&#38647;&#19979;&#36733; </a></div> ';
                                                    document.write(str);
                                                }
                                                </script>
