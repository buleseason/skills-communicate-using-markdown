# Daily Learning

## Morning Planning

<img alt="Cloudy morning" src="https://octodex.github.com/images/cloud.jpg" width="100" align="right">

- [ ] Check out the [github blog](https://github.blog/) for topic ideas.
- [ ] Learn about [GitHub Pages](https://skills.github.com/#first-day-on-github).
- [ ] Convert my first blog post into an actual webpage.
- 1 `[ ]`方括代表的是勾和叉。
- 2 如果`[文字]`+`(网站)`用方括和圆括，可以将网站嵌入文字中，文字会高亮。
- 3 `img alt`赋予图片名称，`src`是网址，`width`是大小 `align`是位置
  
## Review


Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
- 1 三个` ```代表的是全齐标记，可以高亮一大片的区域。```
