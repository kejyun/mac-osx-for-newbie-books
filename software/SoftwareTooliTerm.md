# iTerm

雖然 OS X 有內建的終端機軟體，但是 iTerm 是一個功能更進階的終端機軟體，如果常常需要使用終端機去做指令的輸入操作，相信 iTerm 會讓你操作的更順手

> 目前版本 iTerm2

## 啟用顏色顯示

在 `~/.bash_profile` 檔案中加入以下兩行

```shell
export CLICOLOR=1
export TERM=xterm-256color
```

然後再重新載入設定檔即可

```shell
$ source ~/.bash_profile
```

## 啟用快速隱藏

有時候在終端機指定打一打，可能會需要看終端機背後的文件一眼，可以使用這個功能快速切換終端機的隱藏顯示方式

**設定**

> Preference / Keys / Show/hide iTerm2 with a system-wide hotkey 打勾

設定完成後就可以用 `Option（⌥）` + `空白鍵` 快速將 iTerm 切換到前景跟背景

![快速隱藏 Preference](http://i.imgur.com/cNoaWSx.png)

## 設定透明終端機視窗

我們也可以將視窗設定為透明，可以看到視窗後面的其他視窗資料，透明度則看自己需要去調整

**設定**

> Preference / Profiles / Window / Transparency

![透明度 Preference](http://i.imgur.com/cdTxDsZ.png)

## 快速鍵

### 文字

#### 文字放大

> `Command（⌘）`+`+（加號）`

#### 文字縮小

> `Command（⌘）`+`-（減號）`

#### 文字回復成預設大小

> `Command（⌘）`+`0（數字 0）`

### 複製滑鼠起始點到結束點之間的文字

> `shift` + `滑鼠點一下（起始點）` + `滑鼠點一下（結束點）`

### 複製任意滑鼠選取方型範圍內的文字

> `Command（⌘）`+ `Option（⌥）` + `滑鼠點選 & 移動選取範圍`

### 刪整行命令

> `Control（⌃）` + `?`

### 刪一個字

> `Control（⌃）` + `H`

---

## 分頁視窗

### 開新分頁

> `Command（⌘）` + `T`

### 關閉分頁

> `Command（⌘）` + `W`

### 向左向右切換分頁

> `Command（⌘）` + `左右方向鍵`

### 向左向右移動分頁

> `Command（⌘）` + `shift` + `左右方向鍵`

### 垂直分割視窗

> `Command（⌘）` + `D`

### 水平分割視窗

> `Command（⌘）` + `shift` + `D`

### 左右切換分割視窗

> `Command（⌘）` + `[`

> `Command（⌘）` + `]`

### 開新視窗

> `Command（⌘）` + `N`

### 切換視窗

> `Command（⌘）` + `Option（⌥）` + `數字`

*僅用在新視窗用（非分頁），數字為終端機的開啟順序*

---

## 輸入

### 同步輸入到所有分頁的所有分割視窗

> `Command（⌘）` + `shift` + `I`

### 同步輸入到當前分頁的所有分割視窗

> `Command（⌘）` + `Option（⌥）` + `I`

### 只輸入到當前分頁的當前視窗

> `Command（⌘）` + `Option（⌥）` + `shift` + `I`

---

## 其他

### 剪貼簿（存取過去輸入過的指令）

> `Command（⌘）` + `shift` + `H`
