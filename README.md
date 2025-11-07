# ORSC Tools Query System

一个用于查询和浏览ORSC（Organization Relationship System Coach，组织关系系统教练）工具的信息系统。

## 📋 项目简介

本项目提供了一个交互式的工具查询系统，帮助用户快速查找和了解ORSC培训中使用的各种工具。系统支持：

- 🔍 **搜索功能**：通过工具名称进行模糊搜索
- 🎯 **过滤功能**：按参与者类型、课程、目的等维度过滤
- 🌐 **双语支持**：支持中文和英文切换
- 📱 **响应式设计**：适配桌面和移动设备

## 🚀 快速开始

### 在线访问

访问 [GitHub Pages](https://brookezou.github.io/orsc-tools/) 即可使用。

### 本地运行

1. 克隆仓库：
```bash
git clone https://github.com/brookezou/orsc-tools.git
cd orsc-tools
```

2. 直接在浏览器中打开 `index.html` 文件即可。

## 📁 项目结构

```
orsc-tools/
├── index.html              # 主页面文件
├── README.md               # 项目说明文档
├── .gitignore             # Git忽略文件
└── ORSC-Tools-Summary/    # 工具数据源文件
    └── *.md               # Markdown格式的工具数据
```

## 🛠️ 功能特性

### 当前功能
- ✅ 工具列表展示
- ✅ 工具名称搜索（模糊匹配）
- ✅ 多维度过滤（参与者、课程、目的）
- ✅ 中英文切换
- ✅ 工具详情查看

### 计划功能
- [ ] 完善工具描述和操作步骤
- [ ] 数据导出功能
- [ ] 打印功能
- [ ] 前后端分离架构
- [ ] 微信小程序版本

## 📝 数据说明

工具数据存储在 `index.html` 文件中的JavaScript数据对象中。每个工具包含以下字段：

- **No.**：工具编号
- **Tool Name**：工具名称
- **Tool Description**：工具描述
- **Participants**：适用参与者类型
- **When to use**：使用场景/系统信号
- **Procedures**：操作步骤
- **Purpose**：使用目的
- **in Course**：所属课程
- **Notes**：备注信息

## 🔄 更新说明

### 如何更新工具内容

1. 编辑 `index.html` 文件中的 `rawData` 数组
2. 或者编辑 `ORSC-Tools-Summary` 目录下的Markdown文件
3. 提交更改到GitHub
4. GitHub Pages会自动更新网站

## 🌐 技术栈

- **前端**：HTML5, CSS3, JavaScript (Vanilla)
- **部署**：GitHub Pages
- **数据格式**：JavaScript对象数组

## 📄 许可证

本项目仅供学习和参考使用。

## 👤 作者

- **Brooke Zou** - [GitHub](https://github.com/brookezou)

## 🙏 致谢

感谢ORSC培训体系提供的工具和方法论支持。

---

**最后更新**：2025年11月7日
