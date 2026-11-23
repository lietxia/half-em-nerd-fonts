# 0.5em Nerd Fonts

> 英文（拉丁）字符宽度正好是中文一半的 Nerd Font 字体清单。

排版里 em 是字身宽（全角），en 是 em 的一半（半角）。多数编程字体拉丁字宽约 0.6em，
下面这批实测为 **0.5em**——与全角中文混排时天然 2:1 对齐，Markdown 表格和代码注释不会错位。

所有字体均为 **Nerd Fonts 官方打补丁版本**，开箱自带终端/编辑器图标，无需自己 patch。

## 列表

| 字体 | 预览 | 字宽 | 上游仓库 | 下载 (v3.5.1) | 特点 |
|---|---|---|---|---|---|
| **Agave** | ![Agave](previews/Agave%20Nerd%20Font.svg) | 0.5em | [GitHub](https://github.com/blobject/agave) | [ZIP](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.5.1/Agave.zip) | 几何感强、简洁的细线等宽字体 |
| **Inconsolata** | ![Inconsolata](previews/Inconsolata%20Nerd%20Font.svg) | 0.5em | [GitHub](https://github.com/googlefonts/Inconsolata) | [ZIP](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.5.1/Inconsolata.zip) | 斜杠零，曲线柔和 |
| **Inconsolata Go** | ![Inconsolata Go](previews/InconsolataGo%20Nerd%20Font.svg) | 0.5em | [GitHub](https://github.com/googlefonts/Inconsolata) | [ZIP](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.5.1/InconsolataGo.zip) | Inconsolata 的直引号版本 |
| **Iosevka** | ![Iosevka](previews/Iosevka%20Nerd%20Font.svg) | 0.5em | [GitHub](https://github.com/be5invis/Iosevka) | [ZIP](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.5.1/Iosevka.zip) | 最著名的 0.5em 窄体，Sarasa 的英文底子 |
| **Iosevka Term** | ![Iosevka Term](previews/IosevkaTerm%20Nerd%20Font.svg) | 0.5em | [GitHub](https://github.com/be5invis/Iosevka) | [ZIP](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.5.1/IosevkaTerm.zip) | 箭头/几何符号收窄，面向终端 |
| **Iosevka Term Slab** | ![Iosevka Term Slab](previews/IosevkaTermSlab%20NF.svg) | 0.5em | [GitHub](https://github.com/be5invis/Iosevka) | [ZIP](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.5.1/IosevkaTermSlab.zip) | Iosevka Term 的衬线（slab）版 |
| **Lekton** | ![Lekton](previews/Lekton%20Nerd%20Font.svg) | 0.5em | [GitHub](https://github.com/googlefonts/lekton) | [ZIP](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.5.1/Lekton.zip) | 纤细轻盈，0 与 O 相近 |
| **Monofur** | ![Monofur](previews/Monofur%20Nerd%20Font.svg) | 0.5em | — | [ZIP](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.5.1/Monofur.zip) | 圆点零，字符紧凑带曲线 |
| **Terminus** | ![Terminus](previews/Terminess%20Nerd%20Font.svg) | 0.5em | — | [ZIP](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.5.1/Terminus.zip) | 略带倾斜的方块字形 |
| **Ubuntu Mono** | ![Ubuntu Mono](previews/UbuntuMono%20Nerd%20Font.svg) | 0.5em | — | [ZIP](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.5.1/UbuntuMono.zip) | Ubuntu 家族的等宽字体，圆点零 |
| **D2Coding** | ![D2Coding](previews/D2KodingLigature%20Nerd%20Font.svg) | 0.5em | [GitHub](https://github.com/naver/d2-coding-font) | [ZIP](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.5.1/D2Coding.zip) | Naver 出品的韩文编程字体（连字版） |
| **Zed Mono** | ![Zed Mono](previews/ZedMono%20NF.svg) | 0.5em | [GitHub](https://github.com/zed-industries/zed) | [ZIP](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.5.1/ZedMono.zip) | Iosevka 的圆角衍生，较新 |

## 关于可变字体

Nerd Fonts 官方发布的补丁包都是**静态字重**，没有可变字体。若要 0.5em + 可变字重：

- **Iosevka / Inconsolata** 上游有可变字体（VF），可自行用 `font-patcher` 打图标。
- **Maple Mono** 用 `--width slim`（字宽 500 = 0.5em）配合 `--nf-variable` 可构建出 0.5em 的可变 NF 版本：
  [subframe7536/maple-font](https://github.com/subframe7536/maple-font)。

## 数据来源

- 字宽：下载各字体 Regular 版，用 fontTools 实测 52 个 ASCII 字母/数字的 `advanceWidth / unitsPerEm`，
  确认全部字形等宽且等于 0.5。
- 预览图来自 [Nerd Fonts 官网](https://www.nerdfonts.com/)，上游仓库与下载链接均已核验。
- Nerd Fonts 主仓库：[ryanoasis/nerd-fonts](https://github.com/ryanoasis/nerd-fonts)
