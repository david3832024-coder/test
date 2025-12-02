# AI 写作插件包

这是我的 AI 写作系统使用的 Obsidian 插件包，包含：

1. **obsidian-apple-style** — 排版插件，一键转公众号格式
2. **obsidian-image-uploader** — 图片上传插件，配合 PicGo 使用

## 安装方法

### 方法一：手动安装

1. 下载本仓库所有文件
2. 把 `obsidian-apple-style` 和 `obsidian-image-uploader` 两个文件夹复制到你的 Obsidian 插件目录：
   - Mac: `你的笔记库/.obsidian/plugins/`
   - Windows: `你的笔记库\.obsidian\plugins\`
3. 重启 Obsidian
4. 在设置 → 第三方插件中启用这两个插件

### 方法二：用 Claude Code 一键安装

把下面的提示词发给 Claude Code：

```
帮我安装 Obsidian 插件：

1. 克隆仓库：https://github.com/Ceeon/ai-writing-plugins
2. 把 obsidian-apple-style 和 obsidian-image-uploader 文件夹复制到我的 Obsidian 插件目录
3. 告诉我怎么启用插件
```

## 插件说明

### obsidian-apple-style（排版插件）

功能：
- 主板样式：统一的标题、段落、引用风格
- 排版风格：自定义配色和间距
- 图片水印：自动加头像和备注说明

使用：写完文章后，点击命令面板（Cmd/Ctrl + P），搜索"Apple Style"，选择转换。

### obsidian-image-uploader（图片上传）

功能：粘贴图片自动上传到 PicGo 图床

配置：
1. 先安装 PicGo 并配置好 GitHub 图床
2. 在插件设置中填入 PicGo 的上传地址（默认：http://127.0.0.1:36677/upload）

## PicGo 配置教程

1. 下载 PicGo：https://github.com/Molunerfinn/PicGo/releases
2. 打开 PicGo → 图床设置 → GitHub
3. 配置：
   - 仓库名：你的GitHub用户名/图床仓库名
   - 分支：main
   - Token：去 GitHub Settings → Developer settings → Personal access tokens 生成
   - 存储路径：可留空或填 img/
   - 自定义域名：https://raw.githubusercontent.com/你的用户名/仓库名/main
4. 设为默认图床
5. 打开 PicGo 设置 → 开启 Server

## 作者

AI产品成峰

有问题欢迎留言！
