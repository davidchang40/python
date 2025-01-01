# python專題報告 - 第一組
在這個專案中，我們將會先介紹什麼是累進稅制，再以 Python 為工具，編寫出一個能計算稅率的程式碼，來幫助理解累進稅率的應用。
### 組員:
楊晴、魏士凱、何俞霈、劉祐辰、張峻瑋

# 目錄
- [專案介紹](https://github.com/davidchang40/python/edit/main/README.md#%E5%B0%88%E6%A1%88%E4%BB%8B%E7%B4%B9)
- [Python程式功能介紹](https://github.com/davidchang40/python/edit/main/README.md#python%E7%A8%8B%E5%BC%8F%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%B4%B9)
- [累進稅率介紹](https://github.com/davidchang40/python/edit/main/README.md#%E7%B4%AF%E9%80%B2%E7%A8%85%E7%8E%87%E4%BB%8B%E7%B4%B9)
- [參考資料](https://github.com/davidchang40/python/edit/main/README.md#%E5%8F%83%E8%80%83%E8%B3%87%E6%96%99)

# 專案介紹
本專案目標為介紹累進稅制，透過Canva簡報介紹台灣、中國、日本和澳洲的稅制，來對累進稅制作更深入的介紹，並透過Python語言，編寫出一個可以計算該四個國家的稅額的程式，與報告主題累進稅額來做搭配，以利更加了解累進稅制的運作。

### 專案目標：
- 透過報告介紹累進稅率的運作方式與扣除項目影響。
- 分析不同收入階層在各種稅制下的稅賦負擔。
- 能透過程式計算預期稅額。
- 轉換成台幣，比較各國稅額。

# Python程式功能介紹
- 能進行多國稅制分析和計算（台灣、中國、澳洲、日本）。
- 採用累進稅率進行稅額計算，包含多種扣除項目與免稅額。
- 提供淨所得及應繳稅額結果，便於比較不同收入階層的稅賦分配。
- 以 Python 撰寫，可擴展為其他國家的稅制分析。
- 在Python程式碼中，運用了def函式、if條件判斷和for迴圈等語法，來進行稅率的判斷和計算，另外也使用import語法，來匯入匯率查詢模組，來完善程式的運作。
- [Python程式連結(以googje colab編寫)](https://colab.research.google.com/drive/1ioii8OfWQqSImesI8Elo3aP_qHCDBmLN?usp=sharing)

# 累進稅率介紹
### 累進稅率:
為當今社會中被許多國家採用的稅制，其特色為:根據納稅人的收入高低，劃設不同的級距來以不同的稅率徵收，簡而言之，就是收入越多，其收入所要被課徵的比例也越多，也因此被視為一種達成課稅公平的方法。
### 扣除額:
政府在進行課稅前，根據各國的不同，也會有數個不同的扣除額，在淨收入減去扣除額後，才會依剩下的收入進行課稅。
### 簡略範例:
(總收入 - 各項扣除額) * (扣除後該額度所在區間之稅率)
### Canva簡報:
我們組製作的的Canva簡報，內有各國更詳細之稅制介紹，[連結](https://www.canva.com/design/DAGZtoIbLyU/hYMMxVCRhSU0qGUc2Ab0UQ/view?utm_content=DAGZtoIbLyU&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=hd0615ed781)

# 參考資料
- [累進稅制資料連結](https://houseloan.tw/income-tax-bracket/)
### 日本稅制資料:
- [連結一](https://www.nta.go.jp/publication/pamph/gensen/zeigakuhyo2023/02.htm)
- [連結二](https://life.huli.tw/2024/05/30/japan-tax-vs-taiwan-tax/)
- [連結三](https://jobmenta.yourator.co/blogs/303)
- [連結四](https://www.jetro.go.jp/tc/invest/setting_up/section3/page7.html)
- [連結五](https://thetravellernotes.com/income-tax-in-japan/)




