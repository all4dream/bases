title: "Java研发复习笔记(五)---算法"
date: 2015-10-07 07:13:00
author: "郑江龙"
description: 算法
categories: interview
tags:
    - Java
    - interview
---
1. 链表与数组。
2. 队列和栈，出栈与入栈。
3. 链表的删除、插入、反向。
4. 字符串操作。
5. Hash表的hash函数，冲突解决方法有哪些。
6. 各种排序：冒泡、选择、插入、希尔、归并、快排、堆排、桶排、基数的原理、平均时间复杂度、最坏时间复杂度、空间复杂度、是否稳定。
7. 快排的partition函数与归并的Merge函数。
8. 对冒泡与快排的改进。
9. 二分查找，与变种二分查找。
10. 二叉树、B+树、AVL树、红黑树、哈夫曼树。
11. 二叉树的前中后续遍历：递归与非递归写法，层序遍历算法。
12. 图的BFS与DFS算法，最小生成树prim算法与最短路径Dijkstra算法。
13. KMP算法。
14. 排列组合问题。
15. 动态规划、贪心算法、分治算法。（一般不会问到）
16. 大数据处理：类似10亿条数据找出最大的1000个数.........等等 

## 红黑树
一颗红黑树满足以下5个红黑性质的二叉搜素数．
1) 每个结点或是红色的，或是黑色的
2) 根结点是黑色的
3) 每个叶结点NIL是黑色的.
4) 如果一个结点是红色的,则它的两个子结点是黑色的
5) 对于每个结点，该结点到其所有后代结点的简单路径上,均包含相同数据的黑色结点.
删除: 
http://blog.csdn.net/v_JULY_v/article/details/610563

排序算法介绍、复杂度、稳定性
快速排序原理
B+树和二叉树查找时间复杂度
如何判断链表是否有环
