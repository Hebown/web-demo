搞了 benchmark-demo 的导航栏。结构 belike：

```html
<nav class="navbar">
    <div class="nav-left">
        <div class="nav-logo">
            <img src="./revised.png" />
        </div>
        <div class="nav-links">
            <a href="#">Models</a>
            <a href="#">Research</a>
            <a href="#">Science</a>
            <a href="#">About</a>
        </div>
    </div>
</nav>

<!-- 对应的css -->
<style>
    .nav-left { display: flex; align-items: center; width: 100%; height: 100%; }
    .nav-left img {  height: 100%; object-fit: cover; }
    .nav-logo { font-size: 1.8rem; font-weight: 700; letter-spacing: 1px; margin-right: 30px; height: 100%; }
    .nav-links { display: flex; justify-content: center;}
</style>
<!-- 只要子容器的height写成100%，，就会以父容器的高度来展示->
```



