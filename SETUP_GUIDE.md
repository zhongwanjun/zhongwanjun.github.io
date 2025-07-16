# 个人主页设置指导

您的个人主页已经基本配置完成！以下是完成设置的最后几个步骤：

## 🎯 必需的设置步骤

### 1. 添加您的头像照片
- 在 `images/` 目录中添加您的头像图片，命名为 `wanjun_profile.jpg`
- 推荐尺寸：500x500像素，jpg或png格式

### 2. 配置Google Scholar自动更新
按照以下步骤设置自动引用统计更新：

1. 找到您的Google Scholar ID：
   - 访问您的Google Scholar页面：https://scholar.google.com/citations?user=FGIZfyQAAAAJ
   - 从URL中复制ID：`FGIZfyQAAAAJ`

2. 在GitHub仓库中设置Secret：
   - 进入您的GitHub仓库的 `Settings -> Secrets and variables -> Actions`
   - 点击 `New repository secret`
   - Name: `GOOGLE_SCHOLAR_ID`
   - Value: `FGIZfyQAAAAJ`

3. 启用GitHub Actions：
   - 进入仓库的 `Actions` 标签页
   - 点击 *"I understand my workflows, go ahead and enable them"*

### 3. 生成网站图标（Favicon）
1. 访问 [favicon-generator](https://redketchup.io/favicon-generator)
2. 上传您的logo图片
3. 下载生成的所有文件到 `images/` 目录

### 4. （可选）配置Google Analytics
如果您想跟踪网站访问统计：
1. 注册Google Analytics
2. 获取跟踪ID
3. 在 `_config.yml` 中更新 `google_analytics_id`

## 🚀 本地测试

1. 安装Jekyll：
```bash
# 安装Ruby和Jekyll
gem install bundler jekyll

# 安装依赖
bundle install
```

2. 启动本地服务器：
```bash
bash run_server.sh
```

3. 在浏览器中访问：http://127.0.0.1:4000

## 📝 内容定制

### 主要文件说明：
- `_config.yml`: 网站基本配置和个人信息
- `_pages/about.md`: 主页入口文件
- `_pages/includes/intro_cn.md`: 个人介绍（已配置）
- `_pages/includes/pub_wj.md`: 论文列表（已配置）
- `_pages/includes/news.md`: 新闻和里程碑（已配置）
- `_pages/includes/honers.md`: 荣誉奖项（需要根据您的情况更新）
- `_pages/includes/homepage.md`: 个人链接（已配置）
- `_pages/includes/others.md`: 教育背景和工作经历（已配置）

### 自定义内容：
1. 编辑 `_pages/includes/honers.md` 添加您的具体荣誉奖项
2. 如需要，可以添加更多section到主页

## 🌐 发布网站

1. 确保您的GitHub仓库名为：`zhongwanjun.github.io`
2. 推送所有更改到main分支：
```bash
git add .
git commit -m "Setup personal homepage"
git push origin main
```

3. 您的网站将在几分钟后可通过 https://zhongwanjun.github.io 访问

## ✅ 已完成的配置

✅ 基本网站配置和个人信息  
✅ 中文个人介绍  
✅ 论文列表（40+篇）  
✅ 新闻和里程碑  
✅ 教育背景和工作经历  
✅ 竞赛奖项  
✅ 本地服务器启动脚本  

## 🔧 故障排除

如果遇到问题：
1. 确保所有依赖都已正确安装
2. 检查文件路径和名称是否正确
3. 查看终端错误信息
4. 参考原始README.md中的详细说明

祝您的个人主页搭建顺利！🎉 