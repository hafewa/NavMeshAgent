# NavMeshAgent
(不完美)解决群体寻路时物体之间拥挤、碰撞问题
说不完美，是因为会出现些问题

1.有个别物体没到达目标点附近就停止了

2.当两次目标点距离较近时，物体可能部分会重叠

实现方法：

使用Nav Mesh Obstacle

在寻路过程中，关闭障碍组件，

寻路结束，关闭寻路组件，打开障碍组件。

更详细内容 请查看站点：http://www.u3d8.com/?p=1093
![image](http://www.u3d8.com/wp-content/uploads/2017/04/PathFinding.gif)
