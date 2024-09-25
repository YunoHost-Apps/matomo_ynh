<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Matomo

[![集成程度](https://dash.yunohost.org/integration/matomo.svg)](https://ci-apps.yunohost.org/ci/apps/matomo/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/matomo.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/matomo.maintain.svg)

[![使用 YunoHost 安装 Matomo](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=matomo)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Matomo。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Matomo is the leading Free/Libre open analytics platform. At the end of the five-minute installation process, you will be given a JavaScript code. Simply copy and paste this tag on websites you wish to track and access your analytics reports in real-time.

Matomo aims to be a Free software alternative to Google Analytics and is already used on more than 1,400,000 websites. Privacy is built-in!


**分发版本：** 5.1.2~ynh1

**演示：** <https://demo.matomo.org>

## 截图

![Matomo 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://matomo.org>
- 官方管理文档： <https://matomo.org/docs>
- 上游应用代码库： <https://github.com/matomo-org/matomo>
- YunoHost 商店： <https://apps.yunohost.org/app/matomo>
- 报告 bug： <https://github.com/YunoHost-Apps/matomo_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/matomo_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/matomo_ynh/tree/testing --debug
或
sudo yunohost app upgrade matomo -u https://github.com/YunoHost-Apps/matomo_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
