# 所了解的vue知识
根据Vue.js官网做的一系列练习和总结。学习 Vue ，他的学习曲线平稳很多；不管选择什么框架，除了对基础的知识有一定的了解掌握，还应该对 ES6 有一定的了解；</br>
![image](https://github.com/gyjian/vue/blob/master/img/API.png)</br>
这张图概况了 Vue 通过尽可能简单的 API 实现响应的数据绑定和组合的视图组件</br>
### vue相关特性
key<br>
Vue 为了尽可能高效地渲染元素，通常会重复利用已有元素而不是从头开始渲染。这么做的目的是 Vue 变得非常快。如果我们不想复用已有的元素，即切换到注册的时候，清空账号和密码，那key就派上用场了，在标签内加入 key="username-input" 和 key="username-password" ,就清除复用了，此时 Vue 元素就是重头开始渲染。</br>
