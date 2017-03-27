# 變更截圖路徑

## 變更儲存路徑

打開終端機 Terminal，輸入 `defaults write com.apple.screencapture location`，後方接著輸入你截圖要放置的路徑

```
defaults write com.apple.screencapture location /path/to/screenshot/directory/
defaults write com.apple.screencapture location ~/Downloads/
```

> 我這邊的截圖路徑是放在 `~/Downloads/` 的路徑下，這樣的話可以直接使用 Dock 工具列下方的 `Downloads` 目錄捷徑去直接拿到截圖檔案

> 若為了避免 `~/Downloads/` 目錄下的檔案過亂，也可以自行建立目錄去存放截圖，然後把這個目錄自行移動到 Dock，這樣也可以達到同樣的效果（只是這樣下面就會多一個資料夾目錄了 lol）

## 重啟系統 UI

在終端機 Terminal 輸入 `killall SystemUIServer` 關閉原本的 UI Server，讓系統 UI 可以吃到新的設定

```shell
killall SystemUIServer
```

之後就可以截圖看看，新的目錄設定有沒有生效摟～

## 參考資料
* [How to change where your Mac screenshots get saved](http://www.cultofmac.com/419083/how-to-change-where-mac-screenshots-get-saved/)