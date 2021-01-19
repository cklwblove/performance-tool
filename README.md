
### 使用方式

  1. npm install --save-dev performance-tool  <br/>

  2. 在项目中引入：import performance from 'performance-tool'; <br/>

  3. 在项目中对应位置使用： performance.getPerformanceTiming();  <br/>

  执行结果如下所示：<br/>

<img src="https://raw.githubusercontent.com/tugenhua0707/react-collection/master/images/57.jpg" /> <br />

<a href="https://www.cnblogs.com/tugenhua0707/p/10982332.html">了解更多，请看这篇文章</a> <br />

### window 全局用法

```javascript
 <script src="./performance.js"></script>
 <script type="text/javascript">
    window.onload = function() {
      window.performanceTool.getPerformanceTiming();
    };
  </script>
```
