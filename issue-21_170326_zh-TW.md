# ReactJS新聞 

第021期 (2017.03.26)

***

## 新聞

### React Native中更好的List Views(列表視圖)

React Naive官方部落格近日發表了新的List(列表)元件的消息，三月份的候選版本的0.43-rc.1中，加入了三種新的FlatList、SectionList與VirtualizedList元件，可以針對不同情況需求而使用，這三個新元件的資料來源，都可以對外部的資料流框架Relay、Redux或Flux store進行搭配使用。

- [官方部落格](https://facebook.github.io/react-native/blog/2017/03/13/better-list-views.html)

### idx: 具有存在判斷的函式

idx是一種工具型函式，用於尋遍物件(或陣列)中的屬性，當中間過程的的屬性是null或undefined時，會直接回傳。使用這個工具型函式的目的是因為要對物件中的具有maybe-typed屬性連鎖中解開，可以搭配Flow工具使用。目前ECMAScript中的類似功能仍然在草案中。要使用idx外還需要另外使用babel-plugin-idx。

- [官方部落格](https://facebook.github.io/react-native/blog/2017/03/13/idx-the-existential-function.html)
- [idx](https://github.com/facebookincubator/idx)
- [babel-plugin-idx](https://www.npmjs.com/package/babel-plugin-idx)
- [ECMAScript草案Optional Chaining](https://github.com/claudepache/es-optional-chaining)

### 針對ECMAScript的Observables草案

Observables目前在許多知名的框架或函式庫中例如RxJS與Bacon.js中，都是已經很普遍而且重要的特性。TC39近日擬定了Observables草案，有可能之後就會設計在JavaScript語言核心中。

- [Observables Proposal for ECMAScript!](https://ponyfoo.com/articles/observables-coming-to-ecmascript)
- [TC39的Observables for ECMAScript草案](https://github.com/tc39/proposal-observable)

***

## 教學&文章

- [React Conf 2017研討會所有影片](https://www.youtube.com/playlist?list=PLb0IAmt7-GS3fZ46IGFirdqKTIxlws7e0)
- [用Flow作React與Redux (+Thunk)類型檢查- 第一部份](https://blog.callstack.io/type-checking-react-and-redux-thunk-with-flow-part-1-ad12de935c36#.hcrpjzstl)
- [比較原生iOS(Swift)與React-Native的效能](https://medium.com/the-react-native-log/comparing-the-performance-between-native-ios-swift-and-react-native-7b5490d363e2#.8cw3vch1d)
- [React Native應用堆疊，2017年3月](https://medium.com/react-native-development/react-native-app-stack-march-2017-f7605e02d46f#.nv1w7ylmb)
- [實作React Native中的正方體](https://medium.com/@youngchanje/implementing-cube-in-react-native-cb61b9a7e8c3#.oc660sex5)
- [setState()門](https://medium.com/javascript-scene/setstate-gate-abc10a9b2d82#.iev1x6a25)
- [React是慢的， React是快的: 優化React Apps的實作](https://medium.com/dailyjs/react-is-slow-react-is-fast-optimizing-react-apps-in-practice-394176a11fba#.nao700y2y)
- [我在開發React Native / Redux app過程中犯的11個錯誤](https://medium.com/dailyjs/11-mistakes-ive-made-during-react-native-redux-app-development-8544e2be9a9#.jah2xc8bo)

***

本電子報為每週末發刊，所有內容來自網路。如果您對內容有疑問，請到[ReactJS新聞網站][1]或[Github庫][2]關注我們。

[1]: https://www.reactjs-tw.top/
[2]: https://github.com/eyesofkids/reactjs-news-weekly

