# jQuery calenders

一款简洁扩展方便的日历组件

## How to use?

依赖jQuery

```html
    <script src="cdn.bootcss.com/jquery/1.11.1/jquery.min.js" type="text/javascript"></script>   
```

引入相应的源文件
```html
    <!-- 日历组件 -->
    <script src="./jquery.calender.js" type="text/javascript"></script>   
    <link rel="stylesheet" href="./calender-theme.css">   
    <!-- 日历区间选取组件 -->
    <script src="./jquery.calender.select.js" type="text/javascript"></script>   
    <link rel="stylesheet" href="./calender-theme-select.css">   
    <!-- 工作周选取组件 -->
    <script src="./jquery.weeks.js" type="text/javascript"></script>   
    <link rel="stylesheet" href="./weeks-theme.css">   
```


创建input元素
```html
<input type="text">
```

调用

```javascript

$('input').calender(); // 日历组件
$('input').doubleMonth(); // 日历区间选取组件
$('input').weeks(); // 工作周选取组件

```
