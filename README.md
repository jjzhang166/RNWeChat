# RNWeChat
* 使用ReactNative开发的仿微信客户端，欢迎大家给个star或fork，谢谢~~
* 如果在项目构建过程中有任何问题，欢迎提issue，我有空一定帮忙解答O(∩_∩)O~~

# 运行方法
* 在项目根目录下执行npm install
* 由于项目中的导航控件使用的ReactNavigation，所以还需要执行npm install --save react-navigation
* 上面两步执行结束后，再执行react-native run-android即可
* apk目录下有RNWeChat-release.apk文件，可直接安装查看效果

# 更新
* 2017-6-8 修改联系人数据从服务端获取，包括联系人姓名、头像等，其他部分数据暂时为测试数据

# 注意
打release包时请使用自己的签名文件和签名配置，请注意android/app/build.gradle文件中的
```
signingConfigs {
    release {
        storeFile file(MYAPP_RELEASE_STORE_FILE)
        storePassword MYAPP_RELEASE_STORE_PASSWORD
        keyAlias MYAPP_RELEASE_KEY_ALIAS
        keyPassword MYAPP_RELEASE_KEY_PASSWORD
    }
}
```

# 截图
  <img src='./screenshots/5.jpg' width='300'>
  <img src='./screenshots/6.jpg' width='300'>
  <img src='./screenshots/7.jpg' width='300'>
  <img src='./screenshots/8.jpg' width='300'>
  <img src='./screenshots/1.jpg' width='300'>
  <img src='./screenshots/2.jpg' width='300'>
  <img src='./screenshots/3.jpg' width='300'>
  <img src='./screenshots/4.jpg' width='300'>
  <img src='./screenshots/9.jpg' width='300'>
  <img src='./screenshots/10.jpg' width='300'>