# hugo-binder-theme

主题魔改自[hugo-theme-nostyleplease](https://github.com/hanwenguo/hugo-theme-nostyleplease)，基于hugo v0.139.0

```
|   config.toml
+---assets
+---data
|   |   menu.toml
|   |   SVG.toml
|   \---goods
|           goods.json
+---layouts
|   |   index.html # 请在此处进行Homepage页面站点名修改。
|   +---partials
|   |       comment.html # 请在此处进行评论区链接修改。
|   +---posts
|   |       diary.html # 单页文章diary布局，需要时请在front-matter中填入`layout: "diary"`，否则为默认文章布局（如`single.html`）
|   |       list.html
|   |       single.html
|   \---_default
|       |   index_view.html # 另一种Home主页布局，需要时可以复制到上级目录`layouts`中，并更名为`index.html`（请注意只能存在一个`index.html`，因而会替换原有的Home主页布局文件）
|       |   rss.xml # RSS设置，默认不输出文章具体description
```

## 使用素材鸣谢 Resource Credit

- [「素材屋405番地」](http://sozaiya405.chu.jp/405) 
- [bg by cairovercoat](http://cairovercoat.tumblr.com/tagged/pixel+pattern)
- [scripted resources](https://scripted.neocities.org/#)
