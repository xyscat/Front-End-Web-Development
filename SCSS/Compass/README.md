[Compass官网](http://compass-style.org/)

[阮一峰《Compass用法指南》](http://www.ruanyifeng.com/blog/2012/11/compass.html)

[Koala工具](http://koala-app.com/)

**Compass ?**

Compass 是 Sass 的工具库。

Sass 本身只是一个编译器，Compass 在其基础上，封装了一系列有用的模块和模板，补充 Sass 的功能。

> 每个语言都有自己的工具库，JS 的工具库……，你懂的。

**安装**

- 安装 Ruby：

我们已经安装过 Sass 了，有了 Ruby 环境了。

- 安装 Compass：

`gem install compass`

**项目初始化**

创建 Compass 初始项目：

`compass create myproject`

当前目录会有一个 `myproject`目录。

`cd myproject`，有一个 `sass`目录，`stylesheets`目录和一个`config.rb` 配置文件。

`sass` 目录存放 sass文件，`stylesheets` 目录存放 编译后的 CSS 文件。

**编译**

编译： `compass compile`

在 `sass` 目录中的 `scss` 文件会被编译为 `css`文件，保存到 `stylesheets` 目录中。

压缩编译：`compass compile --output-style compressed`

会编译为压缩的 css 文件。

自动编译：`compass watch`

自动监测 scss 文件变化，自动编译。

> [Koala](http://koala-app.com/) 也可以实现自动编译功能。





