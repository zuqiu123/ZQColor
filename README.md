# 16进制转化为UIColor的Pod库

个人封装的颜色转化的pod库，支持任何版本

## 上手指南

以下指南将帮助你在本地机器上安装和运行该项目，进行开发和测试。关于如何将该项目部署到在线环境，请参考部署小节。

### 安装要求
ZQColor 使用CocoaPods安装，CocoaPods是Objective-C的依赖管理器，它可以自动化并简化在项目中使用ZQColor等第三方库的过程。您可以使用以下命令安装它：
```
pod install ZQColor
```

### Podfile

要使用CocoaPods将ZQColor集成到您的Xcode项目中，请在以下位置指定Podfile：

```
source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '9.0'

target 'TargetName' do
pod 'ZQColor', '~> 0.0.1'
end
```

然后，运行以下命令：

```
pod install
```

等待执行结束完成安装

## 

### 使用方式

工程导入 

```
import <ZQColor/UIColor + ZQConversion.h>
```

然后使用

```
self.view.backgroundColor = [UIColor stringToColor:"3cd342"];
```


## 笔记
如果有什么可以联系我Email: <815130258@qq.com>

## Author

* **大空翼铁粉** 

## License
该项目签署了MIT 授权许可，详情请参阅 LICENSE.md


