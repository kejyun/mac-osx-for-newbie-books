# Sublime Text

Sublime 是一個輕量級的編輯器，可以讓你在撰寫程式時更加的方便，也有許多的擴充套件可以安裝，並且支援跨平台的軟體（OS X、Windows、Linux）。

Sublime 目前可以無限期的免費試用，只是在存擋時偶爾會跳出要求你購買的視窗，若覺得不錯也歡迎大家付費支持作者繼續開發維護這套軟體吧。

## 下載

* [Sublime Text 2 Download](http://www.sublimetext.com/2)
* [Sublime Text 3 Download](http://www.sublimetext.com/3)

## 進階使用

### 在 terminal 使用 Sublime 開啟特定目錄

我們在使用 terminal 時常常會瀏覽到不同的目錄的檔案，但當我們需要編輯該檔案時，則常常會使用 terminal 常用的編輯器（e.g. Vim），而我們可以讓 terminal 可以用 Sublime 開啟我們想要編輯的「檔案」或「目錄」。

#### 設定 Sublime

將安裝的 Sublime 做一個軟連結連結到預設可執行的`/usr/local/bin/`目錄中，並使用`subl`當作執行的關鍵字

> 這裏我 Sublime 安裝的目錄是安裝在`應用程式 (/Application)`中，你必須依照你安裝的路徑去修改以下指令

```shell
ln -s /Applications/Sublime\ Text.app/Contents/SharedSupport/bin/subl /usr/local/bin/subl
```

在做好軟連結之後就可以使用`subl`指令開啟想要編輯的「檔案」或「目錄」。

#### 開啟`/etc/hosts`檔案

```
$ subl /etc/hosts
```

#### 開啟`/etc/`目錄

> 開啟任何目錄時，只需要到該目錄下使用`subl .`就可以將整個目錄用 Sublime 開啟

```
$ cd /etc
etc $ subl .
```

## 相關網址

 * [Sublime Text: The text editor you'll fall in love with](http://www.sublimetext.com/)
 * [Launch Sublime Text 2 from the Mac OS X Terminal](https://gist.github.com/artero/1236170)
