# Iconfont 转 dart 类
可以方便的使用阿里图库下载的字体文件
通过`iconfont.json`文件生成对应的`dart`类, 用于flutter调用

## 两种方式
1. 访问页面`index.html`

2. 使用node生成`Iconfont.dart`文件
```bash
node index.js
```

## flutter 中使用
1. 在flutter项目里面新建文件 Iconfont.dart，然后将生成的内容拷贝进去
2. 在需要使用的文件中引入在个类
3. 使用方式和flutter中原生基本一样
具体使用：

```
// 和其他组件中使用
Container(
    alignment: Alignment.center,
    width: 80,
    height: 80,
    child: Icon(Iconfont.mianxingdafeng)
),
// 图标单独使用
Icon(Iconfont.mianxingdafeng)
// flutter原生使用
Icon(Icons.home)

```
