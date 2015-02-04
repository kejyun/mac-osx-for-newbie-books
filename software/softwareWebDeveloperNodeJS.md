# Node.js

## 安裝 NVM （Node Version Manager）

使用 `brew` 安裝 NVM

```shell
$ brew install nvm
```

將下列指令加入 `.bash_profile`（或 `.bashrc`）檔案

```
export NVM_DIR=~/.nvm
source $(brew --prefix nvm)/nvm.sh
```

重新載入 `.bash_profile` 設定

```
$ source .bash_profile
```

測試 nvm 指令

```shell
kejyun@KeJyundeMBP:~$ nvm

Node Version Manager

Usage:
  nvm help                              Show this message
  nvm --version                         Print out the latest released version of nvm
  nvm install [-s] <version>            Download and install a <version>, [-s] from source. Uses .nvmrc if available
  nvm uninstall <version>               Uninstall a version
  nvm use <version>                     Modify PATH to use <version>. Uses .nvmrc if available
  nvm run <version> [<args>]            Run <version> with <args> as arguments. Uses .nvmrc if available for <version>
  nvm current                           Display currently activated version
  nvm ls                                List installed versions
  nvm ls <version>                      List versions matching a given description
  nvm ls-remote                         List remote versions available for install
  nvm deactivate                        Undo effects of `nvm` on current shell
  nvm alias [<pattern>]                 Show all aliases beginning with <pattern>
  nvm alias <name> <version>            Set an alias named <name> pointing to <version>
  nvm unalias <name>                    Deletes the alias named <name>
  nvm reinstall-packages <version>      Reinstall global `npm` packages contained in <version> to current version
  nvm unload                            Unload `nvm` from shell
  nvm which [<version>]                 Display path to installed node version. Uses .nvmrc if available

Example:
  nvm install v0.10.32                  Install a specific version number
  nvm use 0.10                          Use the latest available 0.10.x release
  nvm run 0.10.32 app.js                Run app.js using node v0.10.32
  nvm exec 0.10.32 node app.js          Run `node app.js` with the PATH pointing to node v0.10.32
  nvm alias default 0.10.32             Set default node version on a shell

Note:
  to remove, delete, or uninstall nvm - just remove ~/.nvm, ~/.npm, and ~/.bower folders
```


## 使用 NVM 安裝 Node.js

找出目前所有可安裝的 Node.js 版本

```shell
$ nvm ls-remote
    v0.11.8
    v0.11.9
    v0.11.10
    v0.11.11
    v0.11.12
    v0.11.13
    v0.11.14
    v0.11.15
    v0.11.16
```

安裝 Node.js (0.11.16)

```shell
$ nvm install 0.11.16
```

指定nvm使用的 Node.js版本

```shell
nvm use 0.11.16
```

預設使用 0.11.16 版本，否則每次重新連線登入，還需要重新 nvm use 一次

```shell
nvm alias default 0.11.16
```

列出所有安裝的版本

```shell
$ nvm ls
->     v0.11.16
default -> 0.11.16 (-> v0.11.16)
unstable -> 0.11 (-> v0.11.16) (default)
```

測試 Node.js

```shell
$ node -v
v0.11.16
```

測試 npm

```shell
$ npm -v
2.3.0
```
