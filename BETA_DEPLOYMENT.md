# 發布測試App

## 製作Ad-Hoc的Provisioning Profile

1. 開啟[Apple Developer](https://developer.apple.com/account/ios/certificate) -> Certificates, Identifiers & Profiles

2. 選擇Provisioning Profiles  
![在網頁上長這樣](https://github.com/vincentLin113/learn-fastlane/blob/master/Screenshots/ProvisioningProfileThumbnail.png?raw=true)

3. 選擇新增➕  
![長這樣](https://github.com/vincentLin113/learn-fastlane/blob/master/Screenshots/ProvisioningProfileHeader.png?raw=true)

4. 選擇類型, 選擇Ad Hoc, 點選繼續  
![長這樣](https://github.com/vincentLin113/learn-fastlane/blob/master/Screenshots/ProvisioningProfileType.png?raw=true)

5. 選擇你目標專案的App ID, 點選繼續  
![長這樣](https://github.com/vincentLin113/learn-fastlane/blob/master/Screenshots/ProvisioningProfileAppId.png?raw=true)

6. 選擇這專案使用的身份憑證  
![長這樣](https://github.com/vincentLin113/learn-fastlane/blob/master/Screenshots/ProvisioningProfileCer.png?raw=true)

7. 選擇可以安裝的手機裝置  
![](https://github.com/vincentLin113/learn-fastlane/blob/master/Screenshots/ProvisioningProfileDevices.png?raw=true)

8. 產出, 你也可以下載一份到電腦上


---

## 在Xcode上使用剛製作的Provisioning Profile

1. Project Info -> General, Signing(Release) 選擇Download Profile 去下載剛才製作的Profile  
![](https://github.com/vincentLin113/learn-fastlane/blob/master/Screenshots/XcodeProvisioningSelection.png?raw=true)

---

## 完成Fastlane指令

1. 前往[官方教學](https://fabric.io/kits/fastlane)設定平台iOS, 下載你的Fastfile  
![](https://github.com/vincentLin113/learn-fastlane/blob/master/Screenshots/GetYourFastfile.png?raw=true)

2. 解壓縮後放進你的目標專案資料夾

3. 雙擊fastlane資料夾, 雙擊installer, 雙擊install 開始下載  
![](https://github.com/vincentLin113/learn-fastlane/blob/master/Screenshots/FastlaneInstaller.png?raw=true)

4. 開啟終端器, cd至目標專案資料夾

5. 下命令
```
fastlane beta
```