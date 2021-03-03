# CSS面经

## 1.line-height设置为1.1与110%的区别？
line-height三种表示方法（带单位，纯数字，百分比）
```css
p {line-height: 1.5em;}
p {line-height: 1.5;}
p {line-height: 150%;}
```
答：**三者只是在给父元素使用行高，子元素继承的方式有区别**，带单位的转换成px继承，无单位的作倍数继承

带单位：px(不用计算)，em则会使元素以其父元素font-size值参考来计算自己的行高

纯数字：把比例传递给后代，例如父级行高为1.5，子元素字体为18px，则子元素行高为1.5*18=27px

百分比：将计算后的值传给后代

## 2.一个div块，设置其为两个效果，一个为渐隐效果，一个为点击空白处显示和隐藏。



## 3.css盒子模型，从外到内的属性

<img src="C:\Users\95191\AppData\Roaming\Typora\typora-user-images\image-20210302213214023.png" alt="image-20210302213214023" style="zoom:50%;" />

```css
box-sizing: content-box|border-box|inherit;
```

<img src="C:\Users\95191\AppData\Roaming\Typora\typora-user-images\image-20210302213605284.png" alt="image-20210302213605284" style="zoom: 67%;" />

## 4.css选择器优先级



## 5.

