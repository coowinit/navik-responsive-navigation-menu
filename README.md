# Navik - 响应式 Header 导航菜单 HTML 组件

Navik 是一套响应式 HTML Header 导航菜单组件，适合用于企业官网、作品集网站、产品展示页、静态模板、后台外壳页面等项目的顶部导航、全屏菜单、侧边栏菜单和 Mega Menu 菜单搭建。

本组件基于 HTML5、CSS3、jQuery、Bootstrap Grid 和 Font Awesome 构建，内置多种导航布局、浅色/深色样式、透明导航、Sticky Header、下拉菜单动画、全屏 Overlay 菜单、侧边栏滑出菜单、固定侧边栏菜单、Mega Menu、菜单图标等示例。

> 说明：本仓库整理自 Navik HTML Header Navigation Menu 静态文件。适合用于学习、二次开发、前端组件集成或 GitHub Pages 演示。公开上传前请确认你拥有该组件的合法授权。

## 组件特点

- 响应式导航菜单，适配桌面端、平板和移动端
- 支持普通顶部导航菜单
- 支持居中 Logo 导航菜单
- 支持全屏 Overlay 导航菜单
- 支持侧边栏滑出菜单
- 支持固定侧边栏菜单
- 支持 Mega Menu 大型菜单
- 支持浅色、深色、透明、背景图、背景色等多种风格
- 支持下拉菜单、二级菜单、三级菜单和垂直子菜单
- 支持菜单图标，可配合 Font Awesome 使用
- 支持多种菜单 Hover 效果和 Dropdown 过渡动画
- 提供编译后的 CSS / JS 文件，可直接引入使用
- 提供 SCSS 源码，方便按项目需求重新编译和定制
- 示例文件完整，便于复制对应结构到自己的页面中

## 适用场景

- 企业官网顶部导航
- 产品展示网站导航
- 作品集 / 摄影 / 设计类网站菜单
- 单页网站导航
- Landing Page 导航栏
- 静态 HTML 模板导航组件
- 需要 Mega Menu 的内容型网站
- 需要移动端汉堡菜单的响应式页面
- 前端导航菜单组件学习与二次开发

## 目录结构

```text
navik-responsive-navigation-menu/
├── index.html                         # 组件演示首页 / Landing Page
├── examples/                          # 64 个导航菜单示例页面
│   ├── 01-default-light.html
│   ├── 02-default-dark.html
│   ├── ...
│   ├── 64-fixed-sidebar-menu-right-background-color.html
│   └── demo/                          # 示例页面使用的图片、Logo、SVG 和演示脚本
├── src/
│   ├── assets/                        # Overlay 菜单使用的 SVG 社交图标资源
│   ├── build/                         # PostCSS / Stylelint 构建配置
│   ├── dist/
│   │   ├── css/                       # 编译后的 Navik CSS 文件
│   │   └── js/                        # Navik 菜单 JS 文件
│   ├── modules/
│   │   ├── bootstrap/                 # Bootstrap 依赖文件
│   │   └── fontawesome/               # Font Awesome 依赖文件
│   ├── scss/                          # Navik SCSS 源码
│   ├── vendor/
│   │   ├── css/reset.css              # 可选 CSS Reset
│   │   └── js/jquery-3.6.0.min.js     # jQuery
│   ├── package.json                   # SCSS 构建脚本与依赖
│   └── package-lock.json
└── README.md
```

## 示例页面清单

### 普通顶部导航

| 文件 | 说明 |
| --- | --- |
| `examples/01-default-light.html` | 默认浅色导航 |
| `examples/02-default-dark.html` | 默认深色导航 |
| `examples/03-default-with-separate-line-light.html` | 浅色导航，菜单分隔线 |
| `examples/04-default-with-separate-line-dark.html` | 深色导航，菜单分隔线 |
| `examples/05-default-transparent.html` | 透明导航 |
| `examples/06-default-overlay-header.html` | Overlay Header 导航 |

### 居中 Logo 导航

| 文件 | 说明 |
| --- | --- |
| `examples/07-center-1-light.html` | 居中 Logo 样式一，浅色 |
| `examples/08-center-1-dark.html` | 居中 Logo 样式一，深色 |
| `examples/09-center-1-with-separate-line-light.html` | 居中 Logo 样式一，浅色分隔线 |
| `examples/10-center-1-with-separate-line-dark.html` | 居中 Logo 样式一，深色分隔线 |
| `examples/11-center-1-transparent.html` | 居中 Logo 样式一，透明导航 |
| `examples/12-center-1-overlay-header.html` | 居中 Logo 样式一，Overlay Header |
| `examples/13-center-2-light.html` | 居中 Logo 样式二，浅色 |
| `examples/14-center-2-dark.html` | 居中 Logo 样式二，深色 |
| `examples/15-center-2-with-separate-line-light.html` | 居中 Logo 样式二，浅色分隔线 |
| `examples/16-center-2-with-separate-line-dark.html` | 居中 Logo 样式二，深色分隔线 |
| `examples/17-center-2-transparent.html` | 居中 Logo 样式二，透明导航 |
| `examples/18-center-2-overlay-header.html` | 居中 Logo 样式二，Overlay Header |

### 全屏 Overlay 菜单

| 文件 | 说明 |
| --- | --- |
| `examples/19-fullscreen-overlay-light.html` | 全屏 Overlay 菜单，浅色 |
| `examples/20-fullscreen-overlay-dark.html` | 全屏 Overlay 菜单，深色 |
| `examples/21-fullscreen-overlay-background-color.html` | 全屏 Overlay 菜单，背景色 |
| `examples/22-fullscreen-overlay-background-image.html` | 全屏 Overlay 菜单，背景图 |
| `examples/23-fullscreen-overlay-center-light.html` | 居中全屏 Overlay 菜单，浅色 |
| `examples/24-fullscreen-overlay-center-dark.html` | 居中全屏 Overlay 菜单，深色 |
| `examples/25-fullscreen-overlay-center-background-color.html` | 居中全屏 Overlay 菜单，背景色 |
| `examples/26-fullscreen-overlay-center-background-image.html` | 居中全屏 Overlay 菜单，背景图 |
| `examples/51-fullscreen-overlay-vertical-submenu-light.html` | 全屏 Overlay 垂直子菜单，浅色 |
| `examples/52-fullscreen-overlay-vertical-submenu-dark.html` | 全屏 Overlay 垂直子菜单，深色 |
| `examples/53-fullscreen-overlay-vertical-submenu-background-color.html` | 全屏 Overlay 垂直子菜单，背景色 |
| `examples/54-fullscreen-overlay-vertical-submenu-background-image.html` | 全屏 Overlay 垂直子菜单，背景图 |
| `examples/55-fullscreen-overlay-center-vertical-submenu-light.html` | 居中全屏 Overlay 垂直子菜单，浅色 |
| `examples/56-fullscreen-overlay-center-vertical-submenu-dark.html` | 居中全屏 Overlay 垂直子菜单，深色 |
| `examples/57-fullscreen-overlay-center-vertical-submenu-background-color.html` | 居中全屏 Overlay 垂直子菜单，背景色 |
| `examples/58-fullscreen-overlay-center-vertical-submenu-background-image.html` | 居中全屏 Overlay 垂直子菜单，背景图 |

### 侧边栏与固定侧边栏菜单

| 文件 | 说明 |
| --- | --- |
| `examples/27-sidebar-slide-menu-light.html` | 侧边栏滑出菜单，浅色 |
| `examples/28-sidebar-slide-menu-dark.html` | 侧边栏滑出菜单，深色 |
| `examples/29-sidebar-slide-menu-background-color.html` | 侧边栏滑出菜单，背景色 |
| `examples/59-fixed-sidebar-menu-light.html` | 左侧固定侧边栏菜单，浅色 |
| `examples/60-fixed-sidebar-menu-dark.html` | 左侧固定侧边栏菜单，深色 |
| `examples/61-fixed-sidebar-menu-background-color.html` | 左侧固定侧边栏菜单，背景色 |
| `examples/62-fixed-sidebar-menu-right-light.html` | 右侧固定侧边栏菜单，浅色 |
| `examples/63-fixed-sidebar-menu-right-dark.html` | 右侧固定侧边栏菜单，深色 |
| `examples/64-fixed-sidebar-menu-right-background-color.html` | 右侧固定侧边栏菜单，背景色 |

### Hover、Dropdown、Mega Menu 与图标示例

| 文件 | 说明 |
| --- | --- |
| `examples/30-navigation-menu-hover-transition-1.html` | 主菜单 Hover 过渡效果一 |
| `examples/31-navigation-menu-hover-transition-2.html` | 主菜单 Hover 过渡效果二 |
| `examples/32-navigation-menu-hover-transition-3.html` | 主菜单 Hover 过渡效果三 |
| `examples/33-navigation-menu-hover-transition-4.html` | 主菜单 Hover 过渡效果四 |
| `examples/34-dropdown-menu-minimal-light.html` | 极简下拉菜单，浅色 |
| `examples/35-dropdown-menu-minimal-dark.html` | 极简下拉菜单，深色 |
| `examples/36-dropdown-with-top-border-light.html` | 下拉菜单顶部边框，浅色 |
| `examples/37-dropdown-with-top-border-dark.html` | 下拉菜单顶部边框，深色 |
| `examples/38-dropdown-with-separate-line-light.html` | 下拉菜单分隔线，浅色 |
| `examples/39-dropdown-with-separate-line-dark.html` | 下拉菜单分隔线，深色 |
| `examples/40-dropdown-menu-transition-fade.html` | 下拉菜单 Fade 过渡 |
| `examples/41-dropdown-menu-transition-scale.html` | 下拉菜单 Scale 过渡 |
| `examples/42-dropdown-menu-transition-flip.html` | 下拉菜单 Flip 过渡 |
| `examples/43-mega-menu-light.html` | Mega Menu，浅色 |
| `examples/44-mega-menu-dark.html` | Mega Menu，深色 |
| `examples/45-mega-menu-fullwidth-light.html` | 全宽 Mega Menu，浅色 |
| `examples/46-mega-menu-fullwidth-dark.html` | 全宽 Mega Menu，深色 |
| `examples/47-navigation-menu-icons.html` | 顶部导航图标示例 |
| `examples/48-dropdown-menu-icons.html` | 下拉菜单图标示例 |
| `examples/49-fullscreen-overlay-menu-icons.html` | 全屏 Overlay 菜单图标示例 |
| `examples/50-sidebar-slide-menu-icons.html` | 侧边栏滑出菜单图标示例 |

## 技术栈与依赖

主题包内已包含主要依赖文件，可以直接本地运行：

- HTML5 / CSS3 / JavaScript
- jQuery 3.6.0
- Bootstrap 5.2.0-beta1
- Font Awesome Free 6.1.1
- SCSS / Sass 源码
- Node.js 构建脚本，用于重新编译 CSS

> 英文文档中部分示例文字仍保留旧版本路径或旧版依赖描述。实际整理时建议以 `src/` 目录中的文件为准。

## 快速开始

### 1. 本地预览

下载或克隆仓库后，直接用浏览器打开：

```text
index.html
```

也可以打开 `examples/` 目录下的任意示例页面，例如：

```text
examples/01-default-light.html
examples/43-mega-menu-light.html
examples/59-fixed-sidebar-menu-light.html
```

如果图片、CSS 或 JS 因浏览器本地安全策略无法正常加载，建议使用本地静态服务器预览：

```bash
npx serve .
```

或使用 VS Code 的 Live Server 插件打开。

### 2. 引入 CSS

在页面 `<head>` 中引入 Bootstrap、Font Awesome 和 Navik 样式：

```html
<link rel="stylesheet" href="src/modules/bootstrap/dist/css/bootstrap.min.css">
<link rel="stylesheet" href="src/modules/fontawesome/css/all.min.css">
<link rel="stylesheet" href="src/dist/css/navik-all.min.css">
```

如果你的项目已经引入 Bootstrap 或 Font Awesome，可以根据实际情况调整路径，避免重复引入。

可选引入 CSS Reset：

```html
<link rel="stylesheet" href="src/vendor/css/reset.css">
```

### 3. 引入 JS

在 `</body>` 前引入 jQuery 和 Navik 菜单脚本：

```html
<script src="src/vendor/js/jquery-3.6.0.min.js"></script>
<script src="src/dist/js/navik.menu.js"></script>
```

### 4. 添加基础 HTML 结构

可以直接复制 `examples/` 中对应页面的 Header 结构到自己的项目中。基础顶部导航结构示例：

```html
<div class="navik-header">
  <div class="container">
    <div class="navik-header-container">
      <div class="logo" data-mobile-logo="images/logo.png" data-sticky-logo="images/logo.png">
        <a href="#"><img src="images/logo.png" alt="Logo"></a>
      </div>

      <div class="burger-menu">
        <div class="line-menu line-half first-line"></div>
        <div class="line-menu"></div>
        <div class="line-menu line-half last-line"></div>
      </div>

      <nav class="navik-menu menu-caret">
        <ul>
          <li class="current-menu"><a href="#">Home</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Services</a>
            <ul>
              <li><a href="#">Dropdown Menu</a></li>
              <li><a href="#">Dropdown Menu</a></li>
              <li><a href="#">Dropdown Menu</a></li>
            </ul>
          </li>
          <li><a href="#">Contact</a></li>
        </ul>
      </nav>
    </div>
  </div>
</div>
```

## 可选 CSS 文件

`src/dist/css/` 中提供了多种编译后的 CSS 文件，可按需引入：

| 文件 | 说明 |
| --- | --- |
| `navik-all.min.css` | 包含全部菜单样式，推荐快速使用 |
| `navik-horizontal-default-menu.min.css` | 普通顶部导航菜单 |
| `navik-horizontal-center-menu.min.css` | 居中 Logo 顶部导航菜单 |
| `navik-overlay-menu.min.css` | 全屏 Overlay 菜单 |
| `navik-overlay-slide-menu.min.css` | Overlay / 侧边栏滑出菜单 |
| `navik-fixed-sidebar-menu.min.css` | 固定侧边栏菜单 |

如果只使用某一种菜单类型，可以引入对应的 CSS 文件，减少页面加载体积。

## 常用 class 说明

| Class | 使用位置 | 说明 |
| --- | --- | --- |
| `center-menu-1` | `.navik-header` | 居中 Logo 导航样式一 |
| `center-menu-2` | `.navik-header` | 居中 Logo 导航样式二 |
| `header-dark` | `.navik-header` | 深色顶部导航 |
| `header-transparent` | `.navik-header` | 透明顶部导航 |
| `header-opacity` | `.navik-header` | 透明叠加背景 |
| `header-shadow` | `.navik-header` | Header 底部阴影 |
| `no-sticky` | `.navik-header` | 禁用 Sticky Header |
| `navik-mega-menu` | `.navik-header` | 启用 Mega Menu 支持 |
| `mega-menu-fullwidth` | `.navik-header` | 全宽 Mega Menu |
| `mega-menu` | `li` | 将某个菜单项设置为 Mega Menu |
| `menu-caret` | `.navik-menu` | 为下拉菜单添加箭头 |
| `separate-line` | `.navik-menu` | 菜单项之间添加分隔线 |
| `menu-hover-2` / `menu-hover-3` / `menu-hover-4` | `.navik-menu` | 不同主菜单 Hover 效果 |
| `submenu-top-border` | `.navik-menu` | 下拉菜单顶部边框 |
| `submenu-list-border` | `.navik-menu` | 下拉菜单列表分隔线 |
| `submenu-scale` | `.navik-menu` | 下拉菜单 Scale 动画 |
| `submenu-flip` | `.navik-menu` | 下拉菜单 Flip 动画 |
| `current-menu` | `li` | 当前菜单项高亮 |
| `submenu-right` | `li` | 子菜单右对齐 |
| `overlay-center-menu` | `.navik-header-overlay` | 全屏菜单内容居中 |
| `menu-slide` | `.navik-header-overlay` | 侧边栏滑出菜单 |
| `navik-menu-icon` | Font Awesome 图标 | 菜单图标样式 |

## Mega Menu 使用说明

如果需要使用 Mega Menu，请在 Header 容器上添加：

```html
<div class="navik-header navik-mega-menu">
```

然后在对应的菜单项 `li` 上添加：

```html
<li class="mega-menu">
```

Mega Menu 内部可以配合 Bootstrap Grid 创建多列布局，例如：

```html
<li class="mega-menu"><a href="#">Mega Menu</a>
  <ul>
    <li>
      <div class="mega-menu-container">
        <div class="row">
          <div class="col-md-3">Column 1</div>
          <div class="col-md-3">Column 2</div>
          <div class="col-md-3">Column 3</div>
          <div class="col-md-3">Column 4</div>
        </div>
      </div>
    </li>
  </ul>
</li>
```

常用 Mega Menu 组件 class：

- `mega-menu-container`：Mega Menu 外层容器
- `mega-menu-box`：内容盒子
- `mega-menu-thumbnail`：缩略图区域
- `mega-menu-heading`：标题
- `mega-menu-desc`：描述文字
- `mega-menu-media`：媒体图文布局
- `mega-menu-list`：列表链接

## 菜单图标

Navik 支持 Font Awesome 图标。示例：

```html
<a href="#">
  <i class="fas fa-home fa-fw fa-sm navik-menu-icon"></i>
  Home
</a>
```

图标可以放在主菜单、下拉菜单、Mega Menu、Overlay Menu 或固定侧边栏菜单中。

## SCSS 自定义与重新编译

如果只需要直接使用组件，可以忽略本节，直接使用 `src/dist/css/` 中已经编译好的 CSS 文件。

如需修改 SCSS 并重新编译，进入 `src/` 目录：

```bash
cd src
npm install
npm run css
```

构建脚本会根据 `src/scss/main.scss` 编译生成 CSS 文件到：

```text
src/dist/css/
```

主要 SCSS 文件包括：

```text
src/scss/_default-menu.scss
src/scss/_center-menu.scss
src/scss/_overlay-menu.scss
src/scss/_overlay-slide-menu.scss
src/scss/_fixed-sidebar-menu.scss
src/scss/_mega-menu.scss
src/scss/_dark-version.scss
src/scss/_menu-icons.scss
src/scss/_breakpoints.scss
src/scss/main.scss
```

> 注意：`package.json` 中使用的是较旧的 `node-sass` 构建方式。如果在新版本 Node.js 中安装失败，建议切换到兼容的 Node.js 版本，或自行升级为 Dart Sass 构建流程。

## GitHub Pages 部署

如果只是作为静态演示页面，可以直接使用 GitHub Pages：

1. 将主题文件上传到 GitHub 仓库根目录。
2. 确保 `index.html` 位于仓库根目录。
3. 打开仓库 `Settings`。
4. 进入 `Pages`。
5. Source 选择 `Deploy from a branch`。
6. Branch 选择 `main`，目录选择 `/root`。
7. 保存后等待 GitHub Pages 生成访问地址。

启用后首页通常类似：

```text
https://your-username.github.io/navik-responsive-navigation-menu/
```

## 自定义建议

### 修改 Logo

在 Header 结构中修改 Logo 图片路径：

```html
<div class="logo" data-mobile-logo="images/logo.png" data-sticky-logo="images/logo.png">
  <a href="#"><img src="images/logo.png" alt="Logo"></a>
</div>
```

常见属性：

- `data-mobile-logo`：移动端 Logo
- `data-sticky-logo`：Sticky Header 状态下的 Logo
- `data-overlay-logo`：Overlay 菜单 Logo

### 修改菜单项

直接修改对应 `<nav>` 中的 `<ul><li><a>` 结构即可。

### 修改颜色、间距和动效

推荐优先修改 SCSS 源码，然后重新编译；如果只是小范围调整，也可以在自己的项目 CSS 中覆盖相关 class。

### 替换图片资源

演示图片主要位于：

```text
examples/demo/images/
```

正式项目中建议替换为你自己的 Logo、背景图、缩略图和 Banner 图片。

## 上线前检查清单

- [ ] 确认是否拥有该组件的公开发布或二次分发授权
- [ ] 替换示例 Logo、图片和占位内容
- [ ] 检查导航链接是否指向真实页面
- [ ] 删除不需要的示例页面或演示图片
- [ ] 删除 `.DS_Store` 等系统缓存文件
- [ ] 检查移动端菜单展开、关闭、下拉层级是否正常
- [ ] 检查 Bootstrap、Font Awesome、jQuery 是否重复引入
- [ ] 如使用 GitHub Pages，确认资源路径是否正确

## 授权说明

本仓库仅对 Navik HTML Header Navigation Menu 文件进行整理和说明。原始模板、组件、图片、字体、图标和第三方插件的版权归其各自作者所有。

如果你计划将该项目公开上传到 GitHub，请先确认购买授权或原始许可是否允许公开发布、二次分发或作为公开仓库展示。

## 第三方资源

主题包中包含或依赖以下第三方资源：

- jQuery
- Bootstrap
- Font Awesome
- Reset CSS

请在正式项目中遵守对应第三方资源的 License 要求。
