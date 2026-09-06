# 谢奇妍 · 个人主页

这是一个由 YAML 配置和 Markdown 内容驱动的静态个人主页，适合直接部署到 GitHub Pages。

## 本地预览

在项目根目录启动任意静态服务器，例如：

~~~bash
npx http-server . -p 4173 -c-1
~~~

然后访问 http://127.0.0.1:4173。

请通过本地服务器访问，不要直接双击打开 index.html；否则浏览器可能阻止页面读取 YAML 和 Markdown 内容。

## 内容维护

- 页面配置：contents/config.yml
- 个人资料、教育、技能与经历：contents/home.md
- 科创项目：contents/publications.md
- 竞赛与荣誉：contents/awards.md
- 图片资源：static/assets/、images/
