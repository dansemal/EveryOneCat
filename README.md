# MEME


**访问量**（自2021.6.311:00:00）

![](https://count.getloli.com/get/@dansemal@meme?theme=gelbooru-h)

点击对应的表情名可以直接到达表情列表，请注意：你在使用本仓库内的表情时请将Valine的CDN设置为下面表格中的任意一个


| 服务器 | CDN链接                                           |
| :----: | :------------------------------------------------ |
| Github | https://cdn.jsdelivr.net/gh/dansemal/meme@master/ |  |

### Valine/Waline

复制的列表可以直接复制到例如[butterfly](https://github.com/jerryc127/hexo-theme-butterfly)主题的`valine.json`内，或者是各种用于放Valine表情配置的地方

请注意：如果你想添加多个分类，请记得在每个分类的最后一个表情后面加个`,`否则Valine无法识别。假设下面这个表情为该系列最后一个表情：

```json
"hotkey1": "bilibiliHotKey/1.jpg"
```

你想在这个表情下面添加其他表情的时候，那么请在这个表情的后面加个`,`就像下面这样

```json
"hotkey1": "bilibiliHotKey/1.jpg",
```

如果你有新的表情包想要加入，你可以提出issue，或者直接发到[admin@bili33.top](mailto:admin@bili33.top)，并注上你的ID和表情包名字（中文英文都需要）

仓库内的那个PY脚本是我提前编写好用来写表情列表的脚本，如果你有需要可以随意取用

这里有跟本项目同类型的表情仓库，如果在本仓库未找到你想要的表情包可以到这里找 [表情速查](https://www.antmoe.ml/)

### MiniValine

直接复制每个分类中的MiniValine所提供的链接（其中`https://valinecdn.bili33.top/`可以替换为任意CDN链接（见上表）），然后放在`emotionUrl`里面即可，请注意遵循列表写法，如：

```html
<body>
    <div class="mvcomment"></div>
    <script>
      new MiniValine({
          el: '.mvcomment',
          appId: 'appId',
          appKey: 'appKey',
          placeholder: 'Write a Comment O(∩_∩)O~~',
          emotionUrl: ['https://valinecdn.bili33.top/alu','https://valinecdn.bili33.top/bilibiliHotKey']
      })
    </script>
</body>

```

### 表情分类



| :----------------------------------------------------------: | :----------------------------------------------------------: |
| [EveryOneCat](https://github.com/dansemal/meme/tree/master/doc/everyonecat.md) | ![嗯嗯](https://cdn.jsdelivr.net/gh/dansemal/meme@master/everyonecat/agree.png) |

### 免责声明

本仓库内所有图片均来源于网络，仅供学习交流使用。若用户违反相关法律法规造成损失，将由用户自行承担，本仓库所有者和PR提交者不承担一切责任！

