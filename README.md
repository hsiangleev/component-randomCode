# component-randomCode
### 画布-随机验证码
[链接](https://hsiangleev.github.io/component-randomCode/randomCode.html)

* html模板: 
``` javascript
<div class="c-code">
	<canvas id="c-cvs"></canvas>
</div>
```
* 使用: 
* 1. 引用js文件
* 2. 在模板之外添加一个盒子，宽高必须给，验证码宽高与之相等
* 3. 每调用一次drawBg()，刷新一次
* 4. drawBg().textArr 得到当前的文本内容存为数组
* 5. drawBg().text 得到当前的文本内容存为字符串
