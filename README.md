web 性能可以通过以下几方面来优化
content 方面
1、减少 HTTP 请求：合并文件、CSS 精灵、inline Image

2、减少 DNS 查询：DNS 缓存、将资源分布到恰当数量的主机名

3、减少 DOM 元素数量

Server 方面
1、使用 CDN

2、配置 ETag

3、对组件使用 Gzip 压缩

Cookie 方面
1、减小 cookie 大小

2、css 方面

3、将样式表放到页面顶部

4、不使用 CSS 表达式

5、使用<link>不使用@import

Javascript 方面
1、将脚本放到页面底部

2、将 javascript 和 css 从外部引入

3、压缩 javascript 和 css

4、删除不需要的脚本

5、减少 DOM 访问

图片方面
1、优化图片：根据实际颜色需要选择色深、压缩

2、优化 css 精灵

3、不要在 HTML 中拉伸图片
