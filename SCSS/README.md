Sass

**CSS 预处理器**

CSS 预处理器定义了一种新的语言（哇靠，又一种语言），基本思想是，用一种专门的编程语言，为 CSS 增加了一些编程的特性，将 CSS 作为目标生成文件，然后开发者就只要使用这种语言进行编码工作。

> 似乎 HTML 和 JavaScript 都有这种对应语言了，JS 对应 TS（TypeScript），其实就是相当于给开发者一个平台来写代码，编译器会将代码转为 HTML、CSS 和 JS，有没有想到 汇编 C JS 语言的发展与分级。还不是很懂，慢慢看，慢慢体会。

CSS 预处理器用一种专门的编程语言，进行 web 页面样式设计，编译为CSS 文件，供项目使用。

CSS 预处理器为 CSS 增加了一些编程特性，不需考虑浏览器兼容性问题。可以在 CSS 使用 变量、简单的逻辑程序、函数等类似于编程语言中的特性。

> 是的，CSS 并不能算一种语言，可能添加的这一层能算的上是一种语言了。对于这么做的好处。我们先不听被人讲，慢慢看，慢慢体会。

CSS 预处理器语言：

- Sass(SCSS)
- LESS
- Stylus
- Turbine
- Swithch CSS
- CSS Cacheer
- DT CSS

> 哇哦，这么多，概念上是一种语言，纳尼？出现这么多版本，快给我个标准！仿佛想起了“浏览器大战”，我的个乖乖……

> ps:所以说人生最痛苦的不是没有选择，而是选择太多！

> 其实，还有一个菜鸟的问题：有使用的必要吗？根据大牛的观点，是必须的！所以，那就学！

选择哪个，现在来看 Sass、LESS 和 Stylus 不错。到底学那个？这个慢慢看吧。

**Sass ?**

Sass官网描述：Sass 是一门高于 CSS 的元语言，它能用来清晰地、结构化地描述文件样式，有着比普通 CSS 更加强大的功能。

Sass 能够提供更简洁、更优雅的语法，同时提供多种功能来创建可维护和管理的样式表。

> 其实，没有体验过，光看是不能体会的，特别对于me来书。

Sass历史：Sass 是采用 Ruby 语言编写的一款 CSS 预处理器，2007年诞生。最初为配合 HAML（一种缩进式的 HTML 预处理器）而设计的。

> 我就说嘛，这是一个趋势，势不可挡，怀念写 HTML、CSS、JS的日子。

早期不如 LESS 普及？ 它的缩进式风格，无法兼容已有的 CSS 代码。所以早期比较渣。

> 那么来说，为什么不学 LESS？

**Sass SCSS ?**

> 看见上面括号的了，为啥还有个 SCSS？名字多？

Sass 和 SCSS 其实是同一种东西，平时都称之为 Sass，不同之处有：

- 文件拓展名不同，`.sass` 和 `.scss`。
- 语法书写方式不同，Sass 严格缩进式语法规则，没有`{{}}` 和 `；`，SCSS 就和 CSS 一样（我就这么说了，不一样再改！）。

> 那么来讲，Sass还是以前的渣喽，为嘛还把 SCSS 叫 Sass，你这么是害人家吗！

**Sass/SCSS 和 CSS 写法？**

> 看起来没啥不同。

> Sass我不想再提了，哈哈，被影响了。

SCSS 和 CSS 写法无差别。

> SCSS可以，我看好你！不要说现在 Sass 受欢迎，受欢迎的是 SCSS！

**SCSS环境安装**

- 安装 Ruby 环境：[链接](http://rubyinstaller.org/downloads)

- 安装 sass：[链接](http://www.w3cplus.com/sassguide/install.html)

安装：
`gem sources -a http://gems.ruby-china.org` 和 `gem install sass`

检查版本：`sass -v`

更新版本：`gem update sass`

卸载：`gem unstall sass`


