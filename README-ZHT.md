[English](./README.md) | <span lang="zh-CN"> [简体中文](./README-ZHS.md) </span> | <span lang="zh-TW"> 繁體中文 </span>
<div lang="zh-tw"> 

> [!Note]
> 此專案目前處於準備階段，首次發佈的演示版預計將於 2026 年釋出。


 # Gathering Script | 緣聚楷   
 一款開源泛中日韓字型，基於 Fontworks 的 Klee One 改作。 
 
 ## Introduction / 項目簡介 
 緣聚楷是一套 TrueType 泛中日韓字型，支持四種不同的東亞語言（簡體中文、繁體中文、日文和韓文），其中，繁體中文又分為臺灣繁體和香港繁體。該項目一個完整版字體文件均包含約 5 萬個字形，可共同呈現一致的視覺美感。該字體還包含多個西文字形，支持拉丁語、希臘語和俄語文本，這些字形一部分來源於 Klee One，一部分來源於「霞鶩文楷」以及其他的衍生字體。   
  
 在有些情況下，基於同一個原始表意文字的字可能有多達五個區域差異化的字形設計。該專案涵蓋所有這些字形變體並且精心地設計了這些區域化字形。在網頁／軟體支持字形變體的情況下，您只需選擇相應語言特定的字體或相應的語言標籤，正確的字形變體即可設置成功。
 
   <details>  
   <summary>Klee One 及其改作字型的發展背景很多人已經知道，關於此項目的背景和更詳盡的資料，點擊此處展開。</summary> 
  
   2020 年 12 月，日本著名字體廠商 FONTWORKS 在 GitHub 上以開源授權釋出 [Klee One](https://github.com/fontworks-fonts/Klee) 字型，震驚字型圈。Klee One 因其兼具楷體筆調、又似仿宋整齊端正，具高易讀性與溫暖外形，非常適合內文排版，亦因此廣受中文使用者喜好。與一般的教科書體相比，Klee One 保留了傳統印刷體的一些特徵。2021 年，LXGW 在其基礎上增補和修改字形，製成「霞鶩文楷」/ LXGW WenKai 字體，受到廣泛歡迎。除此之外，一些字體設計師／愛好者也製作了其他的衍生版本，如「芫荽」/ Iansui、「芫茜雅楷」/ JyunsaiKaai 等。在字體設計師／愛好者的努力下，一系列基於 Klee One 衍生的字體支持的字元數遠大於原有的字元數。 
  
   然而，不同字形之間的統合是一個問題。有的和原字型 Klee One 或其他衍生專案共用同一字形，有的卻做出了修改。對於 Klee One 不包含的字，新補的字之間的設計比例、設計間架具有一定的差異。這些新補字在不同字型對照時較為明顯。在大字符集和標準規範之間，字形統合成了亟待解決的問題。 
  
   我們希望能夠製作出一個類似於思源黑體、思源宋體那樣的大字符集和字形整合兼具的字型，為此本項目誕生了。 
   </details> 
  
 ## 授權資訊 
 本字型是基於 SIL Open Font License 1.1 改造的 FONTWORKS 開發併發布的 [Klee](https://github.com/fontworks-fonts/Klee) 開源專案。Klee 是 FONTWORKS 的商標。 
  
 ### 許可   
 - 這款字型無論是個人還是企業都可以自由商用，無需付費，也無需知會或者標明原作者。 *（但如果告知，我會很感激。）* 
 - 這款字型可以自由傳播、分享，或者將字型安裝於系統、軟體或 APP 中也是允許的，可以與任何軟體捆綁再分發以及／或一併銷售。 
 - 這款字型可以自由修改、改造，製作衍生字型。修改或改造後的字型也必須同樣以 [SIL OFL 1.1](https://scripts.sil.org/OFL) 公開。 

 ### 限制   
 - 在製作衍生字型時，字型名稱不可使用原有字型的「保留名稱」。本字型保留名稱為 
 <span lang="zh-cn">「缘聚楷」</span><span lang="zh-tw">「緣聚楷」</span><span lang="ja-jp">「ギャザー楷書」</span>「Gathering Script」，基於本字型二次衍生的字型，名稱不可出現保留名稱；而在沒有對字型原始碼進行編輯的情況下，重新編譯出來的字型，可以繼續使用本字型的保留名稱。 
 - 根據 [SIL Open Font License 1.1](https://scripts.sil.org/OFL) 許可與條件中第一條的規定， **禁止單獨出售字型檔案(OTF/TTF 檔案)的行為。** 
 - 該字型不可在 [SIL Open Font License 1.1](https://scripts.sil.org/OFL) 以外的授權許可下發行。 

 ## 鳴謝 
 - [FONTWORKS 株式會社](http://fontworks.co.jp) 提供原版開源字型（見[開發者 GitHub 主頁](https://github.com/fontworks-fonts/)）；  
 - [白易](https://github.com/yi-bai)開發的網站[字統網](https://zi.tools)提供各地區標準字形參考；   
 - [Shs-cid](https://github.com/NightFurySL2001/shs-cid) 提供思源字型對映參考；   
 - [LXGW](https://github.com/lxgw) 製作的[「霞鶩文楷」](https://github.com/lxgw/LxgwWenKai)提供中國大陸標準字型、韓文標準字型； 
 - [ButTaiwan](https://github.com/ButTaiwan) 改作的[「芫荽」](https://github.com/ButTaiwan/iansui)提供臺灣地區標準字型； 
 - [ItMarki](https://github.com/ItMarki) 改作的 [「芫茜雅楷」](https://github.com/ItMarki/jyunsaikaai)提供香港地區標準字型； 
 - 部分漢字字形上述字型中均不包含，此部分源自[Steve-Yuu](https://github.com/Steve-Yuu) 製作的[Y 氏筆書體](https://github.com/Steve-Yuu/YshiPen-Shuti)。 
  
 </div>