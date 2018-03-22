# threephasesbottomsheet
一个底部的表格样本，类似于谷歌地图如何对待它。
例如动画：

！【在这里输入图像描述]（https://raw.githubusercontent.com/androiddeveloperlb/threephasesbottomsheet/master/device-2016-01-16-175728.gif）

这主要是基于这2个存储库：

- https://github.com/flipboard/bottomsheet
- https://github.com/chrisbanes/cheesesquare

而被问及对计算器在这里：

http://stackoverflow.com/q/34160423/878126

有可能使用这个库代替了bottomsheet回购：

https://github.com/umano/androidslidinguppanel

已知问题：
——

第一种方法，使用appbarlayout，coordinatorlayout，等：

-测试版本6，4.2和4.4。不确定其他人。
-不处理良好的方向变化。通过重新显示底部的表来处理样品，但是它不能恢复它的状态。
-罕见的问题，能够滚动底部的床单的内容，而它仍然崩溃（在底部）。不确定是否还存在。
-会有奇怪的问题（如全屏显示）的情况下，键盘显示在偷看。这是在示例中处理的，只是当键盘出现时隐藏底部的表。
-不能处理的情况下，在其从国家底纸更大，比它在膨胀状态时。
当你按下按钮去从一个滚动扩底表状态，对PEEK的状态，它有一些奇怪的问题。需要处理这个问题，或者让它与众不同。在这个示例中，我选择了删除这个案例的底表。

第二方法，仅仅使用一nestedscrollview：

-当它处于扩展模式时，不会对底部页进行滚动。不是问题，只是缺少的特性。
按下返回按钮时会导致奇怪的光泽expaneded底部的UI问题。
-可能还有其他问题。

