# ReactJS新闻 

第021期 (2017.03.26)

***

## 新闻

### React Native中更好的List Views(列表视图)

React Naive官方博客近日发表了新的List(列表)组件的消息，三月份的候选版本的0.43-rc.1中，加入了三种新的FlatList、SectionList与VirtualizedList组件，可以针对不同情况需求而使用，这三个新组件的数据来源，都可以对外部的数据流框架Relay、Redux或Flux store进行搭配使用。

- [官方博客](https://facebook.github.io/react-native/blog/2017/03/13/better-list-views.html)

### idx: 具有存在判断的函数

idx是一种工具型函数，用于寻遍对象(或数组)中的属性，当中间过程的的属性是null或undefined时，会直接返回。使用这个工具型函数的目的是因为要对对象中的具有maybe-typed属性连锁中解开，可以搭配Flow工具使用。目前ECMAScript中的类似功能仍然在草案中。要使用idx外还需要另外使用babel-plugin-idx。

- [官方博客](https://facebook.github.io/react-native/blog/2017/03/13/idx-the-existential-function.html)
- [idx](https://github.com/facebookincubator/idx)
- [babel-plugin-idx](https://www.npmjs.com/package/babel-plugin-idx)
- [ECMAScript草案Optional Chaining](https://github.com/claudepache/es-optional-chaining)

### 针对ECMAScript的Observables草案

Observables目前在许多知名的框架或函数库中比如RxJS与Bacon.js中，都是已经很普遍而且重要的特性。TC39近日拟定了Observables草案，有可能之后就会设计在JavaScript语言核心中。

- [Observables Proposal for ECMAScript!](https://ponyfoo.com/articles/observables-coming-to-ecmascript)
- [TC39的Observables for ECMAScript草案](https://github.com/tc39/proposal-observable)

***

## 教程&文档

- [React Conf 2017研习会所有视频](https://www.youtube.com/playlist?list=PLb0IAmt7-GS3fZ46IGFirdqKTIxlws7e0)
- [用Flow作React与Redux (+Thunk)类型检查- 第一部份](https://blog.callstack.io/type-checking-react-and-redux-thunk-with-flow-part-1-ad12de935c36#.hcrpjzstl)
- [比较原生iOS(Swift)与React-Native的效能](https://medium.com/the-react-native-log/comparing-the-performance-between-native-ios-swift-and-react-native-7b5490d363e2#.8cw3vch1d)
- [React Native应用栈，2017年3月](https://medium.com/react-native-development/react-native-app-stack-march-2017-f7605e02d46f#.nv1w7ylmb)
- [实作React Native中的正方体](https://medium.com/@youngchanje/implementing-cube-in-react-native-cb61b9a7e8c3#.oc660sex5)
- [setState()门](https://medium.com/javascript-scene/setstate-gate-abc10a9b2d82#.iev1x6a25)
- [React是慢的， React是快的: 优化React Apps的实作](https://medium.com/dailyjs/react-is-slow-react-is-fast-optimizing-react-apps-in-practice-394176a11fba#.nao700y2y)
- [我在开发React Native / Redux app过程中犯的11个错误](https://medium.com/dailyjs/11-mistakes-ive-made-during-react-native-redux-app-development-8544e2be9a9#.jah2xc8bo)

***

本电子报为每周末发刊，所有内容来自网络。如果您对内容有疑问，请到[ReactJS新闻网站][1]或[Github库][2]关注我们。

[1]: https://www.reactjs-tw.top/
[2]: https://github.com/eyesofkids/reactjs-news-weekly

