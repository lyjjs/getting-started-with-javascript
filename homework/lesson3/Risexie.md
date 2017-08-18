第三节课总结
===
### 浏览器和服务器的交互原理
在浏览器当中只要我们输入一个网址（URL)，浏览器就会神奇地给我们打开一个网页。翻墙之后，更是可以浏览到全世界的信息，那么这到底是如何实现的呢？

简单来说，就是当我们在浏览器输入网址的时候，我们会通过http协议，给服务器发起一次相关URL内容的请求。当服务器接收了我们的请求，解析相关内容，然后再返回信息到我们的浏览器上面。
从这里可以看出，其实我们打开网页之后的内容是在我们请求过后，服务器“一次性”给我们提供的。这些内容可能是第三方库的代码、html、css等，在浏览器给我们缓存了之后，再呈现出来。所以其实我们并不是一直和服务器相连接的，在返回了相关请求内容之后，我们与服务器的连接就会中断。

### 数据那些事
数据有非常多种的类型，每一种类型其实都有自己的作用，而他们的传递效率也是各不相同。
当我们我们在调用一个数组数据的时候，其实电脑还同时调用了这个数组相关的长度、项数等信息。所以如果胡乱地使用数据类型的话，我们就会浪费计算机的内存和计算效率。我想别人经常提到的“优化”，其实就是更高效地实用不同的数据类型，来实现同样的需求。

### 命名的力量
我们所编写的代码除了给计算机运行之外，还可能经过很多程序员的审阅，优秀的代码不但运行高效，还可以给别的程序员带来启发，与收获。所以在编码的时候保持代码的易读性，对于成为一名优秀的程序员来说是必不可少的。而命名数据所使用名字适否恰当，直接代表了这份代码的易读与否。
命名的要点是：
>要what不是how

例如我们在输入某个用户的的数据的时候，用的应该是`'personIMF'`,而不是`'input'`。