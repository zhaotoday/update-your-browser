## 浏览器检测
https://github.com/ded/bowser

## 使用
放在页面最开始的位置，可以按实际情况修改条件语句。
```js
<script src="update-browser/scripts/bowser.js"></script>
<script>
  if (!((bowser.msie && bowser.version >= 10) || bowser.msedge || bowser.webkit || bowser.firefox))
    location.replace('update-browser/index.html')
</script>
```
