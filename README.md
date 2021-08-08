# ChhoeTaigi 找台語：台語字詞資料庫

### 華文簡介
這裡的資料是「台文雞絲麵 Tâibûn Kesimī」計畫的一部份，若你想了解更多，請往這裡：
* 募資計畫：[嘖嘖 × 台文雞絲麵 Tâibûn Kesimī](https://www.zeczec.com/projects/taibun-kesimi)
* 辭典網站：[ChhoeTaigi 找台語](https://chhoe.taigi.info/)

---

## 1. 內容紹介
Chia ê資料是「台文雞絲麵 Tâibûn Kesimī」計畫ê 1部份，若beh koh khah了解，請ùi chia去：
* 募資計畫：[嘖嘖 × 台文雞絲麵 Tâibûn Kesimī](https://www.zeczec.com/projects/taibun-kesimi)
* 辭典網站：[ChhoeTaigi 找台語](https://chhoe.taigi.info/)

## 2. 版權說明
Chia ē無定期來更新字詞ê資料庫，ta̍k ê資料ê詳細說明tī ē-kha。
Beh使用進前請注意，ta̍k-ê字詞資料lóng有無kâng ê授權方式，
使用ê限制請先chim-chiok看！

## 3. 資料庫ê目標：

* 數位化：Kā台語字詞ê文獻、紙本資料數位化，利便資料chhiau-chhōe kap後手運用。
* 標準化：過去文獻資料因為無kâng ê因端致使文字格式無統一，tī chia ē標準化做2套羅馬字。
* 做整合：收集、建立1-ê siōng大siōng完整ê台語字詞資料庫。
* 服務化ê基礎：Chia ê資料ē chiâⁿ做「PhahTaigi」輸入法、「ChhoeTaigi」辭典ê資料來源。

## 4. 資料格式說明
### 4-1. 羅馬字
Chia ê台語字詞資料內底，羅馬字ê部份有整理做下底2款格式：

1. ```白話字```，mā叫```台灣羅馬字```，是頭1套tī台灣有才調完整書寫台語ê文字系統，mā是siōng有文化、歷史、koh有siōng chē文獻ê台語文字，是台語ê正寫法。
2. 另外1款是```中華民國教育部臺灣閩南語羅馬字拼音方案```，下底簡稱```教育部羅馬拼音```，主要是做漢字注音ê路用。

### 4-2. 輸入式kap萬國碼式
2套lóng有萬國碼ê字kap輸入用ê數字調號型式2款，利便使用者直接提去應用、學習。
文字ê部份lóng盡量保留原冊ê用字，利便讀文獻ê時khah好chhiau-chhōe。

### 4-3. 檔案格式
公開ê檔案lóng是用CSV (Comma-Separated Values) ê格式來khiām，ē-sái用Google文件、LibreOffice Calc Spreadsheet、Apple Numbers、Microsoft Office Excel等等軟體直接來phah開檔案。

### 4-4. 補充註解
Chia整理ê字詞資料來源若有重複--ê，kan-na ē保留來源hit份ê資料。


## 5. 資料位置說明：
	https://github.com/ChhoeTaigi/ChhoeTaigiDatabase/tree/ChhoeTaigiDatabase/{字詞資料代碼}.csv

    {字詞資料代碼}：請參考ta̍k-ê字詞資料ê說明。
    
    ../ChhoeTaigiDatabase/
       ├── ChhoeTaigi_EmbreeTaiengSutian.csv
       ├── ChhoeTaigi_iTaigiHoataiTuichiautian.csv
       ├── ChhoeTaigi_KamJitian.csv
       ├── ChhoeTaigi_KauiokpooTaigiSutian.csv
       ├── ChhoeTaigi_MaryknollTaiengSutian.csv
       ├── ChhoeTaigi_TaihoaSoanntengTuichiautian.csv
       ├── ChhoeTaigi_TaijitToaSutian.csv
       ├── ChhoeTaigi_TaioanPehoeKichhooGiku.csv
       └── ChhoeTaigi_TaioanSitbutMialui.csv

## 6. 字詞數量統計：
Ē-kha開始是ta̍k-ê字詞資料庫ê詳細說明，
以詞庫字詞ê數量來排列，siōng chē--ê排siōng頂koân。

|字詞資料名稱         |字詞數量                                                   |
|----------------|---------------------------------------
|#1: 2002+ 台華線頂對照典|91339
|#2: 1932 台日大辭典(台譯版)|69513
|#3: 1976 Maryknoll台英辭典|55903
|#4: 1973 Embree台英辭典|36800
|#5: 2011+ 教育部台語辭典|24608
|#6: 1913 甘字典|24367
|#7: 2016+ iTaigi華台對照典|19046
|#8: 1956 台灣白話基礎語句|5429
|#9: 1928 台灣植物名彙|1722
|#10: 其他索引資料|無公開
|總共|353511

## 7. 字詞資料個別說明
### #1: 2002+ 台華線頂對照典
#### 字詞資料代號：
    ChhoeTaigi_TaihoaSoanntengTuichiautian
#### 資料內容說明：
```
            DictWordID: '番號',
            PojUnicode: '白話字',
            PojUnicodeOthers: '白話字(其他講法)',
            PojInput: '白話字輸入',
            PojInputOthers: '白話字輸入(其他講法)',
            HanLoTaibunPoj: '漢羅台文(白話字)',
            KipUnicode: '教育部羅馬拼音',
            KipUnicodeOthers: '教育部羅馬拼音(其他講法)',
            KipInput: '教育部羅馬拼音輸入',
            KipInputOthers: '教育部羅馬拼音輸入(其他講法)',
            HanLoTaibunKip: '漢羅台文(教育部羅馬拼音)',
            HoaBun: '對應華文',
```

#### 授權說明：
    【台文華文線頂辭典】
    基礎資料提供：Tēⁿ Liông-úi（鄭良偉）教授
    資料增加kap編修：Iûⁿ Ún-giân（楊允言）教授、眾phah字kap校對ê義工
    以 姓名標示-Sio-kâng方式分享 4.0 國際 (CC BY-SA 4.0) 授權
    https://creativecommons.org/licenses/by-sa/4.0/deed.zh_TW

#### 補充說明：
```
多謝 Iûⁿ Ún-giân（楊允言）教授提供資料，koh同意 ChhoeTaigi 計畫使用kap公開授權。
原始網站：http://ip194097.ntcu.edu.tw/ungian/soannteng/chil/Taihoa.asp
```

### #2: 1932 台日大辭典(台譯版)
#### 字詞資料代號：
    ChhoeTaigi_TaijitToaSutian
    
#### 資料內容說明：
```
            DictWordID: '番號',
            PojUnicode: '白話字',
            PojUnicodeOthers: '白話字(其他講法)',
            PojInput: '白話字輸入',
            PojInputOthers: '白話字輸入(其他講法)',
            HanLoTaibunPoj: '漢羅台文(白話字)',
            KaisoehHanLoPoj: '漢羅台文解說(白話字)',
            LekuHanLoPoj: '漢羅台文例句(白話字)',
            KipUnicode: '教育部羅馬拼音',
            KipUnicodeOthers: '教育部羅馬拼音(其他講法)',
            KipInput: '教育部羅馬拼音輸入',
            KipInputOthers: '教育部羅馬拼音輸入(其他講法)',
            HanLoTaibunKip: '漢羅台文(教育部羅馬拼音)',
            KaisoehHanLoKip: '漢羅台文解說(教育部羅馬拼音)',
            LekuHanLoKip: '漢羅台文例句(教育部羅馬拼音)',
            PageNumber: '原冊頁數',
            GoanchhehPoochhiongChuliau: '原冊補充資料',
```

#### 授權說明：
    【台日大辭典（台文譯本）】
    原作者：小川尚義
    台文翻譯kap編修：Lîm Chùn-io̍k（林俊育）長老
    以 姓名標示-非商業性-Sio-kâng方式分享 3.0 台灣 (CC BY-NC-SA 3.0 TW) 授權
    https://creativecommons.org/licenses/by-nc-sa/3.0/tw/

#### 補充說明：
```
多謝 Lîm Chùn-io̍k（林俊育）長老提供資料，koh同意 ChhoeTaigi 計畫使用kap公開授權。
原始網站：http://taigi.fhl.net/dict/
Github：https://github.com/fhl-net/Lim-Chun-iok_2008_Tai-jip-Tua-su-tian
```

### #3: 1976 Maryknoll台英辭典
#### 字詞資料代號：
    ChhoeTaigi_MaryknollTaiengSutian
#### 資料內容說明：
```
            DictWordID: '番號',
            PojUnicode: '白話字',
            PojInput: '白話字輸入',
            KipUnicode: '教育部羅馬拼音',
            KipInput: '教育部羅馬拼音輸入',
            HoaBun: '對應華文',
            EngBun: '對應英文',
            PageNumber: '原冊頁數(暫時無)',
```

#### 授權說明：
    【Maryknoll台英辭典】
    （The Maryknoll Taiwanese-English Dictionary）
    以 姓名標示-非商業性-Sio-kâng方式分享 3.0 台灣 (CC BY-NC-SA 3.0 TW) 授權
    https://creativecommons.org/licenses/by-nc-sa/3.0/tw/

#### 補充說明：
```
資料是ùi Maryknoll Language Service Center ê網站khe̍h--ê，照原本ê授權公開。
原始網站：http://www.taiwanesedictionary.org/
```

### #4: 1973 Embree台英辭典
#### 字詞資料代號：
    ChhoeTaigi_EmbreeTaiengSutian
#### 資料內容說明：
```
            DictWordID: '番號',
            PojUnicode: '白話字',
            PojInput: '白話字輸入',
            KipUnicode: '教育部羅馬拼音',
            KipInput: '教育部羅馬拼音輸入',
            Abbreviation: '詞類縮寫',
            NounClassifier: '單位量詞',
            Reduplication: '疊詞',
            HoaBun: '對應華文',
            EngBun: '對應英文',
            Synonym: 'Kāng義詞',
            Confer: '參照',
            PageNumber: '原冊頁數',
```

#### 授權說明：
    【Embree台語辭典】
    （A dictionary of Southern Min: based on current usage in Taiwan and checked against the earlier works of Carstairs Douglas, Thomas Barclay, and Ernest Tipson）
    作者：Bernard L. M. Embree
    以 姓名標示-非商業性-Sio-kâng方式分享 3.0 台灣 (CC BY-NC-SA 3.0 TW) 授權
    https://creativecommons.org/licenses/by-nc-sa/3.0/tw/

#### 補充說明：
```
資料是ùi Taiwanese-Corpus ê網站khe̍h--ê，頂koân ê數位化資料是Iûⁿ Ún-giân（楊允言）教授提供--ê。
原始網站：https://github.com/Taiwanese-Corpus/Bernard-L.M.-Embree_1973_A-Dictionary-of-Southern-Min
```

### #5: 2011+ 教育部台語辭典
#### 字詞資料代號：
    ChhoeTaigi_KauiokpooTaigiSutian
#### 資料內容說明：
```
            DictWordID: '番號',
            PojUnicode: '白話字',
            PojUnicodeOthers: '白話字(其他講法)',
            PojInput: '白話字輸入',
            PojInputOthers: '白話字輸入(其他講法)',
            KipUnicode: '教育部羅馬拼音',
            KipUnicodeOthers: '教育部羅馬拼音(其他講法)',
            KipInput: '教育部羅馬拼音輸入',
            KipInputOthers: '教育部羅馬拼音輸入(其他講法)',
            HanLoTaibunPoj: '漢字台文',
            KipDictHanjiTaibunOthers: '漢字台文(其他寫法)',
            KipDictWordProperty: '字詞屬性',
            HoaBun: '對應華文',
            KaisoehHanLoPoj: '華文解說、詞性，台文例詞、例句(白話字)',
            KaisoehHanLoKip: '華文解說、詞性，台文例詞、例句(教育部羅馬拼音)',
            KipDictDialects: '無kāng所在ê講法(教育部羅馬拼音)',
            Synonym: 'Kāng義詞',
            Opposite: '反義詞',
```

#### 授權說明：
    【教育部台語辭典】
    （教育部臺灣閩南語常用詞辭典）
    以 姓名標示-禁止改作 3.0 台灣 (CC BY-ND 3.0 TW) 授權
    https://creativecommons.org/licenses/by-nd/3.0/tw/

#### 補充說明：
```
資料是中華民國教育部提供--ê，照原本ê授權公開。
原始網站：http://twblg.dict.edu.tw/holodict_new/index.html
```

### #6: 1913 甘字典
#### 字詞資料代號：
    ChhoeTaigi_KamJitian
#### 資料內容說明：
```
            DictWordID: '番號',
            PojUnicode: '白話字',
            PojInput: '白話字輸入',
            HanLoTaibunPoj: '漢字台文',
            HanbunImPojUnicode: '漢字文讀音(白話字)',
            HanbunImPojInput: '漢字文讀音(白話字輸入)',
            KaisoehPoj: '台文解說(白話字)',
            KaisoehHanLoPoj: '漢羅台文解說(白話字)',
            KipUnicode: '教育部羅馬拼音',
            KipInput: '教育部羅馬拼音輸入',
            HanbunImKipUnicode: '漢字文讀音(教育部羅馬拼音)',
            HanbunImKipInput: '漢字文讀音(教育部羅馬拼音輸入)',
            KaisoehKip: '台文解說(教育部羅馬拼音)',
            PageNumber: '原冊頁數',
```

#### 授權說明：
    【甘字典】
    （廈門音新字典）
    原作者：William Campbell / Kam Ûi-lîm（甘為霖）牧師
    編修：Lîm Chùn-io̍k（林俊育）長老
    以 姓名標示-非商業性-Sio-kâng方式分享 3.0 台灣 (CC BY-NC-SA 3.0 TW) 授權
    https://creativecommons.org/licenses/by-nc-sa/3.0/tw/

#### 補充說明：
```
多謝 Lîm Chùn-io̍k（林俊育）長老提供資料，koh同意 ChhoeTaigi 計畫使用kap公開授權。
原始網站：http://taigi.fhl.net/dick/
Github：https://github.com/fhl-net/Kam-Ui-lim_1913_Kam-Ji-tian
```

### #7: 2016+ iTaigi華台對照典
#### 字詞資料代號：
    ChhoeTaigi_iTaigiHoataiTuichiautian
#### 資料內容說明：
```
            DictWordID: '番號',
            PojUnicode: '白話字',
            PojInput: '白話字輸入',
            KipUnicode: '教育部羅馬拼音',
            KipInput: '教育部羅馬拼音輸入',
            HanLoTaibunPoj: '漢羅台文(白話字)',
            HanLoTaibunKip: '漢羅台文(教育部羅馬拼音)',
            HoaBun: '對應華文',
            DataProvidedBy: '資料來源',
```

#### 授權說明：
    【iTaigi華台辭典】
    （iTaigi）
    以「公眾領域貢獻宣告」（CC0）授權
    http://creativecommons.tw/cc0

#### 補充說明：
```
資料是iTaigi團隊提供--ê。
原始網站：https://itaigi.tw/
```

### #8: 1956 台灣白話基礎語句
#### 字詞資料代號：
    ChhoeTaigi_TaioanPehoeKichhooGiku
#### 資料內容說明：
```
            DictWordID: '番號',
            PojUnicode: '白話字',
            PojUnicodeOthers: '白話字(其他講法)',
            PojInput: '白話字輸入',
            PojInputOthers: '白話字輸入(其他講法)',
            KipUnicode: '教育部羅馬拼音',
            KipUnicodeOthers: '教育部羅馬拼音(其他講法)',
            KipInput: '教育部羅馬拼音輸入',
            KipInputOthers: '教育部羅馬拼音輸入(其他講法)',
            HoaBun: '對應華文',
            EngBun: '對應英文',
            KaisoehEngbun: '英文說明',
            NounClassifier: '單位量詞',
            LesuPoj: '例詞',
            Opposite: '反義詞',
            LekuPoj: '例句(白話字)',
            LekuEngbun: '例句(英文)',
            LekuHoabun: '例句(華文)',
            Confer: '參照',
            PageNumber: '原冊頁數',
```

#### 授權說明：
    【台灣白話基礎語句】
    （A Basic Vocabulary for a Beginner in Taiwanese）
    原作者：Ko Chek-hoàn（高積煥）、Tân Pang-tìn（陳邦鎮）
    數位化kap編修：Lîm Bûn-cheng、Tēⁿ Tì-têng、Tân Kim-hoa、Chiúⁿ Ji̍t-êng
    以 姓名標示-Sio-kâng方式分享 4.0 國際 (CC BY-SA 4.0) 授權
    https://creativecommons.org/licenses/by-sa/4.0/deed.zh_TW

#### 補充說明：
```
資料是ùi台語文記憶網站khe̍h--ê。
原始網站：http://ip194097.ntcu.edu.tw/memory/TGB/thak.asp?id=862
```

### #9: 1928 台灣植物名彙
#### 字詞資料代號：
    ChhoeTaigi_TaioanSitbutMialui
#### 資料內容說明：
```
            DictWordID: '番號',
            PojUnicode: '白話字',
            PojUnicodeOthers: '白話字(其他講法)',
            PojInput: '白話字輸入',
            PojInputOthers: '白話字輸入(其他講法)',
            HanLoTaibunPoj: '漢羅台文(白話字)',
            KaisoehHanLoPoj: '漢羅台文解說(白話字)',
            LekuHanLoPoj: '漢羅台文例句(白話字)',
            KipUnicode: '教育部羅馬拼音',
            KipUnicodeOthers: '教育部羅馬拼音(其他講法)',
            KipInput: '教育部羅馬拼音輸入',
            KipInputOthers: '教育部羅馬拼音輸入(其他講法)',
            HanLoTaibunKip: '漢羅台文(教育部羅馬拼音)',
            KaisoehHanLoKip: '漢羅台文解說(教育部羅馬拼音)',
            LekuHanLoKip: '漢羅台文例句(教育部羅馬拼音)',
            PageNumber: '原冊頁數',
            GoanchhehPoochhiongChuliau: '原冊補充資料',
```

#### 授權說明：
    【台灣植物名彙】
    原作者：佐佐木舜一
    數位化kap編修：Lîm Bûn-cheng、Tēⁿ Tì-têng、Tân Kim-hoa、Chiúⁿ Ji̍t-êng
    以 姓名標示-Sio-kâng方式分享 4.0 國際 (CC BY-SA 4.0) 授權
    https://creativecommons.org/licenses/by-sa/4.0/deed.zh_TW

#### 補充說明：
```
資料是ùi台語文記憶網站khe̍h--ê。
原始網站：http://ip194097.ntcu.edu.tw/memory/TGB/thak.asp?id=59
```


## 8. 聯絡

Nā有任何問題kap建議，請寫批來：
taibunkesimi@gmail.com

真多謝！
