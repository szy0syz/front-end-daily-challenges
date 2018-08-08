# 099-纯CSS做一个过山车Loader

## 步骤

先定义dom，一个容器装三个小圆点 `.loader>span*3`

```html
<div class="loader">
    <span></span>
    <span></span>
    <span></span>
</div>
```

接着我们把这个容器水平垂直居中显示，我们要居中的是三个小球的容器，那得设置它父容器啦，我看看是谁。哦~~~ `body` 老表

```css

```