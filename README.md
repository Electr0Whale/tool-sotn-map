# Castlevania: Symphony of the Night Chinese Map & Tools (`tool-sotn-map`)

<p align="center">
  <img src="https://img.shields.io/badge/Game-Castlevania%3A%20Symphony%20of%20the%20Night-b31b1b.svg?style=flat-square" alt="Game">
  <img src="https://img.shields.io/badge/Language-Python%203%20(Tkinter)-3776ab.svg?style=flat-square" alt="Python 3">
  <img src="https://img.shields.io/badge/Localization-Simplified%20Chinese-success.svg?style=flat-square" alt="Localization">
  <img src="https://img.shields.io/badge/Platform-Cross--Platform%20%2F%20Windows-0078d7.svg?style=flat-square" alt="Platform">
</p>

《恶魔城：月下夜想曲》（Castlevania: Symphony of the Night）全流程双城全高清中文地图资产，附带英/日文到中文的地名、道具、魔导器术语速查与编辑工具。

Chinese-localized high-resolution maps for both castles in *Castlevania: Symphony of the Night*, accompanied by a standalone English/Japanese-to-Chinese terminology lookup and editing utility.

---

## 目录与资产结构

```text
tool-sotn-map/
├── assets/
│   ├── mapcn-1-final.png         # 正城全标注高清中文地图
│   └── mapcn-2-final.png         # 逆城全标注高清中文地图
├── data/
│   └── my_sotn_terms.csv         # 英/日文与中文对照标准术语词典库
├── sotn.pyw                      # 桌面端图形化术语查询与编辑工具 (Tkinter)
└── README.md
```

---

## 地图标注说明

- **`assets/mapcn-1-final.png`**：正城中文地图。
- **`assets/mapcn-2-final.png`**：逆城中文地图。
- **颜色标注规则**：
  - 🟢 **绿色**：物品、消耗品与装备
  - 🟡 **黄色**：魔导器 / 遗物 (Relics)
  - 🔴 **红色文字**：Boss 区域（击倒多数 Boss 掉落 Life Max Up）
- **房间类型**：
  - 🔴 **红色房间**：存档点 (Save Room)
  - 🟠 **橙色房间**：传送点 (Teleport Room)
  - 🟣 **紫色房间**：隐藏墙壁与隐藏区域 (Secret Room)

---

## 术语速查工具 (`sotn.pyw`)

一个轻量实用的桌面端查询工具，便于在重温游戏或进行本地化汉化比对时快速检索术语。

### 特性
- 支持输入英/日文原文即时匹配；
- 支持 `Tab` 键快速补全候选词；
- 支持窗口置顶、一键复制标准中文翻译；
- 内置“编辑术语库”功能，可直接在图形界面内添加新词条并持久化保存至 `data/my_sotn_terms.csv`。

### 运行方式

无需额外安装任何第三方依赖，直接调用 Python 运行：

```powershell
python sotn.pyw
```

---

## 鸣谢与来源声明

- 本项目地图底层标注最初参考 RPGClassics 的 SotN 地图成果；
- 高分辨率原版底图素材来源于 `gamegene.com`；
- 仓库仅供个人学习、单机怀旧与游戏研究交流使用，不对原作游戏版权及第三方美术资产主张所有权。
