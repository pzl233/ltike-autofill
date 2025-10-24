# 🎟️ L-tike AutoFill Pro

> 一键自动填写 L-tike 表单 + 自动选择信用卡付款 + 多 Profile 管理 + 折叠菜单 快捷切换 + 自动模式。

---

## 🚀 功能特点

- 🟦 **一键填写**：自动填写姓名、假名、电话、地址、同行者信息等所有项目  
- 💳 **自动选择信用卡付款**：无需手动切换，自动选中 「クレジットカード」 选项  
- 👥 **多 Profile 管理**：可创建、编辑、删除多个档案（例如自己 / 朋友 / 展示用）  
- ⚙️ **折叠菜单**：右上角单一按钮展开所有功能  
- ⚡ **自动填写模式**：进入页面即自动执行（可开启/关闭）  
- 💾 **本地保存**：所有配置与资料存储在浏览器 localStorage 中  
- 🎨 **静默模式**：无 alert 提示、不打断操作流程  

---

## 🧩 安装方式

### ✅ 从 GreasyFork 安装 （推荐）
👉 [点击这里直接安装 L-tike AutoFill Pro ](https://greasyfork.org/scripts/123456-l-tike-autofill-pro)

### 🔧 从 GitHub 安装
1. 安装 [Tampermonkey 扩展](https://www.tampermonkey.net/)  
2. 打开以下链接：  
   👉 [https://github.com/zhuoliangpu/ltike-autofill/raw/main/ltike-autofill.user.js](https://github.com/zhuoliangpu/ltike-autofill/raw/main/ltike-autofill.user.js)  
3. 点击「安装」即可。

---

## 🖼️ 界面预览

| 折叠菜单 | 编辑 Profile | 自动填写 |
|-----------|--------------|-----------|
| ![menu](./screenshots/menu.png) | ![edit](./screenshots/edit.png) | ![autofill](./screenshots/autofill.png) |

> *（可放实际截图，也可上传至 GitHub 并替换路径）*

---

## ⚙️ 使用说明

- 页面右上角出现 `⚙ 一键填写` 按钮  
- 点击展开菜单：
  - 🟦 一键填写当前 Profile  
  - 👥 点击其他 Profile 名 → 自动切换并填写  
  - 📝 编辑当前 Profile 内容  
  - ➕ 新建 Profile（从当前复制）  
  - 🗑 删除 Profile  
  - ⚡ 启用/禁用 自动填写模式  

### 🧠 自动保存
- 每次修改或切换后都会自动保存到 localStorage  
- 关闭页面或刷新后仍会保留  

---

## 🧠 常见问题 (FAQ)

### 🔹 为什么按钮没出现？
确保网页地址是以 `https://l-tike.com/` 开头。  
若脚本未加载，请在 Tampermonkey 中检查是否启用。

### 🔹 能在手机上用吗？
移动端 浏览器若支持 Tampermonkey （如 Kiwi Browser），则可以使用。

### 🔹 会泄露资料吗？
不会。所有 Profile 信息仅保存在本地浏览器 localStorage，不上传到任何服务器。

### 🔹 如何重置？
打开 开发者工具 → Console 输入：
```js
localStorage.removeItem('ltikeProfiles')
