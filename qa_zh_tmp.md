<link href="https://fonts.googleapis.com/css?family=Poppins&display=swap" rel="stylesheet">
<style>
body {
  background-image: url('background.jpg'); 
  background-size: cover; 
  background-position: center;
  background-repeat: no-repeat; 
  background-attachment: fixed; 
  font-family: 'Poppins', sans-serif;
}
</style>

<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-7261994485465423"
     crossorigin="anonymous"></script>

# 0.導入遊戲時提示:網絡錯誤？
 - 1.由于本軟件沒有使用任何服務器,導入遊戲的資源全部放在Github上，出現網絡錯誤有兩個原因
 - 2.原因1： github的api對于訪問有頻率限制，導入遊戲過多過快時請求會被短暫限制
 - 3.原因2： 部份國家地區運營商對github的請求有屏蔽過濾
 - 4.解決方法：1.本軟件自帶探速功能,出現了原因2導致網絡錯誤，可以稍后再重新導入
 - 5.解決方法：2.使用VPN全局模式，開啟TUN代理

# 1.steam下载或更新游戏提示清单不可用解决办法(2.0.1.14后的版本將不會出現此問題，如果出現試試重啟steam):
 - 0.原因是本軟件在沒有運行的情況下，不會對用戶的steam做任何處理，所以也就沒有鎖住遊戲清單的更新，解決方案如下:
 - 1.退出steam
 - 2.在本软件设置中点击清除steam缓存![image](https://github.com/user-attachments/assets/1d47b48d-5963-4065-84fa-1df12f17054b)

 - 3.启动steam
 - 4.在luckygametools软件中重新导入游戏(鼠标移动软件左侧游戏上会出现一个红X，点击可以将游戏移出库，然后再正常一键导入)
 - 5.完毕

# 2.官方游戏更新了,我的游戏版本却一下停在老版本:
 - 1.联系luckygametools团队（游戏入库资料统一由本团队维护）
 - 2.在luckygametools运营完成更新后再重新导放游戏(鼠标移动软件左侧游戏上会出现一个红X，点击可以将游戏移出库，然后再正常一键导入)
 - 3.steam上游戏如果没有提示更新，可重启一下steam
 - 4.完毕

# 3.steam入库了(壁纸引擎、小黃鴨)却找不到:
 - 1.壁纸引擎在steam属于软件类别
 - 2.在steam的左侧筛选中勾选住软件就可以出现了
 - 3.完毕

# 4.🚨 为什么你们的程序会被杀毒软件误报？
 -  🛡️ 这是因为我们没有购买微软认证，但请放心，这是误报，程序是安全的，而且無需管理員權限就可以正常使用(加速器功能除外)。

# 5. 🎮 遊戲怎麼導入DLC
 - 👥導入軟件內的大部份遊戲都買了dlc，導入沒有dlc的就是當時沒有買， 軟件沒手動導的入口，全是自動導入

# 6. 📸 我贡献了，现在怎么办？
 - 👌 谢谢你的贡献！请提供你的SteamID（76开头的数字串），我们将为你开通权限1。

# 7. 🚀 怎么权限？
 -  📈 你可以通过分享贡献升级到1级，或者通过特殊贡献或捐赠升级到2级。
   
# 8. 🗓️ 我激活了D加密游戏，能用多久？
 -  🔒 D加密是遊戲官方行為（本軟件只是輔助激活繞過），D加密原理是加密的遊戲文件和系統綁定，只有系統或遊戲文件變動才需要重新激活，在不變動的情況下，激活應該可以持续1个月有效。
   
# 9. 🤔 为什么我的游戏没有DLC？
 - 🛍️ 可能是因为DLC没有购买。我们确保所有游戏都是通过购买账号获得的，这样可以保障游戏和DLC的随时更新。
   
# 10.😖 为什么软件启动时会卡顿，資源占用？
 - 💻 这是因为软件需要加载3000多个游戏，这是正常现象。加载完成后，游戏会在本地缓存，之后就不会再次占用电脑资源。

# 11.加了聯機參數（-luckygametools）啟動時遊戲報錯怎麼辦（Steam Error  Application load error V:0000065432）:
 - 1.可在聯機參數中自行調試,`-luckygametools=1|2|3|4|5|6` (后面跟的是數字，多個數字用豎劃線隔開，排列組合測試)
 - 2:調試舉例，appid:2567870(Chained Toogether)  啟動選項設置為: -luckygametools=3
 - 3.排列組合多測試eg: `-luckygametools=2|3|4|5|6  -luckygametools=2|3|5|6 -luckygametools=4|5|6  -luckygametools=2|3|6 `等等
 - 4.完毕

# 12.為什麽 啟動  CAPCOM 發行的遊戲崩潰  eg: 生化危機重制、街霸系列、怪物獵人荒野 :
 - 1.啟動steam需要從luckygametools的左下角啟動![图片](https://github.com/user-attachments/assets/8e18ba43-8b6a-49ed-8717-a4374b4766c0)
 - 2.如果還是有問題，請使用管理員權限運行luckygametools試試
 - 3.完毕

# 13.為什麽 啟動了steam，還是提示未激活|未在線
 - 1.那是因為本程序檢測的機制未檢測到
 - 2.這時需要自行檢測防火墻、殺軟之類的
 - ![img_v3_02lc_cb8ba968-5620-44dd-b8c5-3ced4a6db07g](https://github.com/user-attachments/assets/2403ffb6-b11a-49c1-9626-3bacf6153c8e)


# 14.為什麽 紙嫁衣 系列啟動 進不入遊戲界面
 - 使用本軟件自帶的加速功能可以進行(右鍵管理員權限運行本程序)

# 15.MyDockFinder 啟動不了？
 - 添加steam的啟動參數  -luckygametools

# 16.為什麽軟件會提示 Ban On User(禁止使用)
 - 紅信號或者steam中luckygametools的群組被管理ban了，或者網絡問題

# 17.為什麽我的《荒野大镖客2》 之前可以正常玩，突然玩不了了
 - 之前可以玩說明您的遊戲文件都是正常的，未被其它軟件修改過
 - 解決方法
 -   第一步：進入遊戲的目錄找到RDR2.exe,可以發現這個程序的數字簽名估計不正常
 -   第二步：找到當前目錄下的Launcher.exe，複製一個重合名為RDR2.exe(原來的那個先刪除掉)
 -   第三步：重新啟動遊戲 搞定
 -   如果第二步目錄下沒有Launcher.exe，則需要重新下載遊戲或者較驗一下遊戲的完整性

# 18.關于網吧或其它電腦環境軟件無法正常工作的解決辦法
 - 1.從軟件右上角的設置中切換強化Steam的模式為HID模式
 - 2.從軟件右上角的設置中確認steam的安裝目錄是否正常，打開steam目錄，確認hid.dll文件存在
 - 3.從steam的圖標上啟動steam

# 19.GTA5增強版破解補丁說明
 - 0.如果導入增強版后在steam庫中找不到->移除傳承版后,再導入增强版,重啟一下steam
 - 1.作者目前無精力去做破解補丁
 - 2.給大家找到了個其它破解組織的補丁，<a href="https://raw.githubusercontent.com/luckygametools/steam-cfg/main/gamePatch/GTA5_Enhanced1.0.814.9_zh.zip" target="_blank">點擊下載補丁文件</a>  | <a href="https://gofile.io/d/ifvkmz" target="_blank">備用下載地址1</a> | <a href="https://ranoz.gg/file/ciNEbuCC" target="_blank">備用下載地址2</a>
 - 3.測試可以正常啟動GTA5增強版
 - 4.使用方法：下載完補丁文件后，將其它解壓至遊戲目錄即可(PlayGTAV.exe替換前可以備份一下)

# 20.GTA4破解補丁說明
 - 1. 給大家找到了個其它破解組織的補丁，<a href="https://raw.githubusercontent.com/luckygametools/steam-cfg/main/gamePatch/GTAIV1.2.0.59.zip" target="_blank">點擊下載補丁文件</a>  | <a href="https://gofile.io/d/2wlteo" target="_blank">備用下載地址1</a> | <a href="https://ranoz.gg/file/OqJ0Grxx" target="_blank">備用下載地址2</a>
 - 2. 使用方法：下載完補丁文件后，將其它解壓至遊戲目錄即可(PlayGTAIV.exe、GTAIV.exe替換前可以備份一下)

# 21.有些單機遊戲會提示需要聯網認證進入不了遊戲怎麼辦
 - 1.軟件目前收錄了部份可以突破此限制遊戲
 - 2.使用方法見<a href="https://luckygametools.github.io/README_zh.html" target="_blank">https://luckygametools.github.io/README_zh.html</a> 支持部份需要聯網授權驗證的單機遊戲(或 steam認證失敗 的場景)
 - 3.例如:英雄连3 ,真人快打,夜族崛起,微軟飛行模擬器 等遊戲
