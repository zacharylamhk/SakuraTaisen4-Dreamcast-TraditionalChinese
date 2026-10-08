<div align="center">

<img src="screenshot/Screenshot%202026-10-08%20133606.png" alt="櫻花大戰4 ～戀せよ乙女～ 標題畫面" width="720">

# 櫻花大戰 4 ～戀せよ乙女～

**Dreamcast 繁體中文計畫**

帝劇的燈，我想再為它點一次。<br>
讓這部作品在現在的螢幕上，還能被讀完。

</div>

---

《櫻花大戰4 ～戀せよ乙女～》的官方 PC 繁體中文版，是為很早以前的 Windows 做的。拿到 Windows 10、Windows 11 上，常常裝不起來，也開不起來。這個計畫把那份繁體中文放進 Dreamcast 版，讓你可以在電腦，或 Steam Deck 這類掌上型裝置上，用模擬器把故事看完。

字是我一個人放進遊戲的。句子還沒有全部讀順。如果你願意幫忙看劇本，那就是這個計畫現在最需要的事。

## 為什麼走到 Dreamcast

官方 PC 版現在常見的阻礙：

- **系統太舊。** 原版針對 Windows 98／XP。在 Windows 10、Windows 11 上直接安裝或啟動，經常出錯，或是完全沒有反應。
- **舊式防拷。** 當時使用的 SecuROM、SafeDisc，現在的 Windows 已經不再支援，光碟驗證會失敗。
- **滑鼠游標消失。** 有些環境下遊玩時看不到游標，只能改用鍵盤，或另外調整設定。

## 現在的舞台

- 畫面上的文字改以繁體中文字型繪製。遊戲內會顯示「繁中：ZacLam　版本：0.1a」。
- 補丁只對得上日文版 **v1.003**。其他區域或版本的映像檔位置不同，套下去會不對。
- 標題畫面的「サクラ大戦4」「～恋せよ乙女～」是畫在圖上的，目前仍是日文。那張圖我還沒有改。
- 對白、選項、介面文字都還在校對。看到不順的地方，請直接告訴我。

## 劇照

<div align="center">

<table>
<tr>
<td align="center" width="50%">
<img src="screenshot/Screenshot%202026-10-08%20133629.png" alt="記憶卡選擇，畫面為繁體中文" width="400"><br>
<sub>記憶卡選擇</sub>
</td>
<td align="center" width="50%">
<img src="screenshot/Screenshot%202026-10-08%20133640.png" alt="系統檔複製選單" width="400"><br>
<sub>系統選單</sub>
</td>
</tr>
<tr>
<td align="center" colspan="2">
<img src="screenshot/Screenshot%202026-10-08%20133722.png" alt="花組隊員一覽" width="640"><br>
<sub>花組</sub>
</td>
</tr>
<tr>
<td align="center">
<img src="screenshot/Screenshot%202026-10-08%20133742.png" alt="櫻的繁體中文對白" width="400"><br>
<sub>櫻</sub>
</td>
<td align="center">
<img src="screenshot/Screenshot%202026-10-08%20133800.png" alt="艾莉卡的繁體中文對白" width="400"><br>
<sub>艾莉卡</sub>
</td>
</tr>
<tr>
<td align="center">
<img src="screenshot/Screenshot%202026-10-08%20133814.png" alt="格莉辛的繁體中文對白" width="400"><br>
<sub>格莉辛</sub>
</td>
<td align="center">
<img src="screenshot/Screenshot%202026-10-08%20133847.png" alt="羅貝莉亞的繁體中文對白" width="400"><br>
<sub>羅貝莉亞</sub>
</td>
</tr>
</table>

</div>

## 入場

### 1. 準備映像檔，套上補丁

補丁是依 Internet Archive 上的日文 Dreamcast GDI 製作的，對應：

`Sakura Taisen 4 - Koi Seyo Otome v1.003 (2002)(Sega)(JP)`

請使用你自己合法持有的這個版本。本倉庫不附遊戲映像檔。

1. 準備上述日文版 GDI。
2. 下載 `SakuraTaisen4DC-TraditionalChinese-v0.1a.dcp`。
3. 用 [Universal Dreamcast Patcher](https://github.com/DerekPascarella/Universal-Dreamcast-Patcher) 的 **Apply Patch**，把 `.dcp` 套到這個 GDI 上。

### 2. 用模擬器開啟

Flycast 或 Redream 都可以。載入套好補丁的映像檔即可。

請不要同時掛上舊的 Flycast 韓文材質包。圖像會疊在一起，畫面會錯。

## 請求文本校對

這是我現在最需要的幫忙。

畫面上的字已經是繁體中文，可是句子還沒有全部順。有些地方讀起來彆扭，有些人名和你記得的不一樣，也有換行之後、一行開頭多出空白。這些我一個人玩、一個人看，一定會漏。

你不需要會組譯，也不需要會改程式。玩到不順的地方，或是直接打開倉庫裡的 `.txt`，把下面三樣寫進 [Issue](../../issues/new?template=proofreading.md) 就好：

1. 檔案路徑，例如 `ADVDATA/SCRIPT/S0120.txt`
2. 現在的句子
3. 你覺得比較順的寫法

看不懂檔案在哪裡也沒關係。一張遊戲截圖，加上你的改法，一樣可以。

會改檔的話，歡迎直接改對應的文本，再開 Pull Request。玩家看得到的對白、選項、人名優先。底線開頭、看起來像程式指令的行，先不要動。

人名、招式、地名如果和系列裡慣用的叫法不一致，也請提出來。我想先聽熟這部作品的人怎麼叫，再一起定下來。

文本大致分在這些地方：

| 位置 | 內容 |
| --- | --- |
| `ADVDATA/SCRIPT/` | 主線劇本 |
| `ADVDATA/CINEMA/`、`ADVDATA/ENDING.txt` | 過場與結局 |
| `SLG/` | 戰鬥與事件 |
| `MINIGAME/` | 小遊戲與相關對白 |
| `OVLM/` | 介面文字 |

## 贊助

補丁會繼續免費提供。後面的校對、改稿、重新打包，都是用空下來的時間在做。

如果這份繁體中文陪你把《櫻花大戰4》又走了一遍，而你願意幫我留一點時間繼續對稿，可以用 PayPal。金額隨你。不方便贊助也沒關係。上面的文本校對，對這個計畫更重要。

<div align="center">

<a href="https://www.paypal.com/qrcodes/managed/46e24f56-8128-468a-91ef-f28498c447e7?utm_source=consweb_more">
<img src="screenshot/qrcode.png" alt="PayPal 贊助 QR code" width="180">
</a>

<br>

<a href="https://www.paypal.com/qrcodes/managed/46e24f56-8128-468a-91ef-f28498c447e7?utm_source=consweb_more"><b>用 PayPal 贊助</b></a>

</div>

## 權利

這是粉絲製作的繁體中文補丁，供交流、字型移植與技術研究。遊戲本體、劇本、圖像與音樂的權利屬於 SEGA、OVERWORKS、RED。請支持正版，不要把補丁用於商業。
