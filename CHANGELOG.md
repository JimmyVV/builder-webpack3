<a name="0.3.4"></a>
## [0.3.4](https://github.com/iv-web/builder-webpack/compare/v0.3.3...v0.3.4) (2018-03-22)


### Bug Fixes

* 去掉离线包里面的script标签上的intergrity属性 ([ad0c5a0](https://github.com/iv-web/builder-webpack/commit/ad0c5a0))



<a name="0.3.3"></a>
## [0.3.3](https://github.com/iv-web/builder-webpack/compare/v0.3.2...v0.3.3) (2018-03-20)


### Features

* 增加process.env.NODE_ENV, 避免线上报warning. ([fcd2f3c](https://github.com/iv-web/builder-webpack/commit/fcd2f3c))



<a name="0.3.2"></a>
## [0.3.2](https://github.com/iv-web/builder-webpack/compare/v0.3.1...v0.3.2) (2018-03-20)


### Bug Fixes

* 离线包的assets去掉url paramter. ([5da0139](https://github.com/iv-web/builder-webpack/commit/5da0139))



<a name="0.3.1"></a>
## [0.3.1](https://github.com/iv-web/builder-webpack/compare/v0.2.19...v0.3.1) (2018-03-20)


### Bug Fixes

* 离线包注入version. ([213860b](https://github.com/iv-web/builder-webpack/commit/213860b))
* 离线包问题解决. ([676b365](https://github.com/iv-web/builder-webpack/commit/676b365))



<a name="0.3.0"></a>
# [0.3.0](https://github.com/iv-web/builder-webpack/compare/v0.2.19...v0.3.0) (2018-03-19)


### Bug Fixes

* 离线包问题解决. ([676b365](https://github.com/iv-web/builder-webpack/commit/676b365))



<a name="0.2.19"></a>
## [0.2.19](https://github.com/iv-web/builder-webpack/compare/v0.2.18...v0.2.19) (2018-03-19)


### Features

* 集成babel-plugin-import. ([a868a1c](https://github.com/iv-web/builder-webpack/commit/a868a1c))



<a name="0.2.18"></a>
## [0.2.18](https://github.com/iv-web/builder-webpack/compare/v0.2.16...v0.2.18) (2018-03-19)


### Bug Fixes

* 修复import语法错误. ([3197be6](https://github.com/iv-web/builder-webpack/commit/3197be6))


### Features

* externals引入的js lib也加上crossorigin. ([553f050](https://github.com/iv-web/builder-webpack/commit/553f050))



<a name="0.2.16"></a>
## [0.2.16](https://github.com/iv-web/builder-webpack/compare/v0.2.15...v0.2.16) (2018-03-19)


### Features

* 给生成的js bundle增加crossorigin头,便于记录错误日志详细堆栈. ([bc7fce5](https://github.com/iv-web/builder-webpack/commit/bc7fce5))



<a name="0.2.15"></a>
## [0.2.15](https://github.com/iv-web/builder-webpack/compare/v0.2.13...v0.2.15) (2018-03-11)


### Bug Fixes

* sytax error. ([04e8d28](https://github.com/iv-web/builder-webpack/commit/04e8d28))


### Features

* alias支持自定义配置. ([a8cca61](https://github.com/iv-web/builder-webpack/commit/a8cca61))
* externals支持配置. ([5915fa7](https://github.com/iv-web/builder-webpack/commit/5915fa7))



<a name="0.2.13"></a>
## [0.2.13](https://github.com/iv-web/builder-webpack/compare/v0.2.12...v0.2.13) (2018-03-09)


### Features

* 支持css后缀的解析规则. ([5878cdd](https://github.com/iv-web/builder-webpack/commit/5878cdd))



<a name="0.2.12"></a>
## [0.2.12](https://github.com/iv-web/builder-webpack/compare/v0.2.11...v0.2.12) (2018-03-09)


### Features

* 增加字体解析规则. ([1c50ca9](https://github.com/iv-web/builder-webpack/commit/1c50ca9))



<a name="0.2.11"></a>
## [0.2.11](https://github.com/iv-web/builder-webpack/compare/v0.2.10...v0.2.11) (2018-03-08)


### Features

* 支持ES7 decorators特性 ([7130086](https://github.com/feflow/builder-webpack3/commit/f12b23e201301fdc61f850ebada5e4ff488b98c2))


<a name="0.2.10"></a>
## [0.2.10](https://github.com/iv-web/builder-webpack/compare/v0.2.9...v0.2.10) (2018-03-08)


### Features

* 支持生产环境inlineCSS配置 ([7130086](https://github.com/feflow/builder-webpack3/commit/88b17806872743ff3558df9cdf0da5435a1fa828))


<a name="0.2.9"></a>
## [0.2.9](https://github.com/iv-web/builder-webpack/compare/v0.2.8...v0.2.9) (2018-01-15)


### Features

* replace-text-loader兼容webpack2.x版本 ([7130086](https://github.com/iv-web/builder-webpack/commit/7130086))
* 集成雪碧图功能. ([4cb899c](https://github.com/iv-web/builder-webpack/commit/4cb899c))



<a name="0.2.8"></a>
## [0.2.8](https://github.com/iv-web/builder-webpack/compare/v0.2.7...v0.2.8) (2018-01-09)


### Bug Fixes

* 修复依赖引入问题. ([72073f4](https://github.com/iv-web/builder-webpack/commit/72073f4))



<a name="0.2.7"></a>
## [0.2.7](https://github.com/iv-web/builder-webpack/compare/v0.2.6...v0.2.7) (2018-01-09)


### Features

* 支持scss文件中资源根据绝对路径方式加载 ([7a4b05e](https://github.com/iv-web/builder-webpack/commit/7a4b05e)), closes [close#4](https://github.com/close/issues/4)



<a name="0.2.6"></a>
## [0.2.6](https://github.com/iv-web/builder-webpack/compare/v0.2.5...v0.2.6) (2017-12-21)


### Bug Fixes

* 清楚public目录bug修复. ([b4a7371](https://github.com/iv-web/builder-webpack/commit/b4a7371))



<a name="0.2.5"></a>
## [0.2.5](https://github.com/iv-web/builder-webpack/compare/v0.2.4...v0.2.5) (2017-12-21)


### Features

* inline html语法支持. ([fa73977](https://github.com/iv-web/builder-webpack/commit/fa73977))



<a name="0.2.4"></a>
## [0.2.4](https://github.com/iv-web/builder-webpack/compare/v0.2.3...v0.2.4) (2017-12-21)


### Features

* 支持fis3的inline语法糖. ([071b392](https://github.com/iv-web/builder-webpack/commit/071b392))



<a name="0.2.3"></a>
## [0.2.3](https://github.com/iv-web/builder-webpack/compare/v0.2.1...v0.2.3) (2017-12-18)


### Bug Fixes

* 打包的静态资源路径问题修复 ([55ad4c1](https://github.com/iv-web/builder-webpack/commit/55ad4c1))


### Features

* 对打包出来的html里面replace掉cdn目录路径 ([db9f88a](https://github.com/iv-web/builder-webpack/commit/db9f88a))



<a name="0.2.1"></a>
## [0.2.1](https://github.com/iv-web/builder-webpack/compare/v0.2.0...v0.2.1) (2017-12-18)


### Bug Fixes

* 修复静态资源的引用问题. ([47dc18b](https://github.com/iv-web/builder-webpack/commit/47dc18b))



<a name="0.2.0"></a>
# [0.2.0](https://github.com/iv-web/builder-webpack/compare/v0.2.0-beta.4...v0.2.0) (2017-12-11)
### Bug Fixes

* clean public folder path ([7822a3a](https://github.com/iv-web/builder-webpack/commit/7822a3a))
* remove loader and plugin dependencies in project. ([da9bafc](https://github.com/iv-web/builder-webpack/commit/da9bafc))
* cli show colors and repair dependencies. ([2e8640d](https://github.com/iv-web/builder-webpack/commit/2e8640d))

### Features

* 集成dev和build命令 ([2baa8ec](https://github.com/iv-web/builder-webpack/commit/2baa8ec))



<a name="0.1.5"></a>
## [0.1.5](https://github.com/iv-web/builder-webpack/compare/v0.1.4...v0.1.5) (2017-12-09)


### Features

* 支持非git项目类型的构建 ([8953557](https://github.com/iv-web/builder-webpack/commit/8953557))



<a name="0.1.4"></a>
## [0.1.4](https://github.com/iv-web/builder-webpack/compare/v0.1.3...v0.1.4) (2017-12-07)


### Features

* 支持css绝对路径的写法 ([a9f2d2b](https://github.com/iv-web/builder-webpack/commit/a9f2d2b))



<a name="0.1.3"></a>
## [0.1.3](https://github.com/iv-web/builder-webpack/compare/56c9b55...v0.1.3) (2017-12-06)


### Bug Fixes

* css解析增加auto prefixer ([ec9cf73](https://github.com/iv-web/builder-webpack/commit/ec9cf73))


### Features

* webpack构建配置 ([56c9b55](https://github.com/iv-web/builder-webpack/commit/56c9b55))
* 基础包通过cdn引入 ([d6763fc](https://github.com/iv-web/builder-webpack/commit/d6763fc))
* 支持绝对路径import语法 ([33ab7c6](https://github.com/iv-web/builder-webpack/commit/33ab7c6))
