## 实现一个轻量 fabric

## 目录说明
- src 目录下是最简版的案例代码，我们看这个目录下的就行

## 实现思路
- 创建两层画布、一个 div 容器、一个缓冲层
- 编写 FabricObject 基类，所有画布上的物体都继承于它，如 Rect
- 添加画布鼠标交互事件
- 添加组类，框选多个物体的时候会用到
- 渲染的时候会从 Canvas 实例中的 _objects 对象开始遍历绘制，先绘制失活物体，再绘制激活物体

## 如何运行
在根目录下运行 npx vite 即可

## 缓存好文
https://www.cnblogs.com/axes/p/3567364.html?utm_source=tuicool

## 小发现
- 喜欢先校验非空 if(!obj) {} else {}
- 把变量都事先声明
