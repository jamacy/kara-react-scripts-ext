# react-scripts

This package includes scripts and configuration used by [Create React App](https://github.com/facebookincubator/create-react-app).<br>
Please refer to its documentation:

* [Getting Started](https://github.com/facebookincubator/create-react-app/blob/master/README.md#getting-started) – How to create a new app.
* [User Guide](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md) – How to develop apps bootstrapped with Create React App.

# 脚手架

  写在前面

  基于社区`create-react-app`库调整部分适用于kara项目的移动端web构建

  与社区库保持同步


  ## 主要修改

  - 配置支持CSS modules

  - 配置支持Sass预编译

  - 在原babel基础上扩展一些可以增加的支持（比如decorators），更多的语言特征和polyfill，移动端需要的react-hot-loader/babel、transform-runtime等插件

  - 在原Eslint配置基础上增加更严格要求的rules

  - 在原postcss配置上增加插件（比如pxtorem、utilities）

  - 移动端的各种深入配置

  - 增加stylelint检查

  - 增加git提交hooky
