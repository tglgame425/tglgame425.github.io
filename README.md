# Hexo Blog

这是一个使用Hexo构建的个人博客项目。

## 项目结构

- `_config.yml`: Hexo主配置文件
- `_config.landscape.yml`: Landscape主题配置文件
- `source/`: 文章源文件目录
  - `_posts/`: 博客文章
- `themes/`: 主题目录
- `scaffolds/`: 文章模板
- `public/`: 生成的静态网站（被Git忽略）
- `.deploy_git/`: 部署临时目录（被Git忽略）

## 快速开始

### 安装依赖

```bash
npm install
```

### 本地运行

```bash
npm run server
# 或
hexo server
```

然后访问 http://localhost:4000

### 生成静态网站

```bash
npm run build
# 或
hexo generate
```

### 部署到GitHub Pages

```bash
npm run deploy
# 或
hexo deploy
```

## 写作

### 创建新文章

```bash
hexo new "文章标题"
```

新文章将在 `source/_posts/` 目录下创建。

### 创建页面

```bash
hexo new page "页面标题"
```

新页面将在 `source/页面标题/` 目录下创建。

## 主题

当前使用的是Hexo默认的Landscape主题。你可以通过修改 `_config.landscape.yml` 文件来自定义主题。

要更换主题，可以从Hexo主题市场选择并安装：

```bash
npm install hexo-theme-主题名称
```

然后在 `_config.yml` 中修改 `theme` 配置项。

## 配置

主要配置文件是 `_config.yml`，你可以在其中设置：
- 网站标题、描述、作者等基本信息
- URL配置
- 分页设置
- 主题选择
- 部署配置

## 许可证

MIT