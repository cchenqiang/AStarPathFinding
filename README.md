# AStarPathFinding 基于网格的A*算法，路径基于弗洛伊德平滑优化
## 优化：
### 0 对节点预处理，关联到相邻的节点。
### 1 去掉关闭列表。
### 2 开启列表使用二叉堆。
### 3 忽略G值的更新。
### 4 如果终点不可达，对终点进行广度优先便利，找出离终点最近的位置（暂未实现）。
