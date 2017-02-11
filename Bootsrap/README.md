# Bootstrap

## Container
* two container style in bootstrap
* class="container": for a responsive fixed width container
* class="container-fluid": for a full width container, spanning the entire width of your viewport(类用于 100% 宽度，占据全部视口（viewport）的容器);

## Grid System
* moblie first
* responsive
* scales up to 12 columns as the device or viewport size increases
* If more than 12 columns are placed within a single row, each group of extra columns will, as one unit, wrap onto a new line.

## Media query
```CSS
/* Small devices (tablets, 768px and up) */
@media (min-width: @screen-sm-min) { ... }

/* Medium devices (desktops, 992px and up) */
@media (min-width: @screen-md-min) { ... }

/* Large devices (large desktops, 1200px and up) */
@media (min-width: @screen-lg-min) { ... }
```
## 分割线
* 新加一个div
* 占12column
* 里面有个 hr tag

## 讲图片拉回父容器
* img-responsive