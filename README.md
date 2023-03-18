# RN-Front
react-native 版APP前端项目

# iOS项目启动前置准备 （全程VPN）
- node  V14^  
- ruby  V2.7.6
- Xcode (app store下载) 需要提前下载好至少一个iOS版本模拟器固件
- Homebrew(推荐) & CocoaPods & watchman

# iOS项目启动流程 （全程VPN）
- cd ios(首次)
- bundle install(首次)
- bundle exec pod install(首次)   可能需要多次执行，直到所以依赖安装成功  
- yarn install(首次)
- yarn react-native start
- yarn react-native run-ios

- 或者直接 yarn run ios (默认iPhone 14 Pro模拟器启动，启动机型可以在package.json中随需更改，后续改成灵活配置)

# iOS调试
- 如果可以顺利通过个人开发习惯拉起chrome调试，可以忽略以下
- 在chrome中输入并前往chrome://inspect
- 配置Discover network targets，增加localhost:8081 点击React Native Experimental后“inspect”按钮