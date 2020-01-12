## Vue知识点

1. Vue 的优点

   - ```text
     
     ```

2. 轻量级框架：

   - 只关注视图层
   - 组件化
   - 结构、视图、数据分离
   - 虚拟DOM，提高运行效率

3. 为什么使用key？

   - 给每个节点添加唯一标识，diff算法能够识别此节点，高效更新虚拟DOM

4. computed与watch

   - computed 是基于响应式依赖进行缓存的，如果data中的属性未发生变化，则computed中的对应方法则不会再次执行

     ![computed](E:/Note/image/computed.png)

     ![computed2](E:/Note/image/computed2.png)

5. Vue全家桶

   - vue-cli 是一个基于Vue.js 进行快速开发的完整系统

     ```js
     //通过 @vue/cli 搭建交互式的项目脚手架
     npm install -g @vue/cli 	 //安装vue-cli
     通过 vue init webpack 项目名	 //创建你的项目
     ```

     ![1575709093252](E:/Note/image/1575709093252.png)

     ![test2](E:/Note/image/test2.jpg)