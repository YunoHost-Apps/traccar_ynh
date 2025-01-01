<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Traccar

[![集成程度](https://apps.yunohost.org/badge/integration/traccar)](https://ci-apps.yunohost.org/ci/apps/traccar/)
![工作状态](https://apps.yunohost.org/badge/state/traccar)
![维护状态](https://apps.yunohost.org/badge/maintained/traccar)

[![使用 YunoHost 安装 Traccar](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=traccar)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Traccar。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Traccar is an open source GPS tracking system. It supports more than 200 GPS protocols and more than 2000 models of GPS tracking devices.

### Features

- Real-time GPS tracking
- Driver behaviour monitoring
- Detailed and summary reports
- Geofencing functionality
- Alarms and notifications
- Account and device management
- Email and SMS support


**分发版本：** 6.5~ynh1

**演示：** <https://www.traccar.org/demo-server/>

## 截图

![Traccar 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://www.traccar.org/>
- 官方管理文档： <https://www.traccar.org/documentation/>
- 上游应用代码库： <https://github.com/traccar/traccar>
- YunoHost 商店： <https://apps.yunohost.org/app/traccar>
- 报告 bug： <https://github.com/YunoHost-Apps/traccar_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/traccar_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/traccar_ynh/tree/testing --debug
或
sudo yunohost app upgrade traccar -u https://github.com/YunoHost-Apps/traccar_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
