# Array.prototype.filter

数组筛选，常用于对数组的每条数据过滤，非常好用

```js
/**
 * @file 数组筛选
 *
 * @description 只保留回调里返回true的结果集，不会对原数组有影响
 *              如果所有回调都没有返回true，则结果为空数组
 * @param {Function} fn 回调，参数1为当前循环的值，参数2为索引，参数3为目标数组
 * @param {Object|undefined} context 回调fn的this的上下文
 * @return {boolean} 判断结果，必须全部返回true才为true，否则为false
 * @example
 *     Array.prototype.filter(fn [,context]);
 */
```

## 兼容性

兼容 `ie9+` ，[link](http://kangax.github.io/compat-table/es5/#test-Array.prototype.filter)