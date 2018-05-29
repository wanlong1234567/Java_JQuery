# 一.jQuery中遇到的对象
## 1.通过$获得的都是jQuery对象
- $("p")
- $(p)
- $("<p></p>")

## 2.修改方法返回的是jQuery对象
- obj.html("abc")
- obj.attr("src","../images/02.jpg")

## 3.查询方法
### 1)若查到元素则返回jQuery对象
- obj.parent()
- obj.prev()

### 2)若查到文本则返回字符串
- obj.html()
- obj.val()

## 4.万能的判断方式
- 控制台输出

# 二.jQuery事件
## 1.事件概述
### 1)什么是事件
- 和js事件一样

### 2)事件的分类
- 和js事件一样

## 2.事件定义
### 1)直接定义事件
- 和js事件一样

### 2)动态绑定事件

	$(":button").click(function(){});

### 3)如何取消
- 和js事件一样

## 3.事件对象
### 1)什么是事件对象
- 和js事件一样

### 2)如何获得事件对象
- 和js事件一样
> jQuery对事件对象作出了一些改造

## 4.事件机制
### 1)冒泡机制
- 和js事件一样

### 2)取消冒泡

	e.stopPropagation()

### 3)作用
- 和js事件一样

### 4)事件源

	e.target

## 5.合成事件(了解)
- hover
- toggle

## 6.模拟事件(*)
- obj.trigger("click")