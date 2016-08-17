当内联元素span添加浮动(float)或者是绝对定位(absolute)


正常情况下span只会根据内容将元素撑开，这时给span宽高是无效的，
当添加了float或者是absolute之后，再给span一个宽高，会发现宽高生效了，变成了类似于块级元素的一个元素，
可以简单的理解成inline-block。
