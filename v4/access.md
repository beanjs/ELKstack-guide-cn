Kibana 是让你从 5601 端口访问的网页应用。你需要做的只是打开浏览器，然后输入你运行 Kibana 的机器地址然后加上端口号。比如说：`localhost:5601` 或者 `http://YOURDOMAIN.com:5601`。

当你访问 Kibana 的时候，默认会加载 Discover 页以及默认的索引模式。时间选择器默认为最近 15 分钟。而搜索条件是全部匹配(*)。

如果你没看到任何文档，尝试放宽时间选择器范围。如果还没有，可能你确实没往 Elasticsearch 里写进数据。