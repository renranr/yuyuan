# 公开仓库部署指南

## 🚀 推送到GitHub公开仓库

### 1. 初始化仓库
```bash
cd /mnt/e/yuyuan-public
git init
git remote add origin https://github.com/renranr/yuyuan.git
```

### 2. 复制展示内容
```bash
# 从准备目录复制所有文件到公开仓库
cp -r /mnt/e/xinyu/yuyuan-public-content/* /mnt/e/yuyuan-public/
```

### 3. 添加和提交
```bash
cd /mnt/e/yuyuan-public
git add .
git commit -m "初始化遇愿项目展示仓库

- 添加完整的项目介绍和功能说明
- 准备应用截图和演示文档结构  
- 创建APK下载和发布说明
- 专注于项目展示，不包含源代码

🤖 Generated with [Claude Code](https://claude.ai/code)

Co-Authored-By: Claude <noreply@anthropic.com>"
```

### 4. 推送到GitHub
```bash
git branch -M main
git push -u origin main
```

## 📋 后续更新流程

### 添加应用截图
1. 制作应用截图 (1080x1920)
2. 保存到 `images/` 目录
3. 更新 `docs/screenshots.md`
4. 提交推送更新

### 发布APK版本
1. 构建生产版本APK
2. 在GitHub创建Release
3. 上传APK文件
4. 使用 `RELEASE_TEMPLATE.md` 编写发布说明

### 更新项目信息
1. 修改README.md中的项目描述
2. 更新技术栈和功能说明
3. 添加实际使用数据和反馈
4. 提交推送更新

## 🎯 内容检查清单

在推送前确认：
- [ ] README.md 信息完整准确
- [ ] 联系方式已更新为真实信息
- [ ] 图片链接路径正确
- [ ] 不包含任何源代码
- [ ] 不包含敏感配置信息
- [ ] 所有文档语言统一规范

## 📞 维护建议

- 定期更新项目状态和成果
- 及时回复GitHub Issues和讨论
- 保持APK版本的及时更新
- 根据用户反馈优化展示内容

---

**注意**: 这个仓库只用于项目展示和APK分发，不包含源代码。