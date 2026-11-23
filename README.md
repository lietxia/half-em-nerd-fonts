# 0.5em Nerd Fonts

![预览合集](previews/Iosevka%20Nerd%20Font.svg)

一批拉丁字宽正好等于中文一半（0.5em）的等宽字体，全部由 [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts)
官方打补丁，开箱自带终端与编辑器图标，无需自行 patch。与全角中文混排时天然 2:1 对齐，
Markdown 表格和代码注释不会因中英混排而错位。

字宽数据为实测：逐个下载 Regular 版，用 fontTools 统计 52 个 ASCII 字母/数字的 advance width ÷ UPM，确认全部字形等宽且为 0.5。
多数编程字体（JetBrains Mono、Fira Code、Hack 等）约 0.6em，不在本清单内。

## Agave

![Agave](previews/Agave%20Nerd%20Font.svg)

几何感强、细线风格的小巧等宽字体，结构规整。

- **字重**：2 个字重（Regular、Bold），无斜体
- [下载 ZIP](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.5.1/Agave.zip) · [上游项目](https://github.com/agarick/agave)

## Inconsolata

![Inconsolata](previews/Inconsolata%20Nerd%20Font.svg)

带斜杠零，曲线柔和，灵感取自多款字体的字形。

- **字重**：2 个字重（Regular、Bold）
- **可变字体**：上游提供 `Inconsolata-VF.ttf`（wght 可变轴），但 NF 补丁包为静态。
- [下载 ZIP](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.5.1/Inconsolata.zip) · [上游项目](https://github.com/googlefonts/Inconsolata)

## Inconsolata Go

![Inconsolata Go](previews/InconsolataGo%20Nerd%20Font.svg)

Inconsolata 的直引号版本，适合偏好直排引号的终端。

- **字重**：2 个字重（Regular、Bold）
- [下载 ZIP](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.5.1/InconsolataGo.zip) · [上游项目](https://levien.com/type/myfonts/inconsolata.html)

## Iosevka

![Iosevka](previews/Iosevka%20Nerd%20Font.svg)

最著名的窄体等宽字体，也是更纱黑体（Sarasa）的英文底子。字符排布紧密，省屏幕横向空间。

- **字重**：9 档字重 × 正体/斜体/倾斜，共 27 种字形
- **可变字体**：上游可用官方 customizer 构建可变 VF；NF 补丁包为静态。
- [下载 ZIP](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.5.1/Iosevka.zip) · [上游项目](https://github.com/be5invis/Iosevka)

## Iosevka Term

![Iosevka Term](previews/IosevkaTerm%20Nerd%20Font.svg)

面向终端：箭头和几何符号收窄，以贴合终端的列宽习惯。

- **字重**：同 Iosevka，27 种字形
- **可变字体**：上游可构建 VF；NF 补丁包为静态。
- [下载 ZIP](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.5.1/IosevkaTerm.zip) · [上游项目](https://github.com/be5invis/Iosevka)

## Iosevka Term Slab

![Iosevka Term Slab](previews/IosevkaTermSlab%20NF.svg)

Iosevka Term 的衬线（slab）版，保留终端窄符号的同时加了板状衬线。

- **字重**：9 档字重 × 正体/斜体/倾斜，共 15 种字形
- **可变字体**：上游可构建 VF；NF 补丁包为静态。
- [下载 ZIP](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.5.1/IosevkaTermSlab.zip) · [上游项目](https://github.com/be5invis/Iosevka)

## Lekton

![Lekton](previews/Lekton%20Nerd%20Font.svg)

纤细轻盈，笔锋锐利，`0` 与 `O` 形状接近，偏重极简风格。

- **字重**：3 种字形（Regular、Italic、Bold）
- [下载 ZIP](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.5.1/Lekton.zip) · [上游项目](https://fonts.google.com/specimen/Lekton)

## Monofur

![Monofur](previews/Monofur%20Nerd%20Font.svg)

圆点零，字符紧凑且带曲线，风格圆润。

- **字重**：3 种字形（Regular、Italic、Bold）
- [下载 ZIP](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.5.1/Monofur.zip) · [上游项目](http://carrois.com/)

## Terminus

![Terminus](previews/Terminess%20Nerd%20Font.svg)

源自经典终端位图字体，方块字形略带倾斜，辨识度高。

- **字重**：4 种字形（Regular、Italic、Bold、BoldItalic）
- [下载 ZIP](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.5.1/Terminus.zip) · [上游项目](http://terminus-font.sourceforge.net)

## Ubuntu Mono

![Ubuntu Mono](previews/UbuntuMono%20Nerd%20Font.svg)

Ubuntu 家族的等宽字体，圆点零，以 `n`/`o`/`H`/`O` 为骨架，风格稳重。

- **字重**：4 种字形（Regular、Italic、Bold、BoldItalic）
- [下载 ZIP](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.5.1/UbuntuMono.zip) · [上游项目](http://font.ubuntu.com)

## D2Coding

![D2Coding](previews/D2KodingLigature%20Nerd%20Font.svg)

Naver 出品的韩文编程字体，连字版；韩文与拉丁混排友好。

- **字重**：2 个字重（Regular、Bold）
- [下载 ZIP](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.5.1/D2Coding.zip) · [上游项目](https://github.com/naver/d2codingfont)

## Zed Mono

![Zed Mono](previews/ZedMono%20NF.svg)

Zed 编辑器出品的 Iosevka 圆角衍生，较新，风格柔和。

- **字重**：多字重（Regular～ExtraBold + 斜体/倾斜，含 Extended 宽度）
- [下载 ZIP](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.5.1/ZedMono.zip) · [上游项目](https://github.com/zed-industries/zed-fonts)

## 关于可变字体

Nerd Fonts 官方补丁包全部为静态字重。若需要 0.5em + 可变字重：

- **Iosevka 系**：官网 customizer 构建 VF，再自行用 `font-patcher` 打图标。
- **Inconsolata**：上游 `Inconsolata-VF.ttf` 有 wght 轴，同样需自行打图标。
- **Maple Mono**：`--width slim`（字宽 500 = 0.5em）+ `--nf-variable` 可一步构建出 0.5em 的可变 NF：
  [subframe7536/maple-font](https://github.com/subframe7536/maple-font)。这是唯一开箱即满足三项的方案。

预览图取自 [Nerd Fonts 官网](https://www.nerdfonts.com/font-downloads)。
