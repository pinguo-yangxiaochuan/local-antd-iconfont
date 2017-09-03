* 基于create-react-app环境的字体图标本地部署
* 配置及使用
```
在webpack中配置：resolve.modules = ['xx', 'node_modules']，
即是将webpack解析路径指向xx 和 node_modules目录去。

根据 https://www.npmjs.com/package/less-loader 的文档介绍，可以使用~直接引用这两个目录下的文件
@import '~antd/dist/antd.less';
@icon-url: '~iconfont/iconfont';
``` 