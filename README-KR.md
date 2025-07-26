[English](./README.md) | <span lang="zh-CN"> [简体中文](./REASME-ZHS.md) </span> | <span lang="zh-TW"> [繁體中文](./README-ZHT.md) </span> | <span lang="ja-JP"> [日本語](./README-JP.md) </span> | <span lang="ko-KR"> 한국어</span>

> [!NOTE] 
> 다음 한국어 콘텐츠는 DeepL 에서 번역한 것으로 정확성을 보장하지 않을 수 있습니다. 영어 또는 중국어 사용설명서 파일을 참조하세요.

<div lang="ko-KR">
  
# Gathering Script | 연취해 (계속 지켜봐 주세요)
 Fontworks(현재 Monotype K.K.)의 Klee One 에서 파생된 오픈 소스 CJK 폰트입니다.
 
 ## 서론
 연취해 는 간체 중국어(SC), 번체 중국어(TW & HK), 일본어(JP), 한국어(KR)를 포함한 다양한 동아시아 언어를 지원하는 TrueType CJK 폰트입니다. 이 프로젝트에서 완전한 버전 폰트 파일에는 약 50,000개의 글리프가 포함되어 있으며, 이는 일관된 시각적 미학을 공동으로 구현합니다. 이 폰트에는 서양 글리프도 포함되어 있어 기본 라틴, 그리스 및 키릴 텍스트를 지원합니다. 대부분의 글리프는 Klee One 에서 유래했으며, 일부는 그 파생 폰트에서 유래했습니다.

특정 상황에서는 동일한 원본 표의문자 기반의 글자가 최대 5개의 지역별 차별화된 글리프 디자인을 가질 수 있습니다. 이 프로젝트는 모든 글리프 변형을 포함하며, 이러한 지역별 형태를 세심하게 디자인했습니다. 웹페이지/소프트웨어가 글리프 변형을 지원하는 경우, 해당 언어별 폰트나 언어 태그를 선택하기만 하면 올바른 글리프 변형이 성공적으로 설정됩니다.
 
<details>  
   <summary>이 프로젝트에 대한 자세한 내용은 아래에서 확인할 수 있습니다.</summary> 
  
   
  2020년 12월, 일본 유명 폰트 제작사 Fontworks는 [Klee One](https://github.com/fontworks-fonts/Klee)을 오픈소스 방식으로 공개해 폰트 커뮤니티 전체를 흥분시켰습니다. Klee One은 송조체(영어: Fangsong, 중국어: 倣宋)과 궁수(영어: Kaiti, 중국어: 楷體)와 일부 특징을 공유하며, 우아한 구성과 높은 가독성을 갖추어 텍스트에 적합해 중국 사용자들로부터 인기를 얻고 있습니다. 전통적인 교과서(일본어: <span lang="ja-jp">教科書</span>) 폰트와 비교할 때, 전통적인 인쇄 폰트의 일부 특징을 유지했습니다. 2021년, [LXGW](https://github.com/lxgw)는 이를 기반으로 글리프를 확장해 [LXGW 문해](https://github.com/lxgw/LxgwWenKai)를 출시했으며, 이는 높은 평가를 받았습니다. 또한 많은 폰트 디자이너와 아마추어들도 Klee One을 기반으로 한 폰트를 제작했으며, 예를 들어 [얀쉬 / Iansui](https://github.com/ButTaiwan/iansui), [윤사이 해 / Jyunsaikaai](https://github.com/ItMarki/jyunsaikaai) 등이 있습니다. 폰트 디자이너들의 노력으로 Klee One을 기반으로 한 폰트 시리즈는 Klee One보다 훨씬 많은 문자를 지원합니다.
   
   그러나 일부 폰트가 Klee One 또는 그 파생 폰트와 동일한 글리프를 공유하며, 일부는 수정된 버전을 사용한다는 문제가 있습니다. Klee One에 포함되지 않은 문자들에 대해, 새롭게 추가된 글리프들 사이에는 비율과 구조에 차이가 있으며, 이는 다양한 폰트 간 비교 시 명확히 드러납니다.   
  
   대규모 문자 집합과 표준에 직면해 글리프 통합은 시급하고 필수적인 문제로 대두되고 있습니다.
  
   우리는 본고딕(또는 본명조)와 같은 폰트를 만들고자 합니다. 이 폰트는 넓은 문자 집합과 다국어 지원을 포함합니다. “연취해” 가 탄생했습니다.
   </details> 
   
## 권한 부여  
  “연취해”는 Klee One에서 파생된 서체로, SIL Open Font License 1.1 라이선스 하에 배포됩니다. [Klee](https://github.com/fontworks-fonts/Klee)는 FONTWORKS의 상표입니다.
  
 ### 라이선스  
  - 무료 사용(상업적 사용 포함)으로, 결제, 통지, 또는 원저자의 표시 없이 사용할 수 있습니다. *알려주시면 감사하겠습니다.* 
  - 폰트 파일을 자유롭게 공유하고, 어떤 소프트웨어나 기기에도 설치할 수 있습니다.  
  - 이 기반을 바탕으로 해당 작품은 수정되거나 재창작되어야 합니다. 두 번째 수정된 버전도 [SIL Open Font Licenses 1.1](https://scripts.sil.org/OFL)에 따라 공개되어야 합니다.
  
 ### 한도 
  - 파생 폰트를 생성할 때, 폰트 이름은 원본 폰트의 “예약된 이름”을 사용할 수 없습니다. 
  - 예비 이름  “<span lang="zh-cn">缘聚楷</span>”, “<span lang="zh-tw">緣聚楷</span>”, “<span lang="ja-jp">ギャザー楷書</span>”, “Gathering Script” 및 “<span lang="ko-kr">연취해</span>”는 두 번째 수정된 작품에 사용되어서는 안 됩니다. 폰트 소스 코드를 수정하지 않고 재컴파일된 폰트는 해당 예비 이름을 계속 사용할 수 있습니다.
  - [SIL Open Font License 1.1](https://scripts.sil.org/OFL)의 라이선스 및 이용 약관 제1조에 따라, **이 폰트를 단독으로 판매하는 것은 금지됩니다**.
  - 이 폰트는 [SIL Open Font License 1.1](https://scripts.sil.org/OFL) 이외의 라이선스로 배포될 수 없습니다.
  
  
 ## 감사의 말씀 
 - [FONTWORKS](http://fontworks.co.jp)에서 개발한 원본 폰트.  
 - [Bai Yi(白易)](https://github.com/yi-bai)에서 개발한 [Zitools](https://zi.tools).  
 - [Shs-cid](https://github.com/NightFurySL2001/shs-cid)는 본고딕 (본명조) 매핑 참조를 제공합니다.  
 - [LXGW](https://github.com/lxgw)에서 개발한 [LXGW 문해](https://github.com/lxgw/LxgwWenKai)는 간체 중국어 및 일부 한국어 글리프를 지원합니다.
 - [안쉬](https://github.com/ButTaiwan/iansui)는 [ButTaiwan](https://github.com/ButTaiwan)에서 대만 버전을 위해 개발되었습니다.
 - [윤사이 해](https://github.com/ItMarki/jyunsaikaai)는 [ItMarki](https://github.com/ItMarki)에서 홍콩 버전을 위해 개발되었습니다.
 - 일부 한자 글리프는 [Steve-Yuu](https://github.com/Steve-Yuu)가 개발한 [Yshi Pen Shuti](https://github.com/Steve-Yuu/YshiPen-Shuti)에서 차용했습니다.

</div>
