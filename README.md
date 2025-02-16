<div align="center">
<img src="assets/images/logo.png" alt="插件图标" width="50%">
<h1>Rin's Hub</h1>
<p>收藏了一些关于我的有趣东西</p>
<p>Some interesting things about me</p>


[![星标](https://img.shields.io/github/stars/RinLit-233-shiroko/Rin-sHub?style=for-the-badge&color=orange&label=星标)](https://github.com/RinLit-233-shiroko/Rin-sHub)
[![开源许可](https://img.shields.io/badge/license-MIT-darkgreen.svg?label=开源许可证&style=for-the-badge)](https://github.com/RinLit-233-shiroko/Rin-sHub)

[现在投稿](#如何投稿) | [在线查看](https://hub.rinlit.cn) | [许可证](#许可证)

</div>

<hr>

## 介绍 / Introduction

本项目将使用原生 HTML、CSS 和 JavaScript 编写，展示亿些 [Class Widgets](https://github.com/Class-Widgets/Class-Widgets) 交流群或关于我的奇怪有趣语录/东西。欢迎前来投稿。

当然，这个项目你也可以用哦如果你也希望拥有的话。

> [!TIP]
> 
> 在线预览：[Rin's Hub](https://hub.rinlit.cn)

### 截图
![img.png](docs/screenshot1.png)
目前还没任何投稿喵~

### 特性
- 拥有类似于 Fluent Design 的优雅、美观的界面；
- 使用瀑布流布局，适合展示大量不规则内容；
- 独特的“Tag”标签功能，可以快速筛选内容；
- 内置的Filter(搜索功能)，可以过滤到感兴趣的内容
- 使用**原生** HTML、CSS 和 JavaScript 编写，没错，原生。

## 如何投稿
如果你想为此投稿，请按照以下步骤：

1. 🍴 Fork 本仓库；
2. 🔍 在 `./updates` 中能看见 `images.json` 文件和 `/images` 文件夹，请在其中添加你的内容；
    
    在 `images.json` 文件中，添加你的内容，格式如下：
    
    ```json
   {
        "tags":{  // 标签
            "涩涩": "yellow",
            "test2": "red"
        },
        
        "tags_colors": [
           "red",
           "yellow",
           "green",
           "不要更改此处！"
        ],
        
        "hub_items": [  // 内容列表
              {
                "title": "Test",  // 标题
                "image": "blank.png",  // 图片名称，请将您投稿的图片放在 ./updates/images 文件夹中
                "description": "This is a test",  // 描述
                "tags": ["test", "test2"]  // 标签，可以打多个
              }
        ]
    }
    ```
3. 📷 在 `./updates/images` 文件夹中添加你的图片，图片名称请与 `images.json` 文件中的 `image` 字段对应；
4. 🎉 完成！在提交 PR 并通过审核被合并后，你的内容将会出现在网站上。

## 许可证
本插件采用了 MIT 许可证，详情请查看 [LICENSE](LICENSE) 文件。

Copyright © 2025 RinLit, All rights reserved.

## 鸣谢

### 贡献者
感谢这些为Hub投稿/贡献的同学:
[![Contributors](http://contrib.nn.ci/api?repo=RinLit-233-shiroko/Rin-sHub)](https://github.com/RinLit-233-shiroko/Rin-sHub/graphs/contributors)

感谢这些参演者：
<table>
	<tbody>
            <td align="center">
                <a href="#">
                    <img src="https://q2.qlogo.cn/headimg_dl?dst_uin=3295014118&spec=100" width="100;" alt="Rinlit"/>
                    <br />
                    <sub><b>Rinlit</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="#">
                    <img src="https://q2.qlogo.cn/headimg_dl?dst_uin=2414528438&spec=100" width="100;" alt="JerryQAQ"/>
                    <br />
                    <sub><b>JerryQAQ</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="#">
                    <img src="https://q2.qlogo.cn/headimg_dl?dst_uin=3339148906&spec=100" width="100;" alt="Aris"/>
                    <br />
                    <sub><b>Aris</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="#">
                    <img src="https://q2.qlogo.cn/headimg_dl?dst_uin=3995260769&spec=100" width="100;" alt="bbdqz (白白的群子)"/>
                    <br />
                    <sub><b>bbdqz (白白的群子)</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="#">
                    <img src="https://q2.qlogo.cn/headimg_dl?dst_uin=1562732243&spec=100" width="100;" alt="MC_AbleBlank"/>
                    <br />
                    <sub><b>MC_AbleBlank</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="#">
                    <img src="https://q2.qlogo.cn/headimg_dl?dst_uin=3763253157&spec=100" width="100;" alt="LyRin (零音)"/>
                    <br />
                    <sub><b>LyRin (零音)</b></sub>
                </a>
            </td>
		</tr>
		<tr>
            <td align="center">
                <a href="#">
                    <img src="https://q2.qlogo.cn/headimg_dl?dst_uin=3443873715&spec=100" width="100;" alt="纸飞机"/>
                    <br />
                    <sub><b>纸飞机</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="#">
                    <img src="https://q2.qlogo.cn/headimg_dl?dst_uin=小岳&spec=100" width="100;" alt="小岳"/>
                    <br />
                    <sub><b>小岳</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="#">
                    <img src="https://q2.qlogo.cn/headimg_dl?dst_uin=lokooo.&spec=100" width="100;" alt="lokooo."/>
                    <br />
                    <sub><b>lokooo.</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="#">
                    <img src="https://q2.qlogo.cn/headimg_dl?dst_uin=669968618&spec=100" width="100;" alt="干冰DryIce"/>
                    <br />
                    <sub><b>干冰DryIce</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="#">
                    <img src="https://q2.qlogo.cn/headimg_dl?dst_uin=2473768771&spec=100" width="100;" alt="夏辉7369"/>
                    <br />
                    <sub><b>夏辉7369</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="#">
                    <img src="https://q2.qlogo.cn/headimg_dl?dst_uin=1219439938&spec=100" width="100;" alt="姜胤"/>
                    <br />
                    <sub><b>姜胤</b></sub>
                </a>
            </td>
		</tr>
		<tr>
            <td align="center">
                <a href="#">
                    <img src="https://q2.qlogo.cn/headimg_dl?dst_uin=3382333681&spec=100" width="100;" alt="yuuka"/>
                    <br />
                    <sub><b>yuuka</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="#">
                    <img src="https://q2.qlogo.cn/headimg_dl?dst_uin=2221840752&spec=100" width="100;" alt="Nachoneko-甘城 (AI助理)"/>
                    <br />
                    <sub><b>Nachoneko-甘城 (AI助理)</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="#">
                    <img src="https://q2.qlogo.cn/headimg_dl?dst_uin=3645508750&spec=100" width="100;" alt="冷静的静冷"/>
                    <br />
                    <sub><b>冷静的静冷</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="#">
                    <img src="https://q2.qlogo.cn/headimg_dl?dst_uin=2，2，3-三甲基戊烷&spec=100" width="100;" alt="2，2，3-三甲基戊烷"/>
                    <br />
                    <sub><b>2，2，3-三甲基戊烷</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="#">
                    <img src="https://q2.qlogo.cn/headimg_dl?dst_uin=2774737215&spec=100" width="100;" alt="pizerolol"/>
                    <br />
                    <sub><b>pizerolol</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="#">
                    <img src="https://q2.qlogo.cn/headimg_dl?dst_uin=3469644172&spec=100" width="100;" alt="CoiaPrant"/>
                    <br />
                    <sub><b>CoiaPrant</b></sub>
                </a>
            </td>
		</tr>
		<tr>
            <td align="center">
                <a href="#">
                    <img src="https://q2.qlogo.cn/headimg_dl?dst_uin=quiet-star-gazing&spec=100" width="100;" alt="quiet-star-gazing"/>
                    <br />
                    <sub><b>quiet-star-gazing</b></sub>
                </a>
            </td>
        <tbody>
</table>


### 使用的资源

- [Fluent UI System Icons](https://github.com/microsoft/fluentui-system-icons)
- [各大群友设的精](#)
