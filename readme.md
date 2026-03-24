本地预览
在项目根目录执行：

cd "/home/pony/文档/ppt-present" && python3 -m http.server 8000

浏览器打开 http://127.0.0.1:8000/。操作：方向键 / 空格 翻页，Esc 概览。

后续你只要改 index.html 里 <div class="slides"> 下的 <section> 即可增删页；换主题可把 night.css 换成 reveal.js 自带的其它 dist/theme/*.css。若你希望改成 npm 本地依赖或加插件（Markdown、代码高亮等），可以说一下偏好我帮你接上。