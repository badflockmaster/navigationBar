# 总结编码过程中的问题与要点
## 伪类
主要有两个伪类，before和after。其次就是checked伪类。checked是radio和checkbox的一个点击状态。当被点击是就会触发这个伪类。同时联合label标签。可以在任意地点实现点击。

## 选择器
兄弟选择器：+和~。p+a表示紧靠在p标签的a标签。而p~a表示在靠在p标签之后的a标签。之前可以有其他的标签。

## css3中的transition
第一个参数是对象，第二个参数是时间。主要是第三个参数。可以使css3中提前定义好的，例如ease，linear，ease-in，ease-out。但是最重要的是自定义
cubic-bezier函数，有四个参数，可以自定义速度曲线。

同时注意transition-delay，延迟执行的时间。



