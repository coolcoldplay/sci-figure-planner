# 🔬 SCI Figure Planner / SCI论文图片排版规划工具

<p align="center">
  <img src="https://img.shields.io/badge/版本-4.0-blue.svg" alt="版本">
  <img src="https://img.shields.io/badge/语言-中文%20%7C%20English-green.svg" alt="语言">
  <img src="https://img.shields.io/badge/许可证-MIT-orange.svg" alt="许可证">
  <img src="https://img.shields.io/badge/平台-Web-purple.svg" alt="平台">
</p>

<p align="center">
  <b>一款专为科研人员设计的SCI论文Figure排版规划工具</b>
</p>

<p align="center">
  在线体验：<a href="https://coolcoldplay.github.io/sci-figure-planner/">https://coolcoldplay.github.io/sci-figure-planner/</a>
</p>

---

## ✨ 功能特性

### 🎨 面板设计
- **可视化拖拽** - 自由拖拽调整面板位置和大小
- **智能对齐** - 自动吸附对齐辅助线，精确排版
- **网格系统** - 可调节的网格系统，确保对齐整齐
- **多种状态** - 未开始/进行中/已完成/需重做，直观追踪进度

### 📐 智能排版
- **一键排版** - 根据面板大小和字母顺序智能排列
- **保持比例** - 智能识别宽面板/高面板，合理分配空间
- **预览确认** - 排版前预览效果，满意后再应用

### 🖌️ 格式刷
- **单击模式** - 点击一次，应用一次后自动退出
- **双击模式** - 连续应用格式到多个面板，按Esc退出

### 🎬 展示模式
- **全屏展示** - 隐藏编辑界面，专注查看Figure效果
- **多Figure切换** - 左右箭头或键盘切换不同Figure
- **边框显示** - 清晰展示Figure边界

### 📁 文件关联
- **本地文件夹链接** - 为每个面板关联本地实验数据文件夹
- **快速访问** - 双击面板快速打开关联文件夹

### 🌍 多语言支持
- 中文 / English 一键切换

### 🌙 暗黑模式
- 护眼的深色主题，适合长时间工作

### 💾 数据管理
- **自动保存** - 数据自动保存到浏览器本地存储
- **导入/导出** - JSON格式项目文件，方便备份和分享
- **导出MD** - 导出Markdown格式的Figure报告
- **导出SVG** - 导出矢量图格式

---

## 🚀 快速开始

### 在线使用
直接访问：[https://你的用户名.github.io/sci-figure-planner/](https://你的用户名.github.io/sci-figure-planner/)

### 本地使用
1. 下载 `index.html` 文件
2. 双击用浏览器打开即可使用
3. 无需安装任何依赖，无需网络连接

---

## 📖 使用指南

### 基本操作

| 操作 | 说明 |
|------|------|
| 新建Figure | 点击「新建Figure」按钮，设置画布大小和布局模板 |
| 添加面板 | 点击「添加面板」或选中后点击「复制面板」 |
| 移动面板 | 拖拽面板顶部的标签栏 |
| 调整大小 | 拖拽面板边缘的调整手柄 |
| 选择面板 | 单击选择，Ctrl+单击多选 |
| 框选面板 | Ctrl+拖拽进行框选 |
| 删除面板 | 选中后按Delete键或点击删除按钮 |

### 快捷键

| 快捷键 | 功能 |
|--------|------|
| `Ctrl + 滚轮` | 缩放画布 |
| `Shift + 拖拽` | 平移画布 |
| `方向键` | 微调选中面板位置 |
| `Ctrl + G` | 显示/隐藏网格 |
| `Ctrl + 点击` | 多选面板 |
| `Delete` | 删除选中面板 |
| `Esc` | 退出当前模式（展示模式/命名模式/格式刷） |
| `← →` | 展示模式下切换Figure |

### 面板属性

选中面板后，右侧属性面板可以编辑：

- **面板标签** - A, B, C... 或自定义
- **位置/尺寸** - 精确数值调整
- **进度状态** - 追踪实验进度
- **面板类型** - Western blot、流式细胞术、免疫荧光等
- **面板图片** - 上传实验结果图片
- **矩阵阵列模式** - 适合免疫荧光/流式多通道展示
- **内容描述** - 记录面板内容说明
- **实验方法** - 记录实验方法和步骤
- **关联文件夹** - 链接本地实验数据文件夹

---

## 🎯 适用场景

- 📝 SCI论文Figure规划和设计
- 🔬 实验进度可视化追踪
- 👥 课题组协作讨论Figure布局
- 📊 学术报告和演示准备
- 🎓 毕业论文图表规划

---

## 🛠️ 技术栈

- **纯前端实现** - HTML5 + CSS3 + JavaScript
- **无框架依赖** - 原生JS，加载快速
- **响应式设计** - 适配不同屏幕尺寸
- **本地存储** - LocalStorage 自动保存

---

## 📁 项目结构

```
sci-figure-planner/
├── index.html      # 主程序文件（包含所有代码）
├── README.md       # 项目说明文档
└── LICENSE         # 许可证文件
```

---

## 🤝 贡献指南

欢迎提交 Issue 和 Pull Request！

1. Fork 本仓库
2. 创建你的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交你的改动 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开一个 Pull Request

### 改进建议

如果你有任何建议或发现bug，欢迎：
- 提交 [Issue](../../issues)
- 发送邮件至：你的邮箱@example.com

---

## 🙏 致谢

感谢所有为科研事业努力的研究者们！

如果这个工具对你有帮助，欢迎：
- ⭐ 给项目点个 Star
- 📢 分享给你的同事和朋友
- 💬 提出宝贵的改进建议

---

## 📞 联系作者

- 📧 Email: 1356496415@qq.com

---

<p align="center">
  Made with ❤️ for Researchers
</p>

<p align="center">
  如果觉得有用，请给个 ⭐ Star 支持一下！
</p>
