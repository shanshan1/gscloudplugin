# 光速云插件
## 特点
- 浏览器打印PDF/HTML/图片/自定义绘图。
- 使用静默方式打印。

## 安装
- [下载地址](https://raw.githubusercontent.com/gscloudplugin/gscloudplugin/master/光速云插件3.1.0.zip)
- 解压zip文件后，内含安装包和demo文件

## 文档
### 打印PDF
```
GSCloudPlugin.PrintPdf({
			Title:"PDF0001",
			Width: 100,
			Height: 150,
			Url: "https://domain/demo.pdf",
			PrinterIndex: -1
		       });
```
### 字段说明
属性 | 说明 | 类型 | 默认值
----|-----|------|------
| Title | 标题| String   | 默认GUID格式字符串|
| Width | 纸张宽度，单位毫米 | Int   | 0 |
| Height | 纸张高度，单位毫米 | Int | 0  |
| Url | PDF文件地址 | String | 无  |
| PrinterIndex | 系统打印机索引号。设置-1使用默认打印机 | Int | -1  |

### 打印图片
```
GSCloudPlugin.PrintImage({
			Title:"PNG0001",
			Width: 100,
			Height: 150,
			Url: "https://domain/demo.png",
			PrinterIndex: -1
		       });
```
### 字段说明
属性 | 说明 | 类型 | 默认值
----|-----|------|------
| Title | 标题| String   | 默认GUID格式字符串|
| Width | 纸张宽度，单位毫米 | Int   | 0 |
| Height | 纸张高度，单位毫米 | Int | 0  |
| Url | 图片文件地址 | String | 无  |
| PrinterIndex | 系统打印机索引号。设置-1使用默认打印机 | Int | -1  |

### 打印HTML
```
GSCloudPlugin.PrintHtml({
			Title:"HTML0001",
			Width: 100,
			Height: 150,
			Url: url,
			PrinterIndex: printerIndex // 设置-1使用默认打印机
		       });
```
### 字段说明
属性 | 说明 | 类型 | 默认值
----|-----|------|------
| Title | 标题| String   | 默认GUID格式字符串|
| Width | 纸张宽度，单位毫米 | Int   | 0 |
| Height | 纸张高度，单位毫米 | Int | 0  |
| Url | HTML网页地址 | String | 无  |
| PrinterIndex | 系统打印机索引号。设置-1使用默认打印机 | Int | -1  |
