# 多语言支持使用指南

## ✅ 已完成的功能

我已经为您的个人主页添加了完整的中英文版本切换功能！

### 🌐 双语言页面结构

1. **英文版首页**: `http://localhost:4000/` 或 `https://zhongwanjun.github.io/`
2. **中文版首页**: `http://localhost:4000/cn/` 或 `https://zhongwanjun.github.io/cn/`

### 📁 文件结构

#### 主页文件
- `_pages/about.md` - 英文版主页
- `_pages/about_cn.md` - 中文版主页

#### 组件文件
**英文版组件：**
- `_pages/includes/intro.md` - 英文个人介绍
- `_pages/includes/news_en.md` - 英文新闻
- `_pages/includes/honers_en.md` - 英文荣誉奖项
- `_pages/includes/others_en.md` - 英文教育背景和工作经历

**中文版组件：**
- `_pages/includes/intro_cn.md` - 中文个人介绍
- `_pages/includes/news.md` - 中文新闻
- `_pages/includes/honers.md` - 中文荣誉奖项
- `_pages/includes/others.md` - 中文教育背景和工作经历

**共用组件：**
- `_pages/includes/homepage.md` - 个人链接
- `_pages/includes/pub_wj.md` - 论文列表（英文）

### 🎨 语言切换按钮

- 位于页面顶部的醒目位置
- 美观的按钮样式，支持悬停效果
- 当前语言按钮高亮显示
- 一键切换中英文版本

### 🚀 本地测试

1. 启动本地服务器：
```bash
export PATH="/opt/homebrew/opt/ruby/bin:$PATH"
bundle exec jekyll serve --host 0.0.0.0 --port 4000
```

2. 访问页面：
   - 英文版：http://localhost:4000/
   - 中文版：http://localhost:4000/cn/

### 🔧 自定义内容

#### 修改英文版内容
编辑以下文件：
- `_pages/includes/intro.md` - 修改英文个人介绍
- `_pages/includes/news_en.md` - 修改英文新闻
- `_pages/includes/honers_en.md` - 修改英文荣誉奖项
- `_pages/includes/others_en.md` - 修改英文教育背景

#### 修改中文版内容
编辑以下文件：
- `_pages/includes/intro_cn.md` - 修改中文个人介绍
- `_pages/includes/news.md` - 修改中文新闻
- `_pages/includes/honers.md` - 修改中文荣誉奖项
- `_pages/includes/others.md` - 修改中文教育背景

### 📱 响应式设计

语言切换按钮已经适配了响应式设计，在不同设备上都能正常显示和使用。

### 🎯 SEO优化

- 每个语言版本都有独立的URL
- 搜索引擎可以分别索引中英文版本
- 用户可以直接访问特定语言版本

### 🌟 功能特点

1. **无缝切换**: 点击按钮即可在中英文版本间切换
2. **内容对应**: 每个语言版本都有对应的完整内容
3. **样式统一**: 两个版本保持一致的视觉风格
4. **独立URL**: 每个语言版本都有独立的访问地址
5. **易于维护**: 组件化设计，便于内容更新

## 🎉 总结

您的个人主页现在支持：
- ✅ 完整的中英文版本
- ✅ 美观的语言切换按钮
- ✅ 独立的URL路径
- ✅ 响应式设计
- ✅ 组件化内容管理

现在您可以：
1. 在浏览器中访问 http://localhost:4000 查看效果
2. 点击语言切换按钮测试功能
3. 根据需要编辑相应的组件文件
4. 将更改推送到GitHub以发布到线上

祝您使用愉快！🚀 