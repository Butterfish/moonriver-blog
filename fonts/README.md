# 月河网页字体

这些字体与网站一起提供，不依赖访客设备安装字体或第三方 CDN。

- `serif/`：Noto Serif SC（思源宋体同源），Fontsource 5.3.0，400 字重。
  来源：https://www.npmjs.com/package/@fontsource/noto-serif-sc
- `wenkai/`：LXGW WenKai Screen，网页分片包 1.522.0。
  来源：https://www.npmjs.com/package/lxgw-wenkai-screen-web
  上游：https://github.com/lxgw/LxgwWenKai-Screen

各目录保留原始 SIL Open Font License。网页家族别名为 Moonriver Serif / Moonriver WenKai，未修改字形。仅保留 WOFF2，通过 unicode-range 按页面实际使用的字符加载所需分片，font-display: swap 允许先显示备用字体。粗体由浏览器合成。

CSS 使用相对路径，前端入口通过 withBase 加载，适配 GitHub Pages 子目录。后台仅向已通过本机或手机配对访问检查的请求提供这些资源。
