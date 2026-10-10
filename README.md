# Fusion Gear Generator

Autodesk Fusion add-in for involute gears. Chinese-localized fork of [GF Gear Generator](https://github.com/CenturySturgeon/GF-Gear-Generator) by Juan Gras.

Fusion 加载项，一次生成一只（或一对）齿轮，用来做零件，不是整台减速器装配。界面为中文。

原项目为 BSD 3-Clause。本仓库保留原作者版权与许可证，仅整理仓库名称、中文界面和安装说明。

## Features

工具栏：**Fusion 齿轮生成器**

| 命令 | 说明 |
|---|---|
| 直齿轮 | 标准外直齿 |
| 斜齿轮 / 人字齿轮 | 外斜齿或人字齿 |
| 90° 锥齿轮 | 轴线夹角 90° 的锥齿轮副 |
| 直齿 / 斜齿齿条 | 齿条 |
| 蜗轮蜗杆传动 | 蜗杆及其配对蜗轮 |
| 内直齿轮 | 标准内直齿 |
| 非标准内直齿轮 | 非标内直齿 |
| 内斜齿轮 / 人字齿轮 | 标准内斜 / 人字 |
| 非标准内斜齿轮 / 人字齿轮 | 非标内斜 / 人字 |
| 变位直齿轮 | 变位外直齿 |
| 变位斜齿轮 | 变位外斜齿 |

公制 / 英制可切换。点确定后会记住上次参数。可选「快速计算」降低齿廓采样。

## Requirements

- Autodesk Fusion（设计工作区）
- 不要和原版 GF Gear Generator **同时运行**（命令 ID 相同会冲突）

## Install

1. Clone this repository
2. Fusion → **Utilities → Scripts and Add-Ins** (`Shift+S`)
3. Open the **Add-Ins** tab, click **+**, select this repository folder (the one that contains `FusionGearGenerator.py` and `FusionGearGenerator.manifest`)
4. Click **Run**. Optionally enable **Run on Startup**

## Not included

- 托森差速器、行星减速器整机装配（见 [TorsenDiffGenerator](https://github.com/SFNFIH/TorsenDiffGenerator) 与 [PlanetaryReducerGenerator](https://github.com/SFNFIH/PlanetaryReducerGenerator)）
- 蜗杆命令是减速蜗杆，不是交叉轴斜齿
- 按钮图标资源未包含在本仓库中

## License

BSD 3-Clause. See [LICENSE](LICENSE).

Original work © 2022 CenturySturgeon / Juan Gras.
