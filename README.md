## 仓库由来

本仓库存放的是[Xhofe/alist-web](https://github.com/Xhofe/alist-web)项目的release文件。

并修改`index.html`文件中引用的静态资源的地址为本仓库，使用GitHub中国大陆CDN **jsDelivr**

以此提高小带宽服务器的访问质量，节约带宽、流量。

1Mbps服务器修改前初次访问大约需要15-20秒，修改后仅需1.5-2秒，为之前的十分之一（1.0.3版本）。

## 如何使用

[下载](https://cdn.jsdelivr.net/gh/imldy/alist-web-dist@main/index.html)`index.html`文件，并替换你原来的`index.html`

## 修改的静态资源

`index.html`文件中

| 原地址                                 | 修改后地址                                                   |
| -------------------------------------- | ------------------------------------------------------------ |
| /static/css/chunk-vendors.8f913079.css | https://cdn.jsdelivr.net/gh/imldy/alist-web-dist@main/static/css/chunk-vendors.8f913079.css |
| /static/js/chunk-vendors.131f0f41.js   | https://cdn.jsdelivr.net/gh/imldy/alist-web-dist@main/static/js/chunk-vendors.131f0f41.js |

## 感谢

[Xhofe/alist-web](https://github.com/Xhofe/alist-web)

[jsDelivr - A free, fast, and reliable CDN for open source](https://www.jsdelivr.com/)