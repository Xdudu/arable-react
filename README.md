最近在总结今年的工作，经常遇到深入探索某个知识点后想要重构某块代码的情况。由于代码牵涉了太多业务逻辑，我的重构又与之无关，为了尽量少受羁绊和影响，所以萌生了写这个repo的想法。习惯了用`webpack`打包，于是自己开发了一片可以自由写`React`的“试验田”。配置很简单轻巧，因为这个配置的使用场景是产出demo，就像耕种庄稼一样，收一批割一批。在这里可以快捷地进行实验，然后将其应用到正式项目，所以这里没有生产环境的配置。

#### 配置特点：
* React, with [Transforming class properties](http://babeljs.io/docs/plugins/transform-class-properties/) in stage-2

#### 目录结构：
```
src
 |-- entry.js
 |-- seed.js
 |-- index.css
 |-- seed.css
 |-- index.html
```

#### 用法：

1. `npm start` or `yarn start`
2. open `localhost:9000` in browser

