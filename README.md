# poem
# Random Chinese Poem

一个极简的随机中国古诗词网页。每次打开或点击“再来一首”，都会随机展示一句古诗词。

## 功能

- **随机古诗**：每次刷新或点击按钮，随机获取一句中国古诗词
- **一键复制**：将当前诗句与出处复制为 `诗句—————作者《标题》` 格式
- **夜间模式**：纯黑背景 + 白色衬线字体，护眼且贴合古诗意境
- **加载动画**：入场时的旋转圆环过渡，衔接自然
- **移动端适配**：手机上也能流畅使用

## 技术栈

- 纯 HTML + CSS + JavaScript，单文件，无需构建
- 数据源：[今日诗词 API](https://www.jinrishici.com/)（`v1.jinrishici.com/all.json`）
- 托管：Cloudflare Pages

## 部署

### 方式一：Cloudflare Pages（推荐）

1. Fork 或克隆本仓库
2. 登录 [Cloudflare Dashboard](https://dash.cloudflare.com/)
3. 进入 **Workers 和 Pages** → **创建** → **Pages**
4. 连接本仓库，构建配置**全部留空**
5. 点击部署，等待完成

### 方式二：直接打开

现已托管GitHub pages网址.(https://xk-pro.github.io/poem/)


## 说明

- 本项目的诗词数据来自今日诗词 API，接口本身可能按天或按 Token 缓存，连续点击“再来一首”有概率返回相同诗句，属正常现象。
- 本项目开发使用deepseek ai进行编程辅助
- 当前接口返回的是单句诗，不包含全文，因此“显示全文”按钮默认隐藏。

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
