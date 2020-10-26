



**3. vue文件中将需要懒加载的图片绑定 v-bind:src 修改为 v-lazy** 

 **template:**

```
<ul>
  <li v-for="img in list">
    <img v-lazy="img.src" >
  </li>
</ul>
```

