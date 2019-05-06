## 青果教务系统验证码识别

## 使用方式

1.引入依赖

2.开始使用

```java
InputStream in;
CodeBreak.codeBreak(in);
```


1.引入依赖方式

在release中下载依赖jar包

2.使用Maven引入依赖 待加入


## 启动加速

因首次使用需要加载图片缓存,使用如下方法在项目启动可以加速初次使用
```java
Class.forName("com.boommanpro.codebreak.cache.TrainImageCache");
```

## 使用本项目示例

[kingsoft-code-break-server](https://github.com/BoomManPro/kingsoft-code-break-server)

## 使用须知

感谢大家使用该项目，如果该项目帮助到了你，请点一个start