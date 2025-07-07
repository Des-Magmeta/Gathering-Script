# Gathering Script | 缘聚楷  
一款开源泛中日韩字体，基于 Fontworks 的 Klee One 衍生。
## 项目简介
  <details> 
  <summary>Klee One 及其衍生字体的发展背景很多人已经知道，想进一步了解此项目的背景，点此展开。</summary>
    
  2020 年 12 月，日本著名字体厂商 FONTWORKS 在 GitHub 上以开源授权释出 [Klee One](https://github.com/fontworks-fonts/Klee) 字型，震惊字体圈。Klee One 因其具有楷体笔调、又像仿宋一般整齐端正，具有较高的可读性与优雅的外观，非常适合正文排版，也因此广受中文使用者喜好。与一般的教科书体相比，Klee One 保留了传统印刷字体的一些特征。2021 年，[LXGW](https://github.com/lxgw) 在其基础上增补和修改字形，制成[「霞鹜文楷」](https://github.com/lxgw/LxgwWenKai)字体，受到广泛欢迎。除此之外，一些字体设计师／爱好者也制作了其他的衍生版本，如[「芫荽」](https://github.com/ButTaiwan/iansui)[「芫茜雅楷」](https://github.com/ItMarki/jyunsaikaai)等。在字体设计师／爱好者的努力下，一系列基于 Klee One 衍生的字体支持的字符数远大于原有的字符数。
  
  然而，不同字形之间的统合是一个问题。有的和原字型 Klee One 或其他衍生项目共用同一字形，有的却做出了修改。对于 Klee One 没有的字，新补的字之间的设计比例、设计间架具有一定的差异。这些新补字在不同字型对照时较为明显。在大字符集和标准规范之间，字形统合成了亟待解决的问题。
  
  我们希望能够制作出一个类似于思源黑体、思源宋体那样的大字符集和字形整合兼备的字体，为此本项目诞生了。
  </details>
  
缘聚楷是一套 TrueType 泛中日韩字体，支持四种不同的东亚语言（简体中文、繁体中文、日文和韩文），其中，繁体中文又分为台湾繁体和香港繁体。该项目一个完整版字体文件都有约 5 万个字形，可共同呈现一致的视觉美感。该字体还包含多个西文字形，支持拉丁语、希腊语和西里尔文文本，这些字形一部分来源于 Klee One，一部分来源于「霞鹜文楷」以及其他的衍生字体。  

在有些情况下，基于同一个原始表意文字的字可能有多达五个区域差异化的字形设计。该项目涵盖所有这些字形变体并且精心地设计了这些区域化字形。在网页／软件支持字形变体的情况下，您只需选择相应语言特定的字体或相应的语言标签，正确的字形变体即可设置成功。

## 授权信息
本字体是基于 SIL Open Font License 1.1 改造的 FONTWORKS 开发并发布的 [Klee](https://github.com/fontworks-fonts/Klee) 开源项目。Klee 是 FONTWORKS 的商标。

### 许可  
- 这款字体无论是个人还是企业都可以自由商用，无需付费，也无需知会或者标明原作者。 *（但如果告知，我会很感激。）*
- 这款字体可以自由传播、分享，或者将字体安装于系统、软件或 APP 中也是允许的，可以与任何软件捆绑再分发以及／或一并销售。
- 这款字体可以自由修改、改造，制作衍生字体。修改或改造后的字体也必须同样以 [SIL OFL 1.1](https://scripts.sil.org/OFL) 公开。

### 限制  
- 在制作衍生字体时，字体名称不可使用原有字体的「保留名称」。本字体保留名称为<span lang="zh-cn">「缘聚楷」</span><span lang="zh-tw">「緣聚楷」</span><span lang="ja-jp">「ギャザー楷書」</span>「Gathering Script」，基于本字体二次衍生的字体，名称不可出现保留名称；而在没有对字体源代码进行修改的情况下，重新编译出来的字体，可以继续使用本字体的保留名称。
- 根据 [SIL Open Font License 1.1](https://scripts.sil.org/OFL) 许可与条件中第一条的规定， **禁止单独出售字体文件(OTF/TTF 文件)的行为。**
- 该字体不可在 [SIL Open Font License 1.1](https://scripts.sil.org/OFL) 以外的授权许可下发行。

## 鸣谢
- [FONTWORKS 株式会社](http://fontworks.co.jp) 提供原版开源字体（见[开发者 GitHub 主页](https://github.com/fontworks-fonts/)）；  
- [白易](https://github.com/yi-bai)开发的网站[字统网](https://zi.tools)提供各地区标准字形参考；
-  [Shs-cid](https://github.com/NightFurySL2001/shs-cid) 提供思源字体映射参考；  
- [LXGW](https://github.com/lxgw) 制作的[「霞鹜文楷」](https://github.com/lxgw/LxgwWenKai)提中国大陆标准字体、韩文版本字体；
- [ButTaiwan](https://github.com/ButTaiwan) 衍生的[「芫荽」](https://github.com/ButTaiwan/iansui)提供台湾地区标准字体；
- [ItMarki](https://github.com/ItMarki) 衍生的 [「芫茜雅楷」](https://github.com/ItMarki/jyunsaikaai)提供香港地区标准字体；
- 部分汉字字形上述字体中均不包含，该部分源自 [Steve-Yuu](https://github.com/Steve-Yuu) 制作的 [Y 氏笔书体](https://github.com/Steve-Yuu/YshiPen-Shuti)。
