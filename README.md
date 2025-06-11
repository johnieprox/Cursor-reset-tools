# 🔄 Cursor Free Reset Tool

> 一键重置 Cursor IDE 配置，延长试用体验 | Windows & macOS 双平台支持

[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS-blue.svg)](https://github.com/tancky777/Cursor-reset-tools/releases/tag/Cursor)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Release](https://img.shields.io/github/v/release/your-repo/cursor-reset.svg)](https://github.com/tancky777/Cursor-reset-tools/releases/tag/Cursor)

## 📖 项目简介

**Cursor Free Reset Tool** 是一个专为 Cursor IDE 用户设计的配置重置及恢复工具。当您的 Cursor 出现掉试用（Pro Trial）的情况，本工具可以帮您重置相关配置，彻底解决掉试用（Pro Trial）的问题，同时恢复您之前的工作区配置及对话历史记录。

### 🎯 解决的问题

- ✅ Cursor 试用期到期后无法继续使用
- ✅ 需要清理 Cursor 的历史配置和缓存
- ✅ 想要重新开始使用 Cursor 的完整功能
- ✅ 需要备份和恢复 Cursor 的对话历史

## ✨ 核心功能

### 🔧 一键重置配置

- **自动备份**：重置前自动备份您的重要配置和对话历史
- **智能清理**：清除 Cursor 的配置文件和缓存数据
- **机器码重置**：重置系统标识，实现真正的"全新开始"
- **自动重启**：操作完成后自动启动 Cursor

### 💾 历史记录恢复

- **对话历史**：恢复您与 AI 的对话记录
- **工作区配置**：恢复项目设置和工作环境
- **个人偏好**：保留您的个性化设置
- **智能合并**：新旧配置智能整合

### 🛡️ 安全保障

- **本地操作**：所有操作均在本地执行，无网络传输
- **自动备份**：操作前自动创建配置备份
- **可逆操作**：支持恢复到操作前的状态
- **进程保护**：自动处理 Cursor 进程，避免文件占用

## 💻 系统支持

| 操作系统            | 支持版本              | 可执行文件                 |
| ------------------- | --------------------- | -------------------------- |
| Windows             | Windows 10/11 (x64)   | `cursor_reset-windows.exe` |
| macOS Intel         | macOS 10.14+ (x86_64) | `cursor_reset-macOS-Intel` |
| macOS Apple Silicon | macOS 11.0+           | `cursor_reset-macOS-ARM`   |

## 🚀 快速开始

### 第一步：下载工具

1. 访问 [Releases 页面](https://github.com/tancky777/Cursor-reset-tools/releases/tag/Cursor)
2. 根据您的系统下载对应文件：
   - Windows 用户：下载 `cursor_reset-windows.exe`
   - macOS Intel 芯片：下载 `cursor_reset-macOS-Intel.zip`
   - macOS M 系列芯片：下载 `cursor_reset-macOS-ARM.zip`

### 第二步：准备环境

1. **关闭 Cursor**：确保 Cursor IDE 完全关闭
2. **管理员权限**：Windows 用户建议以管理员身份运行
3. **安全软件**：临时关闭杀毒软件（避免误报）

### 第三步：通用教程 (必看！！！)

1. windows 用户双击运行选 1 重置
2. 重置成功后选 2 恢复历史记录
3. 注册登录（随便你用什么方式登录，只要登录成功后），确保登录的账户是试用（Pro Trial）状态
4. 手动关闭 cursor，必须步骤！！！
5. 手动打开 cursor 后，再次选 2 恢复历史记录
6. 开始使用
7. 额度用完后重复以上步骤

mac 版本需要额外执行

1. 打开设置---隐私与安全性---App 管理---允许脚本权限
2. ./脚本名字（不需要 sudo），即可运行

## 📋 详细使用指南

### 🔄 重置操作流程

```
[1] 重置 Cursor 配置
```

**操作步骤：**

1. 工具会自动关闭所有 Cursor 进程
2. 创建当前配置的完整备份
3. 清理以下目录和文件：
   - 配置数据库
   - 工作区存储
   - 历史记录
4. 重置系统机器码标识
5. 自动重新启动 Cursor

**预期结果：**

- Cursor 重新显示欢迎界面
- 所有配置恢复默认状态

### 📂 恢复历史记录

```
[2] 恢复历史记录
```

**使用场景：**

- 重置后想要找回对话历史
- 需要恢复之前的工作区配置
- 想要保留部分个人设置

**操作步骤：**

1. 确保之前已执行过重置操作（有备份数据）
2. 选择恢复功能
3. 工具会自动：
   - 恢复对话历史记录
   - 恢复工作区配置
   - 恢复个人设置

### 🗂️ 备份文件位置

所有备份文件存储在：

- **Windows**：`C:\Users\[用户名]\CursorBackups\`
- **macOS**：`~/CursorBackups/`

备份内容包括：

- `settings/` - 配置文件备份
- `workspaceStorage/` - 工作区备份
- `History.zip` - 对话历史备份

## ⚠️ 重要注意事项

### 🚨 使用前必读

1. **数据备份**：虽然工具会自动备份，但建议您手动备份重要的项目文件
2. **网络连接**：重置后首次启动 Cursor 需要网络连接
3. **系统权限**：某些操作需要管理员权限，请按提示操作
4. **杀毒软件**：部分杀毒软件可能误报，请添加信任

### 🔒 安全性说明

- ✅ 本工具完全本地运行，不会上传任何数据
- ✅ 不会修改 Cursor 安装文件，只处理配置数据
- ✅ 所有操作可逆，支持恢复到原始状态

## ❓ 常见问题

### Q: 会丢失我的项目代码吗？

**A:** 不会。本工具只处理 Cursor 的配置文件，不会触及您的项目代码。

### Q: 重置后需要重新登录吗？

**A:** 是的，重置会清除登录状态，需要重新登录您的账户。

### Q: 可以撤销重置操作吗？

**A:** 可以使用恢复功能找回对话历史，但无法撤销机器码重置。

### Q: 支持 Linux 系统吗？

**A:** 目前仅支持 Windows 和 macOS，暂不 Linux 。

### Q: 为什么杀毒软件报警？

**A:** 因为工具需要修改系统配置文件，可能被误识别。请添加信任后使用。

### Q: 多久可以重置一次？

**A:** 没有次数限制，额度用完重复上面流程即可。

### Q: 重置后设置会保留吗？

**A:** 大部分设置会被清除，但可以通过恢复功能找回相关配置。

## 📝 免责声明

### 使用条款

1. **自主使用**：本工具仅供学习和研究使用，用户需自行承担使用风险
2. **合规责任**：请确保您的使用行为符合 Cursor 的服务条款和当地法律法规
3. **数据安全**：虽然工具会自动备份，但建议用户自行备份重要数据
4. **结果保证**：工具按现状提供，不保证 100% 成功率或特定结果

### 责任限制

- 本工具开发者不对使用本工具造成的任何直接或间接损失承担责任
- 用户在使用前应充分了解工具功能和潜在风险
- 任何因违反服务条款导致的后果由用户自行承担

## 🤝 支持项目

如果这个工具对您有帮助，欢迎：

- ⭐ 给项目点个 Star
- 🐛 报告 Bug 或建议改进
- 📢 推荐给其他需要的用户

### 💬 加入交流群

有问题或想交流使用心得？欢迎加入我们的微信群：

<div align="center">
  <img src="https://github.com/tancky777/Cursor-reset-tools/blob/main/assets/wechat-group.jpg" alt="微信群二维码" width="200">
  <p><strong>📱 微信群二维码</strong></p>
  <p><em>如群满或二维码过期，可添加群主微信Tyh_ba拉群</em></p>
</div>

### ☕ 请作者喝杯咖啡

如果这个工具为您节省了时间，欢迎请作者喝杯咖啡：

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="https://github.com/tancky777/Cursor-reset-tools/blob/main/assets/assets/wechat-pay.jpg" alt="微信赞赏码" width="150">
        <br>
        <strong>微信赞赏</strong>
      </td>
      <td align="center">
        <img src="https://github.com/tancky777/Cursor-reset-tools/blob/main/assets/alipay.jpg" alt="支付宝收款码" width="150">
        <br>
        <strong>支付宝</strong>
      </td>
    </tr>
  </table>
</div>

> 💡 **赞赏说明**：您的支持是我持续维护和优化工具的动力，每一份心意都非常珍贵！
