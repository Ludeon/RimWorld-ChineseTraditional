# RimWorld-ChineseTraditional

Traditional Chinese translation of RimWorld.

See this page for license info and guidelines for how to contribute to the localization:

<http://ludeon.com/forums/index.php?topic=2933.0>

===========================

## RimWorld 繁體中文化

RimWorld 繁體中文化(台灣)

本專案專為核心遊戲製作(包含 DLC)，模組相關疑問或翻譯「請勿」在此詢問或請求。

授權憑證:

<http://ludeon.com/forums/index.php?topic=2933.0>

本翻譯為玩家志願者無償與遊戲開發者合作推出的中文化，屬於共享資源，Ludeon Studios 將會將本翻譯內容應用在官方釋出的 RimWorld 遊戲之中，而並不會提供任何形式上的酬勞與獎勵給予參與者(但你可以將你的名字放在中文化參與者的名單中並顯示在遊戲裡)。

參與本專案表示你同意 Ludeon Studios 可以任意使用你所提供的內容，且任何人皆可不經授權的修改、散佈、再製，惟仍需符合各地法令。

===========================

本繁體中文補丁對應遊戲版本：1.5.4082

注意事項：  
本補丁為 1.5.4082 版本專用，注意，即使同屬 1.5 版，各版間仍存在大量不相容，未更新至 1.5.4082 版以上的玩家請自行斟酌是否使用此補丁。

## 安裝方法

1. 下載壓縮檔(請點擊本頁上方的`Code▾` 點選`Download ZIP`)並解壓縮，得到`Core`、`Royalty`、`Ideology`、`Biotech`、`Anomaly`五個資料夾與本說明文件
    >
    > - 若未來有新的 DLC 發布則會有更多資料夾
    > - `.github` 的資料夾與 `.gitattributes` 為 git 的版本控制設定及 github 平台的相關設定，若只是想更新語言的人刪除或忽略即可
    >
2. 刪除或重新命名 `遊戲根目錄(Rimworld安裝的位置)\Data\Core\Languages` 中的 `ChineseTraditional (繁體中文).tar` 檔案
    >
    > - 此步驟可以省略，只要名稱不要和下一步驟的資料夾重複即可
    > - 若有購買並安裝DLC：Royalty, Ideology, Biotech 及 Anomaly則 `Data` 資料夾中會出現對應的資料夾，更新時在對應的資料夾重複同樣步驟即可(五個資料夾要重複五次本安裝流程)
    >
3. 在同一資料夾下新增「ChineseTraditional (繁體中文)」的資料夾
    >
    > - 此步驟的資料夾名稱可以自訂，遊戲內會顯示相對應的資料夾名稱
    > - 注意！若有安裝可選擇「ChineseTraditional (繁體中文)」的模組時，請務必將資料夾名稱取作「ChineseTraditional (繁體中文)」而非自訂名稱，否則模組無法正常套用繁中翻譯
    >
4. 將下載下來的 `Core` 資料夾內的東西，放入剛剛新建的資料夾
    >
    > - Core 的資料夾內應有：`Backstories` 、 `DefInjected` 、`Keyed` 、 `Strings` 四個資料夾與 `LangIcon.png` 、 `LanguageInfo.xml` 兩個檔案
    > - Royalty 與 Ideology 應只有：`DefInjected` 、 `Keyed` 兩個資料夾
    > - Biotech 與 Anomaly 應只有︰`DefInjected` 、 `Keyed` 與 `Strings` 三個資料夾
    > - 請注意以上檔案放置的位置是否正確，若不正確將導致所有文本無法正常顯示！
    >
5. 開始遊戲並在遊戲內選擇語言

官方會把 github 這裡的翻譯放到遊戲中，只是會稍微晚一點， 
過一段時間，官方放到遊戲內就不用做以上安裝步驟，直接遊戲中切換語言即可。

### FAQ

- 問：我的遊戲根目錄在哪裡？我找不到
    > 答：看你的Steam安裝在哪裡，Rimworld 的資料夾會放在`Steam\steamapps\common\RimWorld` 這個位置，至於你的Steam又安裝在哪裡，假如直接放在你的D槽的話就是`D:\Steam` 或是 `本機\本機磁碟 (D:)\Steam`
    >
    > 也可以在 Steam 上面滑鼠右鍵點選 Rimworld，選擇 `管理` > `瀏覽本機檔案` 就會打開檔案總管到那個資料夾了

## 變更語言方法

於遊戲主選單點選國旗圖案，即可選擇語言。或於遊戲選項內點選 Change Language 即可選擇語言。  
本補丁可無痛套用，無須重開新檔。

## 中文化說明

本繁體中文化翻譯在 A6 版本前的部分內容是基於翻譯得極為優秀的簡體中文內容修改而成， 
將對岸用字用語修改為台灣地區熟悉通用的字詞語，一方面可極大節省翻譯時程， 
一方面也為了縮小兩個中文版本間的差異性。  
從 A7 版本以後的中文化工作基本是以原文(英文)進行，並以簡中、日文與德文輔助參考，力求給予繁體中文使用者最友善的遊戲環境。

原則上每次的翻譯工作都會在取得所需文件後盡速展開，依照各版本更新規模還有文件釋出時間點不同，進行翻譯工作所需的時間也不同。  
每次翻譯完成後將會率先發布在巴哈姆特供巴友們使用， 
如想給予翻譯建議或與其他玩家交流，歡迎加入 Rimworld 繁體翻譯群的 Discord 群組，群組連結位於本文最末。

目前的繁體中文化完成度仍有極限，遊戲有部分內容無法以一般方式中文化，因此目前不劃入繁體中文化的翻譯範圍內。  
另外也有部分內容將保持原文。  
目前所知暫不(無法)翻譯的內容有：

- 特定勢力的預設人物名稱(官方未提供翻譯接口)
- 開發團隊名單(預計保留原文)
- 快捷鍵設定中的部分按鍵名稱
- 開發者模式之內容(官方未提供翻譯接口)

## 其他連結

歡迎加入 FB 社團：<https://www.facebook.com/groups/261201480757707/>  
Discord群組：<https://discord.gg/96sZ5RgW2G>  
巴哈姆特邊緣世界哈拉版：<https://forum.gamer.com.tw/B.php?bsn=27313>  
  
翻譯問題回報：請透過 Discord 或巴哈討論板(訊息跟信箱容易被忽略...)  
感謝支持 RimWorld

## 中文化人員

Wilseanhsu 個人中文化。 2018/10/3

win50117 中文化。 2020/3/2

ranke96 中文化。 2020/3/2

Jerifo 中文化 2020/3/16

Gast 2020/4/24

Darkborderman

TrashGrass

Hangalice2156

SCThunder

BathBall

shiromifox
