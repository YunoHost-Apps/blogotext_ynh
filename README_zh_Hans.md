<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 BlogoText

[![集成程度](https://dash.yunohost.org/integration/blogotext.svg)](https://dash.yunohost.org/appci/app/blogotext) ![工作状态](https://ci-apps.yunohost.org/ci/badges/blogotext.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/blogotext.maintain.svg)

[![使用 YunoHost 安装 BlogoText](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=blogotext)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 BlogoText。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

BlogoText is a lightweight Blog-Engine.

### Features

- Blog with comments and RSS feeds
- Links sharing
- RSS Reader
- Images/Files uploading and sharing
- JSON/ZIP/HTML import-export; WordPress import
- Support Addons


**分发版本：** 3.7.6~ynh6

**演示：** <https://blogotext.org/blog/>

## 截图

![BlogoText 的截图](./doc/screenshots/preview.png)

## :red_circle: 负面特征

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## 文档与资源

- 官方应用网站： <https://blogotext.org/>
- 官方管理文档： <https://github.com/BlogoText/blogotext/wiki>
- 上游应用代码库： <https://github.com/BlogoText/blogotext>
- YunoHost 商店： <https://apps.yunohost.org/app/blogotext>
- 报告 bug： <https://github.com/YunoHost-Apps/blogotext_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/blogotext_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/blogotext_ynh/tree/testing --debug
或
sudo yunohost app upgrade blogotext -u https://github.com/YunoHost-Apps/blogotext_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
