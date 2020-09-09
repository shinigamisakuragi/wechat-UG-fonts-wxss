# 在微信小程序中使用少数民族字体

1.  下载需要的字体wxss文件到项目中
2.  在app.wxss文件内引入字体wxss文件 `@import "/resources/fonts/alkatipbasmatom.wxss";`
3.  在app.wxss文件内定义 `font-family: 'ALKATIP Basma Tom';`

##### 自定义字体wxss文件

在 https://transfonter.org/ 等转换字体文件成base64字符串，创建一个wxss文件
```
@font-face {
  font-family: '#字体名称#';
  src: #转换好的字符串#;
  font-weight: normal;
  font-style: normal;
}
```
