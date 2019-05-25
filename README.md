# 💕damai
- 💝 纯前端实现的大麦网购票网站，利用gulp进行项目的基本构建。
- ✨ 数据接口基本来自原站，通过ajax请求获取数据并渲染页面。
- 🍻 登录注册、购物车功能利用cookie实现。
- ❌ 搜索功能暂未实现，后续版本持续迭代中...

### 🎉安装与下载预览
- 下载地址 https://github.com/gsh0581/damai/releases
- 安装依赖包
- `npm install`
- 运行
- `gulp build`
- `gulp server`

# 入口文件地址
http://localhost:9999/pages/home/home.html

## 环境参数
- 技术语言 ：HTML、ES6、Sass
- 框架： Swiper、Bootstrap、jQuery
- 插件： jquery.validate、jquery.cookie
- 构建工具： gulp3.9.1
- 开发工具：VsCode


## 交流&提问
- 在issue区
- https://github.com/gsh0581/damai/issues
## 项目目录
```
├── LICENSE
├── README.md
├── dist
│   ├── pages
│   │   ├── account
│   │   │   ├── account.html
│   │   │   └── account.js
│   │   ├── category
│   │   │   ├── category.html
│   │   │   └── category.js
│   │   ├── home
│   │   │   ├── Untitled-1.js
│   │   │   ├── home.html
│   │   │   └── home.js
│   │   ├── login
│   │   │   ├── login.html
│   │   │   └── login.js
│   │   ├── order
│   │   │   ├── order.html
│   │   │   └── order.js
│   │   ├── product
│   │   │   ├── product.html
│   │   │   └── product.js
│   │   └── register
│   │       ├── register.html
│   │       └── register.js
│   ├── scripts
│   │   ├── data.js
│   │   └── libs
│   │       ├── bootstrap.js
│   │       ├── css.js
│   │       ├── jquery-2.0.3.js
│   │       ├── jquery-ui.js
│   │       ├── jquery.cookie.js
│   │       ├── jquery.validate.js
│   │       └── swiper.js
│   ├── static
│   │   ├── conf
│   │   │   └── config.js
│   │   └── scripts
│   │       └── require.js
│   └── styles
│       ├── bootstrap.css
│       ├── jquery-ui.css
│       ├── pages
│       │   ├── account
│       │   │   └── account.css
│       │   ├── base.css
│       │   ├── category
│       │   │   └── category.css
│       │   ├── home
│       │   │   └── home.css
│       │   ├── login
│       │   │   └── login.css
│       │   ├── order
│       │   │   └── order.css
│       │   ├── product
│       │   │   └── product.css
│       │   └── register
│       │       └── register.css
│       └── swiper.css
├── gulpfile.js
├── package-lock.json
├── package.json
├── src
│   ├── pages
│   │   ├── account
│   │   │   ├── account.html
│   │   │   └── account.js
│   │   ├── category
│   │   │   ├── category.html
│   │   │   └── category.js
│   │   ├── home
│   │   │   ├── home.html
│   │   │   └── home.js
│   │   ├── login
│   │   │   ├── login.html
│   │   │   └── login.js
│   │   ├── order
│   │   │   ├── order.html
│   │   │   └── order.js
│   │   ├── product
│   │   │   ├── product.html
│   │   │   └── product.js
│   │   └── register
│   │       ├── register.html
│   │       └── register.js
│   ├── scripts
│   │   └── libs
│   │       ├── bootstrap.js
│   │       ├── css.js
│   │       ├── jquery-2.0.3.js
│   │       ├── jquery-ui.js
│   │       ├── jquery.cookie.js
│   │       ├── jquery.validate.js
│   │       └── swiper.js
│   ├── static
│   │   ├── conf
│   │   │   └── config.js
│   │   └── scripts
│   │       └── require.js
│   └── styles
│       ├── bootstrap.scss
│       ├── jquery-ui.scss
│       ├── pages
│       │   ├── _mixins.scss
│       │   ├── account
│       │   │   └── account.scss
│       │   ├── base.scss
│       │   ├── category
│       │   │   └── category.scss
│       │   ├── home
│       │   │   └── home.scss
│       │   ├── login
│       │   │   └── login.scss
│       │   ├── order
│       │   │   └── order.scss
│       │   ├── product
│       │   │   └── product.scss
│       │   └── register
│       │       └── register.scss
│       └── swiper.scss
└── tree.md
```