codes COPY from opcache status

将多台php服务器的opcache的状态页面统一到一个站点展示。

在代理服务器端部署index.html 和js静态资源

结合upstream\proxy_pass；将访问不同目录，代理至上游不同的服务器。

这样就可以同一个域名，访问不同的服务器上opcache的运行状态。