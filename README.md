# ➡️ [w.0hanxi.info](https://w.hanxi.infon) - 个人书签网址导航

本项目是 [webstack.cc](https://github.com/WebStackPage/WebStackPage.github.io) 的 [Jekyll](https://jekyllrb.com/) 版。

额外的书签生成网址导航工具 [w.hanxi.info](https://w.hanxi.info/convert.html)

用到了icon服务器提取网站标题：https://github.com/mat/besticon

```
    iconserver:
        container_name: iconserver
        image: matthiasluedtke/iconserver
        network_mode: bridge
        restart: always
        ports:
            - "2113:80"
        environment:
            - SERVER_MODE=download
            - PORT=80

```

> 这是一个纯静态的网址导航网站，内容均由 [viggo](http://viggoz.com/) 收集并整理。项目基于bootstrap前端框架开发。

![](https://w.hanxi.info/assets/images/preview.gif)
