> [!Note]
> <div lang="ja-JP">
> 以下の日本語テキストはDeepLから翻訳されたものであり、正確性を保証するものではありません。英語または中国語のユーザーマニュアルをご参照ください。 
> </div>
 
<div lang="ja-jp"> 
  
# Gathering Script | ギャザー楷書
 フォントワークス（今 MonoType 株式会社）の「クレー One」をベースにしたオープンソースの汎日中韓フォント。
 
## プロジェクト概要 
 ギャザー楷書 (Gathering Script) は、4つの異なる東アジア言語（簡体字中国語、繁体字中国語、日本語、韓国語）をサポートするTrueType汎日中韓フォントのセットです。このプロジェクトのフルバージョンは、一つのフォントファイルに約 50,000 のグリフを含んでおり、それらが一体となって一貫した視覚的美学を表現している。このフォントには英語、ギリシャ語、ロシア語のテキストをサポートする西洋のグリフも多数含まれており、一部はKlee Oneから、一部は 「LXGW Wenkai」やその他の派生フォントから引用されている。   
  
 場合によっては、同じ漢字に基づく地域化されたグリフデザインが５つも存在することもある。このプロジェクトではこれらのグリフバリエーションをすべてカバーし、地域化されたグリフを注意深くデザインしています。ウェブページやソフトウェアがグリフバリアントをサポートしている場合、言語固有のフォントまたは対応する言語タグを選択するだけで、正しいグリフバリアントが正常に設定されます。
 
   <details>  
   <summary>このプロジェクトの背景と詳細については、ここをクリックして拡大してください。</summary> 
   
   2020年12月、日本の有名フォントメーカー FONTWORKS が GitHub で [「クレー One」](https://github.com/fontworks-fonts/Klee) 
   フォントをオープンソースライセンスで公開し、フォントコミュニティに衝撃を与えた。その静かなデザインは、伝統的なスクリプトフォントやテキストフォントとは一線を画すエレガントな外観で、中国のユーザーに人気がある。クレー One は通常の教科書体と比べて伝統的な活字体の特徴を残しており、2021 年には LXGW がこのフォントを追加・修正して [LXGW WenKai](https://github.com/lxgw/LxgwWenKai) フォントを作成し、広く歓迎されている。さらに、一部のフォントデザイナーや愛好家たちは、[「ヤンスイ」](https://github.com/ButTaiwan/iansui)[「ユンサイ雅楷」](https://github.com/ItMarki/jyunsaikaai)など、他の派生フォントも制作している。フォントデザイナー／マニアの努力のおかげで、「クレー One」から派生した一連のフォントは、オリジナルのものよりもはるかに多くの文字をサポートしている。
   
   しかし、異なるグリフ間の調和が問題である。オリジナルの「クレー One」や他の派生プロジェクトと同じグリフもあれば、修正されたものもある。「クレー One」に含まれていない文字については、新しく追加された文字の比率や骨格に若干の違いがある。これらの新しい追加は、異なるグリフを比較するとより明白になる。グリフの調和は、大規模な文字セットと標準化の間で緊急の問題となっている。
   
   このプロジェクトは、源ノゴシックや源ノ明朝のように、大きな文字セットとグリフの統合を組み合わせたフォントを作りたいという私たちの願いから生まれた。
   </details> 
  
## ライセンス情報
 このフォントは <ruby>フォントワークス<rp>(</rp><rt>FONTWORKS</rt><rp>)</rp></ruby> の開発に基づく「<ruby>クレー<rp>(</rp><rt>Klee</rt><rp>)</rp></ruby>」のオープンソースプロジェクトであり、SIL Open Font License 1.1の下でリリースされている。<ruby>クレー<rp>(</rp><rt>Klee</rt><rp>)</rp></ruby> は<ruby>フォントワークス<rp>(</rp><rt>FONTWORKS</rt><rp>)</rp></ruby>の商標です。
  
### 許可   
 - このフォントは、個人・法人を問わず、無償で自由に商用利用することができます。*（ご一報いただければ幸いです）*

 - このフォントは、自由に配布、共有、またはシステム、ソフトウェア、APPにインストールすることができ、再配布および／または一緒に販売するために任意のソフトウェアにバンドルすることができます。 
 - このフォントは、派生フォントを作成するために自由に修正または翻案することができます。改変または修正されたフォントも、[SIL OFL 1.1](https://scripts.sil.org/OFL) として開示されなければなりません。 

### 制約
- 派生フォントを作成する際には、元のフォント の予約名はフォント名の中で使えません。このフォントの予約名は
「<span lang="zh-cn">缘聚楷</span>」「<span lang="zh-tw">緣聚楷</span>」「<span lang="ja-jp">ギャザー楷書</span>」「Gathering Script」「<span lang="ko-kr">연취해</span>」であり、このフォントの２回目の派生では予約名は現れません。しかし、フォントの元のコードが編集されていなければ、再コンパイルされたフォントはこのフォントの予約名を使い続けることができます。
  
 - 個々の**フォントファイル（OTF/TTFファイル）の販売は**、[SIL Open Font License 1.1](https://scripts.sil.org/OFL) ライセンスと条件の第１条により**禁止**されています。

 - フォントは、[SIL Open Font License 1.1](https://scripts.sil.org/OFL) 以外のライセンスのもとで発行することはできません。

## 謝辞 
 - [FONTWORKS 株式会社](http://fontworks.co.jp)によるオリジナルオープンソースフォント[「クレー One」](https://github.com/fontworks-fonts/Klee)（[開発者の GitHub ホームページ](https://github.com/fontworks-fonts/)）。
- [白易](https://github.com/yi-bai)氏による [ZiTools](https://zi.tools)。  
- 源ノフォント対応参照サイト [Shs-cid](https://github.com/NightFurySL2001/shs-cid)。
- [LXGW](https://github.com/lxgw) が改作した中国大陸フォント、韓国語フォント [LXGW Wenkai](https://github.com/lxgw/LxgwWenKai)。
- [ButTaiwan](https://github.com/ButTaiwan) が改作した台湾標準フォント[「ヤンスイ」](https://github.com/ButTaiwan/iansui)。
- [ItMarki](https://github.com/ItMarki) が改作した香港標準フォント[「ユンサイ雅楷」](https://github.com/ItMarki/jyunsaikaai)。
- [Steve-Yuu](https://github.com/Steve-Yuu) 氏による [Yshi Pen Shuti](https://github.com/Steve-Yuu/YshiPen-Shuti)。 
  
</div>
