## g6 Plugin XQuark

官方Mimimap存在错误，而且不好看

### Setup

```sh
npm install -S g6-plugin-xquark
```

需要先安装好`@antv/g6`  



### Use

```
const { Minimap } = require('g6-plugin-xquark')
```

使用方法和配置和官方一致

`scss`配置

```SCSS
.g6-minimap-container{
  background-color:inherit;
  overflow: hidden;
  cursor: move;
  height: 100%;
  z-index: 10;
  .g6-minimap-viewport{
    background:white;
    border:1px solid #43439977;
    z-index:-1;
  }
}
```



### 效果预览

![image-20191206165239073](https://github.com/wuchuanxun/g6-plugin-xquark/blob/master/assets/image-20191206165239073.png)
