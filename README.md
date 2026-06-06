# 喵喵学习小助手

一个基于 Go 的刷题工具，专为福州大学政治选择题设计。当前支持毛概和习概两门课程的选择题练习。

## ✨ 特性

- 📚 多种答题模式（速刷、答题、错题回顾）
- 🎓 当前支持毛概和习概两门课程
- 📊 详细的答题统计和错题管理
- 💾 本地数据持久化，支持多用户
- 🚀 单文件部署，跨平台支持
- 🌐 响应式 Web 界面
- 🐱 萌化的界面设计和交互体验

## 🚀 快速开始

### 直接下载使用（推荐）

本人维护的是旧版本，可从 [155TuT-Releases](https://github.com/155TuT/Meow-Politics-Helper/releases) 下载可执行二进制文件：

- Windows: `Meow-Politics-Helper-windows-amd64.exe`

下载后双击运行，会自动在浏览器中打开学习界面。

### 本地编译运行

如果你熟悉开发，可以克隆仓库后在项目根目录运行：

```powershell
go run .
```

服务默认监听 `http://localhost:8899`，启动后会自动尝试打开浏览器。

需要生成本地可执行文件时运行：

```powershell
go build -o Meow-Politics-Helper.exe .
.\Meow-Politics-Helper.exe
```

## 题库说明

出题老师（仅列姓氏）包括林、王、阮、潘、杨、钱、罗、黄

### 毛概选择题

- 2025上半学年康老师的题目，包含9个章节的选择题
- 2026上半学年康老师的题目，包含8个章节的选择题

### 习概选择题

- 2024下半学年李老师的题目，合计101道选择题
- 2025下半学年杨老师的题目，合计269道选择题；章节划分为导论加17个章节（共18章节）

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

1. Fork 本项目
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 创建 Pull Request

## 📞 联系方式

- 项目地址: [Meow-Politics-Helper](https://github.com/ShaddockNH3/Meow-Politics-Helper)
- 问题反馈: [GitHub Issues](https://github.com/ShaddockNH3/Meow-Politics-Helper/issues)

---

**🎉 祝学习愉快！**
