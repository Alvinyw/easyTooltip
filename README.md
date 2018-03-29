# easyTooltip: 鼠标移上去出现提示内容

## easyTooltip 介绍
```javascript
$(targetNode).easyTooltip({
	/************ tooltip 结构参数 ************/
	tooltipId: "easyTooltip",/*tooltip 最外层元素的 ID*/
	tooltipClass: "easyTooltip",/*tooltip 最外层元素的 Class*/
	content: "",/*设置 tooltip 的内容，可以包含 html 标签元素*/
	existedContentId: "",/*将已有元素的内容作为 tooltip 的内容，若不为空，则将替换 content 所设置的内容*/
	tooltipDir: "top",/*tooltip 出现的方向(top\right\bottom\left)*/
	xOffset: 5,/*tooltip 在 X 轴离鼠标的距离*/       
	yOffset: 5,/*tooltip 在 Y 轴离鼠标的距离*/
	clickRemove: false,/*是否点击隐藏 tooltip*/
	tooltipPosition: 'absolute',/*tooltip 是否会跟随鼠标移动(absolute\relative)*/
	/************ tooltip 样式参数 ************/
	defaultRadius: "3px",
	tooltipZindex: 10000,
	tooltipPadding: "10px 15px",
	tooltipBgColor: "rgba(200,200,200,0.7)",
	tooltipFtSize: "14px",
	tooltipLineHeight: "24px",
	tooltipFtColor: "#000",
	tooltipOpacity: 1,
	tooltipArwBorderWidth: 6
});
```
**参数说明：**
- 当 tooltipPosition 值为空或值为 "absolute" 时，tooltip 会随鼠标移动，且不会有小三角；当 tooltipPosition 值为 "relative" 时，tooltip 的位置相对于 *$(targetNode)* 固定，不会随鼠标移动，而且会有小三角；
- 当 existedContentId 为空时，tooltip 里的内容是 content，当 existedContentId 不为空时，不管 content 是否为空，tooltip 里的内容都是 existedContentId；
- tooltip 里小三角不是用伪元素画出来的，而是一个 class 为 arw 的 span 元素： **&lt;span class="arw">**，通过设置 arw 的 		  border 来实现小三角效果；
- tooltip 的样式代码如下：

  ```css
  position: absolute;
  z-index: 10000;
  display: none;
  padding: 10px 15px;
  background-color: rgba(200,200,200,0.7);
  font-size: 14px;
  line-height: 24px;
  color: #000;
  opacity: 1;
  border-radius: 3px;
  ```
- 小三角 arw 的样式代码为：

  ```css
  display: inline-block;
  position: absolute;
  width: 0;
  height: 0;
  border-style: solid;
  border-width: 6px;
  border-color: transparent;
  border-top-color: rgba(200,200,200,0.7);
  ```
## easyTooltip 调用

因为是基于 jQuery 开发的，所以要先引入 jQuery 文件：

```javascript
<script type="text/javascript" src="jquery.min.js"></script>
```

1. 默认用法（Tooltip 出现在上侧）

   ```html
   
   <script type="text/javascript">
   
   </script>
   ```
   
2. 默认用法（Tooltip 出现在上侧）

   ```html
   
   <script type="text/javascript">
   
   </script>
   ```
   
3. 默认用法（Tooltip 出现在上侧）

   ```html
   
   <script type="text/javascript">
   
   </script>
   ```
   
4. 默认用法（Tooltip 出现在上侧）

   ```html
   
   <script type="text/javascript">
   
   </script>
   ```
   
5. 默认用法（Tooltip 出现在上侧）

   ```html
   
   <script type="text/javascript">
   
   </script>
   ```
   
6. 默认用法（Tooltip 出现在上侧）

   ```html
   
   <script type="text/javascript">
   
   </script>
   ```
   
7. 默认用法（Tooltip 出现在上侧）

   ```html
   
   <script type="text/javascript">
   
   </script>
   ```
   
8. 默认用法（Tooltip 出现在上侧）

   ```html
   
   <script type="text/javascript">
   
   </script>
   ```
   
9. 默认用法（Tooltip 出现在上侧）

   ```html
   
   <script type="text/javascript">
   
   </script>
   ```
   
10. 默认用法（Tooltip 出现在上侧）

   ```html
   
   <script type="text/javascript">
   
   </script>
   ```
   
11. 默认用法（Tooltip 出现在上侧）

   ```html
   
   <script type="text/javascript">
   
   </script>
   ```
   
12. 默认用法（Tooltip 出现在上侧）

   ```html
   
   <script type="text/javascript">
   
   </script>
   ```
   
13. 默认用法（Tooltip 出现在上侧）

   ```html
   
   <script type="text/javascript">
   
   </script>
   ```
   
14. 默认用法（Tooltip 出现在上侧）

   ```html
   
   <script type="text/javascript">
   
   </script>
   ```
   
## easyTooltip 示例

[Demo](https://alvinyw.github.io/Blog/easyTooltip/easyTooltip.html)
