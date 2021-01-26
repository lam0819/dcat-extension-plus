# Dcat Plus

为 DcatAdmin 后台添加增强配置的功能。修改过程利用 DcatAdmin 自带的 `admin_setting()` 方法实现，不会硬编码修改任何 config 文件或者 .env 文件。

## 安装方式

### 本地安装

下载本项目 `.zip` 包，在 `DcatAdmin` 后台的 `扩展` 菜单中，通过上传进行安装。

### Composer 安装

`composer require celaraze/dcat-extension-plus`

### 使用

在菜单 `扩展` 中启用扩展后，会自动添加名为 `站点配置` 的菜单。

### 功能

#### 站点配置

站点标题

站点 LOGO

站点微缩 LOGO

站点静态资源 URL

调试模式

#### UI优化

移除底部授权

头部块状显示

侧栏缩进增大
