#css

## Grid base design
## Responsive design
* not a fixed pixel for our product
* response to different devices
* not fixed pixel but percentage
* most of sites use 12 colmuns

## display
* list-item：指定对象为列表项目。
* table-cell：指定对象作为表格单元格。类同于html标签<td>（CSS2）
* flex：将对象作为弹性伸缩盒显示。（伸缩盒最新版本）（CSS3）

## flex-wrap
* nowrap | wrap | wrap-reverse
```CSS
nowrap：
flex容器为单行。该情况下flex子项可能会溢出容器
wrap：
flex容器为多行。该情况下flex子项溢出的部分会被放置到新行，子项内部会发生断行
wrap-reverse：
反转 wrap 排列。
```
## Nagative space
* the space doesn't content anything.
*

## overflow attribute
* solve the problem with content overflow
```CSS
overflow: auto;
```


## Media Queries
* start with @: @media
* **only** arrtibute can help to older browsers
```CSS
@media only screen and (max-width: 300px) {
    p {
        background: blue;
    }
}

screen: this media is for all type of screen.
max-width: 300px: 指定了media只有在300px以下才会被查询.
```

## CSS Resetting/ CSS normalize
* to help the css perform the same thing in the different browser: 解决兼容问题
* link to the **normalize.css**

