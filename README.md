#JS片段

### 点击其他区域关闭弹窗
```javascript
$(document).mouseup(function(e){
  var _con = $(' 目标区域 ');   // 设置目标区域
  if(!_con.is(e.target) && _con.has(e.target).length === 0){ // Mark 1
    some code...   // 功能代码
  }
});
```
