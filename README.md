#### 操作
- 进入项目，执行``npm run dev``，添加新的样式，sass会自动转化为css，然后``npm publish``才会生效
- ``npm publish`` 之前，执行``npm version patch``，自动更新版本号(具体规则，现在先不管，目前这个指令能达到我想要的效果)
- 项目中更新包，使用``npm update jy-public.css``

#### 目标
- 后面可改进为通过webpack打包生成index.css文件
- 需要添加上浏览器前缀，目前这种写法还没研究明白怎么添加上
