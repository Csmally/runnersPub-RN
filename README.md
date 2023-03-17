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