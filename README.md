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

    \ChhoeTaigiDatabase\{版本編號}\{字詞資料代號}.csv

    {版本編號}：用產生ê日期kap時間做標記（yyyyMMdd-HHmmss）。
    {字詞資料代號}：請參考ta̍k-ê字詞資料ê說明。

#### 字詞數量統計：
|字詞資料名稱         |字詞數量                                                   |
|----------------|---------------------------------------
|1. 台文華文線頂辭典|91340
|2. 台日大辭典（台文譯本）|69547
|3. Maryknoll台英辭典|55903
|4. Embree台語辭典|36824
|5. 教育部台語辭典|25881
|6. 甘字典|24368
|7. iTaigi華台辭典|8126
|8. 台灣白話基礎語句|5301
|9. 台灣植物名彙|1722

Ē-kha開始是ta̍k-ê字詞資料庫ê詳細說明，以詞庫字詞ê數量來排列，siōng chē--ê排siōng頂koân。

若有問題a̍h-sī建議，歡迎kap我連絡：
ngoohebi+chhoetaigidb@gmail.com


## 1. 台文華文線頂辭典
#### 字詞資料代號：
    ChhoeTaigi_TaibunHoabunSoanntengSutian
#### 資料內容說明：

|欄位名稱         |說明                                                   |
|----------------|---------------------------------------
|id|編號（照來源資料編號）
|poj_input|白話字輸入
|poj_other_input|其他講法、白話字輸入
|poj_unicode|白話字
|poj_other_unicode|其他講法、白話字
|tailo_input|教育部羅馬字輸入
|tailo_other_input|其他講法、教育部羅馬字輸入
|tailo_unicode|教育部羅馬字
|tailo_other_unicode|其他講法、教育部羅馬字
|hanlo_poj|漢羅（白話字）
|hanlo_tailo|漢羅（教育部羅馬字）
|hoagi|華語漢字

#### 授權說明：
    【台文華文線頂辭典】
    基礎資料提供：Tēⁿ Liông-úi（鄭良偉）教授
    資料增加kap編修：Iûⁿ Ún-giân（楊允言）教授、眾phah字kap校對ê義工
    以 姓名標示-Sio-kâng方式分享 4.0 國際 (CC BY-SA 4.0) 授權
    https://creativecommons.org/licenses/by-sa/4.0/deed.zh_TW

#### 補充說明：
> 多謝 Iûⁿ Ún-giân（楊允言）教授提供資料，koh同意 ChhoeTaigi 計畫使用kap公開授權。

> 原始網站：http://ip194097.ntcu.edu.tw/ungian/soannteng/chil/Taihoa.asp

## 2. 台日大辭典（台文譯本）
#### 字詞資料代號：
    ChhoeTaigi_TaiJitToaSuTian
#### 資料內容說明：
|欄位名稱         |說明                                                   |
|----------------|---------------------------------------
|id|編號（照來源資料編號）
|poj_input|白話字輸入
|poj_other_input|其他講法、白話字輸入
|poj_unicode|白話字
|poj_other_unicode|其他講法、白話字
|tailo_input|教育部羅馬字輸入
|tailo_other_input|其他講法、教育部羅馬字輸入
|tailo_unicode|教育部羅馬字
|tailo_other_unicode|其他講法、教育部羅馬字
|hanlo_poj|漢羅（白話字）
|hanlo_tailo|漢羅（教育部羅馬字）
|taigi_kaisoeh_hanlo_poj|台語解說（漢羅、白話字）
|taigi_kaisoeh_hanlo_tailo|台語解說（漢羅、教育部羅馬字）
|taigi_leku_hanlo_poj|台語例句（漢羅、白話字）
|taigi_leku_hanlo_tailo|台語例句（漢羅、教育部羅馬字）
|page_number|原冊頁數
#### 授權說明：
    【台日大辭典（台文譯本）】
    原作者：小川尚義
    台文翻譯kap編修：Lîm Chùn-io̍k（林俊育）長老
    以 姓名標示-非商業性-Sio-kâng方式分享 3.0 台灣 (CC BY-NC-SA 3.0 TW) 授權
    https://creativecommons.org/licenses/by-nc-sa/3.0/tw/

#### 補充說明：
> 多謝 Lîm Chùn-io̍k（林俊育）長老提供資料，koh同意 ChhoeTaigi 計畫使用kap公開授權。

> 原始網站：http://taigi.fhl.net/dict/

## 3. Maryknoll台英辭典
#### 字詞資料代號：
    ChhoeTaigi_MaryknollTaiEngSuTian
#### 資料內容說明：
|欄位名稱         |說明                                                   |
|----------------|---------------------------------------
|id|編號（照來源資料ê順序編號）
|poj_input|白話字輸入
|poj_unicode|白話字
|tailo_input|教育部羅馬字輸入
|tailo_unicode|教育部羅馬字
|hoagi|華語漢字
|english_descriptions|英文解說
|page_number|原冊頁數（暫時無）

#### 授權說明：
    【Maryknoll台英辭典】
    （The Maryknoll Taiwanese-English Dictionary）
    以 姓名標示-非商業性-Sio-kâng方式分享 3.0 台灣 (CC BY-NC-SA 3.0 TW) 授權
    https://creativecommons.org/licenses/by-nc-sa/3.0/tw/

#### 補充說明：
> 資料是ùi Maryknoll Language Service Center ê網站khe̍h--ê，照原本ê授權公開。

> 原始網站：http://www.taiwanesedictionary.org/

## 4. Embree台語辭典
#### 字詞資料代號：
    ChhoeTaigi_EmbreeTaigiSuTian
#### 資料內容說明：
|欄位名稱         |說明                                                   |
|----------------|---------------------------------------
|id|編號（照原冊ê順序編號）
|poj_input|白話字輸入
|poj_unicode|白話字
|tailo_input|教育部羅馬字輸入
|tailo_unicode|教育部羅馬字
|hoagi|華語漢字
|abbreviations|詞類縮寫
|noun_classifiers|單位量詞
|reduplication|疊詞
|english_descriptions|英文解說
|page_number|原冊頁數（暫時無）

#### 授權說明：
    【Embree台語辭典】
    （A dictionary of Southern Min: based on current usage in Taiwan and checked against the earlier works of Carstairs Douglas, Thomas Barclay, and Ernest Tipson）
    作者：Bernard L. M. Embree
    以 姓名標示-非商業性-Sio-kâng方式分享 3.0 台灣 (CC BY-NC-SA 3.0 TW) 授權
    https://creativecommons.org/licenses/by-nc-sa/3.0/tw/

#### 補充說明：
> 資料是ùi Taiwanese-Corpus ê網站khe̍h--ê，頂koân ê數位化資料是Iûⁿ Ún-giân（楊允言）教授提供--ê。

> 原始網站：https://github.com/Taiwanese-Corpus/Bernard-L.M.-Embree_1973_A-Dictionary-of-Southern-Min

## 5. 教育部台語辭典
#### 字詞資料代號：
    ChhoeTaigi_KauiokpooTaigiSutian
#### 資料內容說明：
|欄位名稱         |說明                                                   |
|----------------|---------------------------------------
|id|編號（照來源資料編號）
|poj_input|白話字輸入
|poj_unicode|白話字
|poj_other_input|其他講法、白話字輸入
|poj_other_unicode|其他講法、白話字
|tailo_input|教育部羅馬字輸入
|tailo_unicode|教育部羅馬字
|tailo_other_input|其他講法、教育部羅馬字輸入
|tailo_other_unicode|其他講法、教育部羅馬字
|word_property|字詞ê屬性
|word_bunpeh_property|文白屬性
|word_other_property|其他講法ê類型
|taigi_hanji|台語漢字
|hoagi|華語漢字
|descriptions|華語解說、詞性、台語例詞kap例句

#### 授權說明：
    【教育部台語辭典】
    （教育部臺灣閩南語常用詞辭典）
    以 姓名標示-禁止改作 3.0 台灣 (CC BY-ND 3.0 TW) 授權
    https://creativecommons.org/licenses/by-nd/3.0/tw/

#### 補充說明：
> 資料是中華民國教育部提供--ê，照原本ê授權公開。

> 原始網站：http://twblg.dict.edu.tw/holodict_new/index.html

## 6. 甘字典
#### 字詞資料代號：
    ChhoeTaigi_KamJitian
#### 資料內容說明：
|欄位名稱         |說明                                                   |
|----------------|---------------------------------------
|id|編號（照來源資料編號）
|poj_input|白話字輸入
|poj_unicode|白話字
|tailo_input|教育部羅馬字輸入
|tailo_unicode|教育部羅馬字
|taigi_hanlo_poj|台文漢羅（白話字）
|taigi_hanlo_tailo|台文漢羅（教育部羅馬字）
|taigi_kaisoeh_poj|台文解說（白話字）
|taigi_kaisoeh_tailo|台文解說（教育部羅馬字）
|taigi_kaisoeh_hanlo_poj|台文解說（漢羅、白話字）
|page_number|原冊頁數

#### 授權說明：
    【甘字典】
    （廈門音新字典）
    原作者：William Campbell / Kam Ûi-lîm（甘為霖）牧師
    編修：Lîm Chùn-io̍k（林俊育）長老
    以 姓名標示-非商業性-Sio-kâng方式分享 3.0 台灣 (CC BY-NC-SA 3.0 TW) 授權
    https://creativecommons.org/licenses/by-nc-sa/3.0/tw/

#### 補充說明：
> 多謝 Lîm Chùn-io̍k（林俊育）長老提供資料，koh同意 ChhoeTaigi 計畫使用kap公開授權。

> 原始網站：http://taigi.fhl.net/dick/

## 7. iTaigi華台辭典
#### 字詞資料代號：
    ChhoeTaigi_iTaigiHoaTaiSutian
#### 資料內容說明：
|欄位名稱         |說明                                                   |
|----------------|---------------------------------------
|id|編號（照來源資料ê順序編號）
|poj_input|白話字輸入
|poj_unicode|白話字
|tailo_input|教育部羅馬字輸入
|tailo_unicode|教育部羅馬字
|hanlo|台文漢羅（教育部羅馬字）
|hoagi|華語漢字
|from|字詞來源

#### 授權說明：
    【iTaigi華台辭典】
    （iTaigi）
    以 姓名標示-Sio-kâng方式分享 4.0 國際 (CC BY-SA 4.0) 授權
    https://creativecommons.org/licenses/by-sa/4.0/deed.zh_TW

#### 補充說明：
> 資料是iTaigi團隊提供--ê。

> 原始網站：https://itaigi.tw/

## 8. 台灣白話基礎語句
#### 字詞資料代號：
    ChhoeTaigi_TaioanPehoeKichhooGiku
#### 資料內容說明：
|欄位名稱         |說明                                                   |
|----------------|---------------------------------------
|id|編號（照來源資料ê順序編號）
|poj_input|白話字輸入
|poj_other_input|其他講法、白話字輸入
|poj_unicode|白話字
|poj_other_unicode|其他講法、白話字
|tailo_input|教育部羅馬字輸入
|tailo_other_input|其他講法、教育部羅馬字輸入
|tailo_unicode|教育部羅馬字
|tailo_other_unicode|其他講法、教育部羅馬字
|hoagi|華語漢字
|page_number|原冊頁數

#### 授權說明：
    【台灣白話基礎語句】
    （A Basic Vocabulary for a Beginner in Taiwanese）
    原作者：Ko Chek-hoàn（高積煥）、Tân Pang-tìn（陳邦鎮）
    數位化kap編修：Lîm Bûn-cheng、Tēⁿ Tì-têng、Tân Kim-hoa、Chiúⁿ Ji̍t-êng
    以 姓名標示-Sio-kâng方式分享 4.0 國際 (CC BY-SA 4.0) 授權
    https://creativecommons.org/licenses/by-sa/4.0/deed.zh_TW

#### 補充說明：
> 資料是ùi台語文記憶網站khe̍h--ê。

> 原始網站：http://ip194097.ntcu.edu.tw/memory/TGB/thak.asp?id=862

## 9. 台灣植物名彙
#### 字詞資料代號：
    ChhoeTaigi_TaioanSitbutMialui
#### 資料內容說明：
|欄位名稱         |說明                                                   |
|----------------|---------------------------------------
|id|編號（照來源資料ê順序編號）
|poj_input|白話字輸入
|poj_unicode|白話字
|tailo_input|教育部羅馬字輸入
|tailo_unicode|教育部羅馬字
|taigi_hanji|台語漢字
|page_number|原冊頁數

#### 授權說明：
    【台灣植物名彙】
    原作者：佐佐木舜一
    數位化kap編修：Lîm Bûn-cheng、Tēⁿ Tì-têng、Tân Kim-hoa、Chiúⁿ Ji̍t-êng
    以 姓名標示-Sio-kâng方式分享 4.0 國際 (CC BY-SA 4.0) 授權
    https://creativecommons.org/licenses/by-sa/4.0/deed.zh_TW

#### 補充說明：
> 資料是ùi台語文記憶網站khe̍h--ê。

> 原始網站：http://ip194097.ntcu.edu.tw/memory/TGB/thak.asp?id=59
