## MyStreak
This is a Trailing Sample,it is similar to the fruit knife cut light effect ,weapon waving effect,airplane tail flame.
When the Fingers move on the screen ,the streak is appear.
刀光，尾焰，拖尾效果的开发。 实现原理链接 https://blog.csdn.net/ModestBean/article/details/79245439
## Running Result
![这里写图片描述](./result/result.gif)
## Algorithm 
![这里写图片描述](./result/yuan1.png)

The yellow section is the streak.	A,B,C,D are the screen points ,by these points ,you can calculate the streak points.

I use a list to store these points ,the length of list is fixed length . one point have a parameter--lifecycle.
