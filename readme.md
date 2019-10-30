## 用CSS制作一个彩虹

1. 先做8个div依次是红橙黄绿青蓝紫，第八个做成白色，因为背景是白色的。
2. 用 border-radius: 50% 让每个正方形的div变成半圆形。
3. 彩虹的样子大概出来后，把最外层的.rainbow的div宽度设置成里面div的一半，这样内容溢出，我们利用overflow：hidden，使溢出部门隐藏。
4. 因为会出现margin合并，我们在.rainbow里面的每个div加上overflow：hidden，消除margin合并。