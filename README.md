## 如何显示GitHub pages？

第一次尝试：
先有readme文件，再传html文件但名字非index，那么GitHub pages会显示哪个呢？

结果：
GitHub Pages设置好master branch为site source之后，等待一会，刷新页面。页面显示的为readme.md的内容。

第二次尝试：删除readme文件，看看非index名字的网页能否显示

结果：
网页提醒
> you must provide an index.html file. 

显然，缺少名字为index的HTML。那么把名字改为index

结果: 改名字为index后显示成功


最后，如果同时有readme.md和index.html文件，那么会怎么显示呢？


最终结论：同时有readme和index.html时会显示index的页面。如果没有index的页面就会显示readme的内容！
