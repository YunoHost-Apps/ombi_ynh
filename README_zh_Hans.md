<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Ombi

[![集成程度](https://apps.yunohost.org/badge/integration/ombi)](https://ci-apps.yunohost.org/ci/apps/ombi/)
![工作状态](https://apps.yunohost.org/badge/state/ombi)
![维护状态](https://apps.yunohost.org/badge/maintained/ombi)

[![使用 YunoHost 安装 Ombi](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ombi)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Ombi。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Ombi is a self-hosted web application that automatically gives your shared Plex or Emby users the ability to request content by themselves! Ombi can be linked to multiple TV Show and Movie DVR tools to create a seamless end-to-end experience for your users.


**分发版本：** 4.47.1~ynh2

**演示：** <https://app.ombi.io/landingpage>

## 截图

![Ombi 的截图](./doc/screenshots/screenshot.jpg)

## 文档与资源

- 官方应用网站： <https://ombi.io/>
- 官方管理文档： <https://docs.ombi.app/guides/installation/>
- 上游应用代码库： <https://github.com/Ombi-app/Ombi>
- YunoHost 商店： <https://apps.yunohost.org/app/ombi>
- 报告 bug： <https://github.com/YunoHost-Apps/ombi_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/ombi_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/ombi_ynh/tree/testing --debug
或
sudo yunohost app upgrade ombi -u https://github.com/YunoHost-Apps/ombi_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
