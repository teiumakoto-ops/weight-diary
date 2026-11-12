# 岁时记重 · 正式页面字体

| 应用内字族 | 来源 | 处理 | 字节 | SHA-256 |
|---|---|---|---:|---|
| Diary Content | [霞鹜文楷 Lite v1.530 Regular](https://github.com/lxgw/LxgwWenKai-Lite/releases/tag/v1.530) | 全原始 Unicode 映射，转 WOFF2 | 5,306,020 | `0c4750db78429ae69e1173dfce60c643507ebab106a8b68ffc8a6c7277134fa8` |
| Diary UI Sans | [Source Han Sans CN VF 2.005R](https://github.com/adobe-fonts/source-han-sans/blob/2.005R/Variable/WOFF2/TTF/Subset/SourceHanSansCN-VF.ttf.woff2) | 固定 400 字重，保留 GB2312 常用字符及项目界面字符，转 WOFF2 | 1,031,156 | `5f3f4e0cea76a2dba423a7b3f4881caa5402b775af71d470968dc6cb35a20be8` |

其余字体文件与已验收的 V2.2 冻结预览逐字节相同，来源与许可沿用冻结目录。

| 本地文件 | 视觉角色 | 同目录许可 |
|---|---|---|
| v21-ui-sans-variable.woff2 | 可变字重思源黑体，界面文字 | OFL-Source-Han-Sans.txt |
| v2-noto-serif-sc.woff2 | 思源宋体，文学标题 | OFL-notoserifsc.txt |
| v2-plus-jakarta.ttf | Plus Jakarta Sans，数字 | OFL-plusjakartasans.txt |
| v2-playfair-display.ttf | Playfair Display，品牌装饰字 | OFL-playfairdisplay.txt |

Android WebView 从固定本地 HTTPS origin 的内置 APK 资源加载字体。CSS 使用同目录下 fonts 的相对路径。正式打包使用显式资源清单。运行时无需访问字体网站。文楷 WOFF2 保留原字库的 Unicode 映射；原字库未覆盖的字符由设备字体回退。
