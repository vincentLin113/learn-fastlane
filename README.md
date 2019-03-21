
## [Fastlane](https://fastlane.tools/) - The easiest way to build and release mobile apps.  

- 自動獲取App截圖
- [測試版App發佈](https://github.com/vincentLin113/learn-fastlane/blob/master/BETA_DEPLOYMENT.md)
- 上傳至App Store
- 自動生產/更新憑證

- - - -

1. [安裝CocoaPods](https://guides.cocoapods.org/using/getting-started.html)  

```
$ sudo gem install cocoapods
```  

2. [透過CocoaPods來安裝Crashlytics](https://fabric.io/kits/ios/crashlytics/install)  
			1. pod install
			2. 新增Run Script
			3. 調整Info.plist
			4. 初始化你的專案(這步驟能將這個Project註冊在你的Fabric帳戶)  
			5. Build your project


3. [測試偵錯功能](https://fabric.io/kits/ios/crashlytics/features) - 確定Fabric能抓到你的專案的閃退問題

- - - -

[安裝Fastlane及所需工具](https://docs.fastlane.tools/getting-started/ios/setup/) - 不管要使用哪個Fastlane的功能都需要先安裝

1. 安裝Xcode的命令列工具

```
xcode-select --install
```

2. 安裝

```
*# Using RubyGems*
sudo gem install fastlane -NV

*#Homebrew 安裝, 與上面選擇一個安裝方式就好*
brew cask install fastlane
```

3. 前往你目標專案的資料夾

```
fastlane init
```


