---
layout: post
title: 深度优先搜索
---
### LeetCode Problems about DFS  

Q.39
第一次碰到DFS的题目，是要找到一个数组中sum为target，且要求不出现重复的组合  
hint:   
1. 排序数组，然后每次查找时候，从前一个输入位置处开始，这样就能保证，不出现重复组合  
2. 使用回溯的DFS，当触到根部，或者满足相应条件时候则返回  

Q.40  
同39题相同，也是DFS，但是要注意  
1. 不能出现重复组合  
2. 数组中的数不是unique的，所以设置选择条件时候，要跳过那些相同的数，避免形成重复组合

### Dynamic programming  

Q.300  
最长子序列的题目  
关键在于分析清楚问题可以又什么样的子问题构成，以及和子问题相关的状态  
