# 🎟️ L-tike AutoFill Pro

> 一键自动填写 L-tike 表单 + 自动选择信用卡付款 + 可编辑 Profile + 自动模式  
> 轻量版（仅展示用 Profile）

---

## 🌐 官方页面

🪄 **GreasyFork 安装页：**  
👉 [https://greasyfork.org/en/scripts/553537-l-tike-autofill-pro](https://greasyfork.org/en/scripts/553537-l-tike-autofill-pro)

> 推荐从 GreasyFork 安装或更新，Tampermonkey 会自动检测新版本。

---

## 🚀 功能特点

- 🟦 一键填写：自动填写所有 L-tike 购票表单字段  
- 💳 自动选择信用卡付款  
- 🧍‍♂️ 仅含展示用 Profile（可自定义编辑）  
- ⚙️ 折叠菜单界面（右上角按钮展开）  
- ⚡ 自动填写模式（可开关）  
- 💾 本地保存（存储于浏览器 localStorage）  
- 🪶 静默执行（无弹窗中断）

---

## 🧩 安装方式

### ✅ 从 GreasyFork 安装（推荐）
👉 [在 GreasyFork 上安装 L-tike AutoFill Pro](https://greasyfork.org/en/scripts/553537-l-tike-autofill-pro)

### 💻 从 GitHub 安装
1. 安装浏览器扩展 [Tampermonkey](https://www.tampermonkey.net/)
2. 点击以下链接自动安装脚本：  
   👉 [GitHub 原始脚本链接](https://github.com/pzl233/ltike-autofill/raw/main/ltike-autofill.user.js)

---

## ⚙️ 使用说明

1. 打开任意 L-tike 表单页面  
2. 页面右上角会出现按钮：`⚙ 一键填写`  
3. 点击后展开菜单，可选择：
   - 🟦 一键填写当前表单  
   - 📝 编辑展示用 Profile  
   - ⚡ 启用/关闭自动填写模式  
4. 若启用自动模式，页面加载后将自动填写并选中信用卡付款。

---

## 📄 展示用 Profile 信息

| 字段 | 值 |
|------|----|
| 姓名 | 前桑 实力深不可测 |
| 假名 | ヤマダ ハナコ |
| 电话 | 08012345678 |
| 出生日期 | 1995年5月17日 |
| 性别 | 男性 |
| 地址 | 東京都渋谷区神宮前1-2-3 青山マンション201 |
| Plus ID | E01099999999 |
| 登録電話 | 08099999999 |
| チケット電話 | 08088888888 |

> 所有资料仅为演示用，可在界面中自由编辑保存。

---

## 🧠 常见问题 (FAQ)

### 按钮没出现？
确认页面地址为 `https://l-tike.com/` 开头。  
如无反应，请检查 Tampermonkey 是否启用脚本。

### 数据会泄露吗？
不会，所有数据都保存在本地 localStorage。

### 如何重置资料？
在浏览器控制台输入：
```js
localStorage.removeItem('ltikeProfiles');
