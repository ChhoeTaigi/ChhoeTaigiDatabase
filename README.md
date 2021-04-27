# ChhoeTaigi 找台語：台語字詞資料庫
#### 華文簡介
這裡的資料是「ChhoeTaigi 找台語」計畫的一部份，若你想了解更多，請往這裡：
https://github.com/ChhoeTaigi/ChhoeTaigi

#### 以下是台文完整說明
Chia ê資料是「ChhoeTaigi 找台語」計畫ê 1部份，若beh koh khah了解，請ùi chia去：
https://github.com/ChhoeTaigi/ChhoeTaigi

Chia ē無定期來更新字詞ê資料庫，ta̍k ê資料ê詳細說明tī ē-kha，beh使用進前請注意，ta̍k-ê字詞資料lóng有無kâng ê授權方式，使用ê限制請先chim-chiok看。

Chia ê台語字詞資料內底，羅馬字ê部份lóng有整理做現此時標準ê白話字kap台羅2套系統，而且lóng有萬國碼ê字kap輸入用ê數字調號型式2 khoán，利便未來其他ê研究a̍h-sī應用thang直接使用。漢字ê部份保留原本ê用字做研究kap參考使用。

Chia整理ê字詞資料來源若有重複--ê，kan-na ē保留來源hit份ê資料。

公開ê檔案lóng是用CSV (Comma-Separated Values) ê格式來khiām，ē-sái用Google文件、LibreOffice Calc Spreadsheet、Apple Numbers、Microsoft Office Excel等等軟體直接來phah開檔案。

#### 資料庫ê目標：

1. 數位化：Kā台語字詞ê文獻、紙本資料數位化，利便資料chhiau-chhōe kap後手ê運用
2. 標準化：過去文獻資料因為無kâng ê因端致使文字格式無統一，tī chia ē標準化做傳統白話字kap教育部台羅版，包含Unicode調號kap輸入用ê數字調號
3. 整合：收集、建立1 ê siōng大siōng完整ê台語字詞資料庫，ǹg望未來有lú chē資料ē-tàng chòe-hoe來貢獻

#### 資料位置說明：
	https://github.com/ChhoeTaigi/ChhoeTaigiDatabase/tree/ChhoeTaigiDatabase/{字詞資料代號}.csv

    {字詞資料代號}：請參考ta̍k-ê字詞資料ê說明。
    
    ../ChhoeTaigiDatabase/
       ├── ChhoeTaigi_ChhoeTaigi_BanglooMuitheSekin.csv
       ├── ChhoeTaigi_EmbreeTaiengSutian.csv
       ├── ChhoeTaigi_iTaigiHoataiTuichiautian.csv
       ├── ChhoeTaigi_KamJitian.csv
       ├── ChhoeTaigi_KauiokpooTaigiSutian.csv
       ├── ChhoeTaigi_MaryknollTaiengSutian.csv
       ├── ChhoeTaigi_TaihoaSoanntengTuichiautian.csv
       ├── ChhoeTaigi_TaijitToaSutian.csv
       ├── ChhoeTaigi_TaioanPehoeKichhooGiku.csv
       └── ChhoeTaigi_TaioanSitbutMialui.csv

#### 字詞數量統計：
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
|#9: 2021+ 線頂媒體索引辭典|2806
|#10: 1928 台灣植物名彙|1722
|總共|331533

Ē-kha開始是ta̍k-ê字詞資料庫ê詳細說明，以詞庫字詞ê數量來排列，siōng chē--ê排siōng頂koân。

若有問題a̍h-sī建議，歡迎kap我連絡：
ngoohebi+chhoetaigidb@gmail.com


## #1: 2002+ 台華線頂對照典
#### 字詞資料代號：
    ChhoeTaigi_TaihoaSoanntengTuichiautian
#### 資料內容說明：
```
id: '番號',
poj_unicode: '白話字',
poj_unicode_other: '白話字(其他講法)',
poj_input: '白話字輸入',
poj_input_other: '白話字輸入(其他講法)',
hanlo_taibun_poj: '漢羅台文(白話字)',
kip_unicode: '教育部羅馬拼音',
kip_unicode_other: '教育部羅馬拼音(其他講法)',
kip_input: '教育部羅馬拼音輸入',
kip_input_other: '教育部羅馬拼音輸入(其他講法)',
hanlo_taibun_kip: '漢羅台文(教育部羅馬拼音)',
hoabun: '華文',
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

## #2: 1932 台日大辭典(台譯版)
#### 字詞資料代號：
    ChhoeTaigi_TaijitToaSutian
#### 資料內容說明：
```
id: '番號',
poj_unicode: '白話字',
poj_unicode_other: '白話字(其他講法)',
poj_input: '白話字輸入',
poj_input_other: '白話字輸入(其他講法)',
hanlo_taibun_poj: '漢羅台文(白話字)',
hanlo_taibun_kaisoeh_poj: '漢羅台文解說(白話字)',
hanlo_taibun_leku_poj: '漢羅台文例句(白話字)',
kip_unicode: '教育部羅馬拼音',
kip_unicode_other: '教育部羅馬拼音(其他講法)',
kip_input: '教育部羅馬拼音輸入',
kip_input_other: '教育部羅馬拼音輸入(其他講法)',
hanlo_taibun_kip: '漢羅台文(教育部羅馬拼音)',
hanlo_taibun_kaisoeh_kip: '漢羅台文解說(教育部羅馬拼音)',
hanlo_taibun_leku_kip: '漢羅台文例句(教育部羅馬拼音)',
page_number: '原冊頁數',
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

## #3: 1976 Maryknoll台英辭典
#### 字詞資料代號：
    ChhoeTaigi_MaryknollTaiengSutian
#### 資料內容說明：
```
id: '番號',
poj_unicode: '白話字',
poj_input: '白話字輸入',
kip_unicode: '教育部羅馬拼音',
kip_input: '教育部羅馬拼音輸入',
hoabun: '華文',
english: '英文解說',
page_number: '原冊頁數(暫時無)',
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

## #4: 1973 Embree台英辭典
#### 字詞資料代號：
    ChhoeTaigi_EmbreeTaiengSutian
#### 資料內容說明：
```
id: '番號',
poj_unicode: '白話字',
poj_input: '白話字輸入',
kip_unicode: '教育部羅馬拼音',
kip_input: '教育部羅馬拼音輸入',
abbreviations: '詞類縮寫',
noun_classifiers: '單位量詞',
reduplication: '疊詞',
hoabun: '華文',
english: '英文解說',
synonym: 'Kāng義詞',
cf: '參照',
page_number: '原冊頁數',
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

## #5: 2011+ 教育部台語辭典
#### 字詞資料代號：
    ChhoeTaigi_KauiokpooTaigiSutian
#### 資料內容說明：
```
id: '番號',
poj_unicode: '白話字',
poj_unicode_other: '白話字(其他講法)',
poj_input: '白話字輸入',
poj_input_other: '白話字輸入(其他講法)',
kip_unicode: '教育部羅馬拼音',
kip_unicode_other: '教育部羅馬拼音(其他講法)',
kip_input: '教育部羅馬拼音輸入',
kip_input_other: '教育部羅馬拼音輸入(其他講法)',
hanji_taibun: '漢字台文',
hanji_taibun_other: '漢字台文(其他寫法)',
word_property: '字詞屬性',
word_bunpeh_property: '文白屬性',
other_word_bunpeh_property: '文白屬性(其他講法)',
hoabun: '華文',
descriptions_poj: '華文解說、詞性，台文例詞、例句',
descriptions_kip: '華文解說、詞性，台文例詞、例句',
dialects_kip: '無kāng所在ê講法(教育部羅馬拼音)',
synonym: 'Kāng義詞',
opposite: '反義詞',
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

## #6: 1913 甘字典
#### 字詞資料代號：
    ChhoeTaigi_KamJitian
#### 資料內容說明：
```
id: '番號',
poj_unicode: '白話字',
poj_input: '白話字輸入',
hanji_taibun: '漢字台文',
poj_bunim_unicode: '漢字文讀音(白話字)',
poj_bunim_input: '漢字文讀音(白話字輸入)',
poj_kaisoeh: '台文解說(白話字)',
hanlo_taibun_kaisoeh_poj: '漢羅台文解說(白話字)',
kip_unicode: '教育部羅馬拼音',
kip_input: '教育部羅馬拼音輸入',
kip_bunim_unicode: '漢字文讀音(教育部羅馬拼音)',
kip_bunim_input: '漢字文讀音(教育部羅馬拼音輸入)',
kip_kaisoeh: '台文解說(教育部羅馬拼音)',
page_number: '原冊頁數',
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

## #7: 2016+ iTaigi華台對照典
#### 字詞資料代號：
    ChhoeTaigi_iTaigiHoataiTuichiautian
#### 資料內容說明：
```
id: '番號',
poj_unicode: '白話字',
poj_input: '白話字輸入',
kip_unicode: '教育部羅馬拼音',
kip_input: '教育部羅馬拼音輸入',
hanlo_taibun_poj: '漢羅台文(白話字)',
hanlo_taibun_kip: '漢羅台文(教育部羅馬拼音)',
hoabun: '華文',
from: '字詞來源',
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

## #8: 1956 台灣白話基礎語句
#### 字詞資料代號：
    ChhoeTaigi_TaioanPehoeKichhooGiku
#### 資料內容說明：
```
id: '番號',
poj_unicode: '白話字',
poj_unicode_other: '白話字(其他講法)',
poj_input: '白話字輸入',
poj_input_other: '白話字輸入(其他講法)',
kip_unicode: '教育部羅馬拼音',
kip_unicode_other: '教育部羅馬拼音(其他講法)',
kip_input: '教育部羅馬拼音輸入',
kip_input_other: '教育部羅馬拼音輸入(其他講法)',
hoabun: '對應華文',
english: '對應英文',
english_soatbeng: '英文說明',
noun_classifiers: '單位量詞',
example_su: '例詞',
opposite: '反義詞',
example_ku_taibun_poj: '例句(白話字台文)',
example_ku_english: '例句(英文)',
example_ku_hoabun: '例句(華文)',
from_su: '參照',
page_number: '原冊頁數',
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

## #9: 2021+ 線頂媒體索引辭典
#### 字詞資料代號：
    ChhoeTaigi_BanglooMuitheSekinSutian
#### 資料內容說明：
```
id: '番號',
poj_unicode: '白話字',
poj_input: '白話字輸入',
kip_unicode: '教育部羅馬拼音',
kip_input: '教育部羅馬拼音輸入',
hanlo_taibun_poj: '漢羅台文(白話字)',
hanlo_taibun_kip: '漢羅台文(教育部羅馬拼音)',
hoabun: '對應華文',
english: '對應英文',
poochhiong_chuliau: '參考資料',
muithe_miachheng: '媒體名稱',
hongsang_jitki: '放送日期',
liankiat: '媒體網址',
```

#### 授權說明：
    【ChhoeTaigi 2021+ 線頂媒體索引辭典】
    原作者：請參考辭條內容「媒體名稱」、「媒體網址」。
    數位化kap編修：ChhoeTaigi。
    內容版權屬原作者、原單位。
    數位化索引ê部份nā有版權，用下底ê方式公開：
    以 姓名標示-Sio-kâng方式分享 4.0 國際 (CC BY-SA 4.0) 授權
    https://creativecommons.org/licenses/by-sa/4.0/deed.zh_TW

#### 補充說明：
```
資料是ùi台語文記憶網站khe̍h--ê。
原始網站：http://ip194097.ntcu.edu.tw/memory/TGB/thak.asp?id=59
```


## #10: 1928 台灣植物名彙
#### 字詞資料代號：
    ChhoeTaigi_TaioanSitbutMialui
#### 資料內容說明：
```
id: '番號',
poj_unicode: '白話字',
poj_input: '白話字輸入',
kip_unicode: '教育部羅馬拼音',
kip_input: '教育部羅馬拼音輸入',
hanji_taibun: '漢字台文',
page_number: '原冊頁數',
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
