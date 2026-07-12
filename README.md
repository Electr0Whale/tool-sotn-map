# Castlevania: Symphony of the Night Chinese Map

《恶魔城：月下夜想曲》双城地图中文化项目，同时附带英/日文到中文的术语查询工具。

Chinese-localized maps for both castles in *Castlevania: Symphony of the Night*,
with a small English/Japanese-to-Chinese terminology helper.

## 地图文件

- `mapcn-1-final.png`：正城中文地图。
- `mapcn-2-final.png`：逆城中文地图。
- 绿色表示物品和装备，黄色表示遗物，红色表示 Boss。
- 红色房间是存档点，橙色房间是传送点，紫色房间是隐藏区域。

地图图标也标注了 Life Max Up 和 HP Max Up；多数 Boss 还会掉落 Life Max Up。

## 术语工具

- `sotn.pyw`：Windows Tkinter 术语查询与编辑界面。
- `my_sotn_terms.csv`：英/日文到中文的术语表。

将两个文件放在同一目录后运行：

```powershell
python .\sotn.pyw
```

工具支持搜索、候选补全、复制译名和编辑术语库。

## 来源说明

本项目最初基于 RPGClassics 的 SotN 地图进行中文化。现有说明中记录的高分辨率地图素材来源为 `gamegene.com`。仓库不对原游戏、美术素材或第三方地图主张所有权。
