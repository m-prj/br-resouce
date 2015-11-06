# br-resouce
【broccoli】refInfo Class

クライアント側
```js
var psdFileInfo = e.target.files[0];;
var resInfo = new resouce();
resInfo.size = psdFileInfo.size;
resInfo.ext = (psdFileInfo.name).uGetFileExt();
resInfo.type = psdFileInfo.type;
resInfo.readSelectedLocalFile(psdFileInfo, function(obj){
  // ここに処理を書く
});
```
