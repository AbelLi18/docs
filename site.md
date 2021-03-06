# 多站点

>   目前基础版提供4个站点：分别为 桌面站点(desktop)、API站点(api)、文档站点(doc)与管理后台站点(admin) 。

>   注意，上述四个站点您可以根据实际需要绑定特定独立的（子）域名来访问。

### 桌面站点

基础版桌面站点只有 `YASCMF` 宣传页页面，博客内容页面已被移除；但[官方博客](http://blog.yascmf.com/)已更新新版主题，欢迎访问体验。

前台已启用新的轻博客，下载 `base` 源码即可体验，使用 `markdown` 撰写博客的快感。

### API站点

>   特别注意，最新版中已移除IP归属地与身份证归属地查询两个服务，挪到 `yascmf/api` 项目中。

API站点也只提供了三个开放的 `API` 服务（身份证归属地、IP归属与汉字转拼音查询）。你可以通过访问下面 `URL` 地址来获取示例信息：

>   https://www.yascmf.com/api/ip?ip=14.215.177.37  
>   https://www.yascmf.com/api/identity-card?pid=42032319930606629x  
>   https://www.yascmf.com/api/pinyin?content=%E4%BD%A0%E5%A5%BD%E4%B8%96%E7%95%8C


### 文档站点

基础版文档站点提供了不完整的 `YASCMF` 文档，你可以访问[官网](http://www.yascmf.com/docs/index) 获取最新较全的文档。

### 管理后台站点

管理后台站点默认使用 `admin` 作为路由前缀，可在配置中修改，绑定域名（如 `www.yascmf.dev`）部署到本地之后，通过 `http://www.yascmf.dev/admin` 即可访问。
