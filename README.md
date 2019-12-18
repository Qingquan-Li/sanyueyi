> 基于 Bootstrap v3.3.7 的响应式静态网站  
使用 [GitHub Pages](https://pages.github.com/) 方案，网站部署在 GitHub 上，具体思路如下：  
1. 在自己的开发环境中编写好项目；
2. 把项目部署到 GitHub 上，即[搭建 GitHub Pages](http://fatlitalk.com/#post/12)；
3. 把 https://fatlitalk.github.io/sanyueyi CNAME 为 www.sanyueyi.com 即可通过独立域名访问（根目录下新建一个 CNAME 文件，文件内容为域名： www.sanyueyi.com ）；在域名解析平台，把 www.sanyueyi.com CNAME 到 FatliTalk.github.io.（或为 sanyueyi.com 添加 A 记录指向 GitHub 提供的 185.199.109.153 ）
4. 注意：「GitHub Pages」顾名思义，部署在 GitHub 上的网站，只能是静态的（无数据交互的）网站，动态网站请部署到服务器。
