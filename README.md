## storage.js
封装的localStorage方法

## 介绍
+ 存储storage数据
+ 获取storage数据
+ 清除storage指定数据
+ 清除storage全部数据

## 使用
+ 任意组件引入
```js
import { setStore, getStore, clearStore, clearAll } from '@/utils/storage.js'
```

+ 调用storage方法
```js
// 存储数据
setStore('userName', {userName: 'admin'})

// 获取数据
console.log(getStore('userName')) // {userName: 'admin'}

// 清除userName
clearStore('userName')

// 清除全部storage数据
clearAll()
```