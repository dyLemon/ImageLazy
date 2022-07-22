# 使用

```
1. 安装依赖 `npm i vue-imagelazy-dy`
```

```
2. 在main.ts中

引入插件
import VueImagelazy from vue-imagelazy-dy

const app = createApp(App);
注册全局
app.use(VueImagelazy)
```

```
组件中使用
 <img v-imageLazy="baseImg" src="" :imgsrc="item" />

baseImg:  默认图片地址
imgsrc:   真正图片地址，最后赋值给src

```
