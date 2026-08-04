# 📊 PPT 代码快捷运行器

> 一款面向教育工作者的免费 PPT 辅助生成工具，无需编程基础，粘贴 AI 代码即可一键生成 PPT。

针对传统PPT制作效率低下与市面AI生成工具收费过高的双重问题，本软件以完全免费、零门槛的方式，为教育工作者提供高效便捷的PPT生成解决方案。

[![Python](https://img.shields.io/badge/Python-3.6+-blue.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-PolyForm%20Noncommercial-red.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Windows-blue.svg)](https://www.microsoft.com/windows)

---

## ✨ 特色

- 🎯 **零门槛**：无需安装 Python，无需编程知识
- ⚡ **高效率**：粘贴 AI 代码，3 秒生成 PPT
- 🆓 **完全免费**：面向教育工作者，永久免费
- 📦 **便携版**：解压即用，无需安装
- 🤖 **AI 友好**：完美配合 DeepSeek、ChatGPT 等 AI 工具

## 📷 界面预览

<img width="865" height="785" alt="image" src="https://github.com/user-attachments/assets/067d2c0f-0bc8-41b1-bf0e-89ef6ae652bd" />

---

## 🚀 快速开始

### 下载与使用

1. **下载**：从 [Releases](https://github.com/你的用户名/ppt-code-runner/releases) 下载最新版本
2. **解压**：解压到任意文件夹
3. **运行**：双击 `PPT代码运行器.exe`
<img width="723" height="584" alt="image" src="https://github.com/user-attachments/assets/b70aec84-c1fe-449d-be58-f16d0ac9b348" />


### 让AI制作PPT
流程：① 向 AI 发送提示词 → ② 复制 AI 生成的代码 → ③ 粘贴到工具 → ④ 点击运行 → ⑤ PPT 自动打开 ✅

<img width="865" height="425" alt="image" src="https://github.com/user-attachments/assets/432c7356-0e06-4f1c-bdb9-07a1413946e1" />


为保持稳定，建议基于下图的模板进行增加其他的要求

<img width="865" height="293" alt="image" src="https://github.com/user-attachments/assets/fa45ba8b-89a8-4e30-a134-102703aa2797" />


**推荐 AI 提示词模板：**

```text
请帮我制作一份关于 [你的主题] 的 PPT，使用 python-pptx 库生成代码。
要求：
1. 使用系统默认字体
2. 保存在桌面
3. 美化润色，极具吸引力

[在这里补充你的其他要求，如：页数、配色、内容结构等]
```


单缶复制后


<img width="865" height="636" alt="image" src="https://github.com/user-attachments/assets/0db761b4-094d-481e-996b-84fef278d09a" />


<img width="865" height="425" alt="image" src="https://github.com/user-attachments/assets/7c8ac555-9507-4ccf-8d1d-ea82eae980dc" />


切换至软件界面，粘贴即可。
<img width="865" height="785" alt="image" src="https://github.com/user-attachments/assets/2af33327-d67e-4121-9543-04bbe36d98a1" />


单击"运行并生成ppt"


<img width="433" height="114" alt="image" src="https://github.com/user-attachments/assets/ecfd4091-1bb6-472c-b10c-d8a5ba421b69" />


自动弹出，并形成


<img width="865" height="515" alt="image" src="https://github.com/user-attachments/assets/9b39281e-264e-43ea-8707-5f560f9fd196" />


### 加载示例代码
为方便向初学者演示该软件的相关功能，设置了此功能
<img width="865" height="782" alt="image" src="https://github.com/user-attachments/assets/672e98de-ea0d-461c-b891-eb998d94f01a" />


单击运行，形成


<img width="865" height="515" alt="image" src="https://github.com/user-attachments/assets/0fb8d552-4d91-4b67-87c4-418c8cfa7030" />


### 清空编辑区
若已完成ppt的创作，可选择单击清空，进而方便复制粘贴下一个ppt
<img width="865" height="771" alt="image" src="https://github.com/user-attachments/assets/90008b96-aa52-4349-a10f-425d196ef9a4" />


### 解决报错
状态栏显示“代码执行出错”？
<img width="865" height="921" alt="image" src="https://github.com/user-attachments/assets/4c97d909-c919-4330-b100-b2dd5d296dd6" />


可能原因：
(1)	AI生成的代码存在语法错误
(2)	代码内容不完整或被截断
(3)	代码中有中文字符导致的编码问题


解决方法：
	单击“复制错误”，将错误发给具备记忆的大模型（即之前生成ppt的AI），让其修复即可。
<img width="865" height="926" alt="image" src="https://github.com/user-attachments/assets/efb2d386-2a7a-4537-a1e7-cf5ce57a75c1" />
<img width="865" height="616" alt="image" src="https://github.com/user-attachments/assets/cbb63511-5f2e-4357-b9c5-054aa550ed49" />


---


## 📦 系统要求

| 项目 | 要求 |
|------|------|
| 操作系统 | Windows 7/10/11（64位） |
| 内存 | 4GB 及以上 |
| 硬盘空间 | 100MB |
| Python | 无需预装（已集成） |

---


## 🔧 开发者指南


### 从源码运行


```bash
# 克隆仓库
git clone https://github.com/cbyygyitoh/ppt-code-runner.git

# 安装依赖
pip install -r requirements.txt

# 运行
python PPT代码运行_源码.py

#打包为 exe
pyinstaller --onefile --noconsole --name "PPT代码运行器" PPT代码运行_源码.py
```

##生成作品示例

<img width="2560" height="1409" alt="image" src="https://github.com/user-attachments/assets/d2b42250-5eef-47f0-9bab-1da3d76fc23b" />

<img width="2560" height="1406" alt="image" src="https://github.com/user-attachments/assets/62bddad1-900f-4ad3-b9a3-b06412647a76" />

<img width="2560" height="1104" alt="image" src="https://github.com/user-attachments/assets/ae60fb15-f76d-4813-8dc1-4d3b820d0864" />


## 📄 许可证
本项目采用 PolyForm Noncommercial 1.0.0 许可证。


✅ 个人学习、研究、教学使用

✅ 非商业目的分享和修改

❌ 商业用途（出售、收费服务等）

详见 LICENSE 文件。

##🙏 致谢
python-pptx - 强大的 PPT 生成库

PyInstaller - Python 打包工具

所有使用本工具的教育工作者 ❤️

<h3 align="center">⭐ 如果这个项目对你有帮助，请点个 Star 支持一下！</h3>
