# XMLHttpRequest.onreadystatechange

只要 readyState 属性发生变化，就会调用相应的处理函数。这个回调函数会被用户线程所调用。XMLHttpRequest.onreadystatechange 会在 XMLHttpRequest 的readyState 属性发生改变时触发 readystatechange 事件的时候被调用。

> 警告：这个方法不该用于同步的requests对象,并且不能在内部(C++)代码中使用.

当一个 XMLHttpRequest 请求被 abort() 方法取消时，其对应的 readystatechange 事件不会被触发。