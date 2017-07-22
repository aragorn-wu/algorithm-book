```

```

* 一个无环的有向图称为无环图（Directed Acyclic Graph），简称DAG图。 
* 在一个表示工程的有向图中，用顶点表示活动，用弧表示活动之间的优先关系，这样的有向图为顶点表示活动的网，我们称之为AOV网（Active On Vertex Network）。 
* 拓扑序列：设G=\(V,E\)是一个具有n个顶点的有向图，V中的顶点序列V1,V2,……,Vn满足若从顶点Vi到Vj有一条路径，则在顶点序列中顶点Vi必在顶点Vj之前。则我们称这样的顶点序列为一个拓扑序列。 
* 拓扑排序：所谓的拓扑排序，其实就是对一个有向图构造拓扑序列的过程。

* 计算机专业的学生必须完成一系列规定的专业基础课和专业课才能毕业，这个过程就可以被看成是一个大的工程，而活动就是学习每一门课程。我们不妨把这些课程的名称与相应的代号列于表

![](/assets/14.jpg)

![](/assets/25.jpg)

* **拓扑序列（其中一种）：1,13,4,8,14,15,5,2,3,10,11,12,7,6,9**

* 实现方式

  * Kahn算法

  代码如下：

  [https://github.com/aragorn-wu/algorithm/blob/master/src/main/java/com/git/algorithm/graph/TopologicalOrder.java](#)

  * 深度优先算法





