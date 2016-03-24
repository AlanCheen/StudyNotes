
# RecyclerView 



记录一下关于RV的知识点





### `scrollToPosition()`与`scrollToPositionWithOffset`的区别


`scrollToPosition` 使得指定的position可见，注意只是可见而已

`scrollToPositionWithOffset(position, 0)`不仅仅是使得指定的position可见，而且还可以指定offset值（pixel），滑动到指定位置，并伴随偏移量，比如offset为0，则可以保证该position会滑动到顶部！可以用它来做联系人列表滑动功能




## 文章

[RecyclerView使用详解系列](http://frank-zhu.github.io/android/2015/02/26/android-recyclerview-part-3/)  
[RecyclerView剖析](http://blog.csdn.net/qq_23012315/article/details/50807224)