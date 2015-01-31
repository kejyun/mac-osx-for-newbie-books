# Homebrew 套件管理軟體

![Homebrew OS X 缺少的套件管理工具](http://i.imgur.com/taFP7Vj.png)

## 說明

OSX 套件管理軟體，常常在安裝不同版本的軟體時，可能會造成不同軟體上的衝突，而 Homebrew 可以幫助你管理這些不同軟體之間的相依性問題。

## 適合對象

 * 工程師 (Engineer)

## 安裝需求

 * Xcode

## 安裝方式

在安裝完`Xcode`後，開啟`Xcode`同意授權，等`Xcode`授權完畢且開啟完成後，開啟 terminal 之後，執行:

```
$ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

## 相關指令

### 搜尋套件

```shell
$ brew search 套件名稱
```

### 套件資訊

```shell
$ brew info 套件名稱
```

### 安裝套件

```shell
$ brew install 套件名稱
```

### 查詢目前已安裝的套件

```shell
$ brew list
```

### 更新 homebrew 套件管理程式

```shell
$ brew update
```

## 測試

因為自己是 Web Engineer，所以馬上用來安裝 Git 套件管理程式來試試

```shell
brew install git
```

## 相關網址
 * [Homebrew — OS X 缺少的套件管理工具](http://brew.sh/index_zh-tw.html)
