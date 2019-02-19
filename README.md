# test01

> test

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).


build文件夹：webpack打包配置
	build.js：生成环境构建脚本
	webpack.base.conf.js：webpack基础配置
	webpack.dev.conf.js：webpack开发环境配置
	webpack.prod.conf.js：webpack生产环境配置

config文件夹：项目配置
	dev.env.js：开发环境变量
	index.js：项目配置文件
	prod.env.js：生产环境变量

src文件：项目源码目录
	assets文件：静态资源目录
	components文件：公共组件目录
	router文件：前端路由
	App.vue：根组件
	main.js：入口js文件

static文件：纯静态资源，不会被webpack构建

.babelrc:babel配置，es6需要babel编译

.editorconfig：编译器的配置，编码，代码风格等

.gitignore：过滤无需上传到svn上的文件类型

package.json：项目配置文件，项目模块


