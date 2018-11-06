# 記憶卡無法 mount（external disk not mounted）

在升級 Mac OS 版本至 `Mojave` 版本後，原本的隨身記憶卡卻突然讀取不到了

打開 `Disk Utility` 可以看到他狀態一直為 `Unmount` 狀態，就算點了上方的 `Mount` 按鈕也不理我

![Disk Utility](./images/disk-utility.png)

為了解決這個問題可以點選上方的 `First Aid`，之後就會開始檢測此裝置

![First Aid external disk](./images/driver-not-mounting-first-aid.png)

檢測完後，就可以正常的 mount 記憶卡了

![Finish First Aid external disk](./images/driver-not-mounting-first-aid-finish.png)


## 參考資料
* [\[Solved\] How to fix external drive not mounting Mac and recover lost data?](https://iboysoft.com/mac-data-recovery/external-drive-not-mounting-mac.html)
* [Mac SSD not Booting? Try 5 Fixes to Boot up Your Mac](https://medium.com/@kepler.donald/mac-ssd-not-booting-try-5-fixes-to-boot-up-your-mac-710d02aec288)
