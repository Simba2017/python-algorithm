
---
Easy

## 1. 二叉树最大深度

- 来源： leetcode 104

## 2. 二叉树的最小深度

- 来源： leetcode 111

## 3. 翻转二叉树

- 来源： leetcode 226

## 4. 相同的树

- 来源： leetcode 100

## 5. 路径总和

- 来源： leetcode 112

## 6. 左叶子之和

- 来源： leetcode 404

## 7. 二叉树的所有路径

- 来源： leetcode 257


## 8. 路径总和 3

- 来源： leetcode 437

## 9. 二叉搜索树的最近公共祖先

- 来源： leetcode 235


## 10. 将有序数组转化为二叉搜索树

- 来源： leetcode 108
---
Medium

## 1. 二叉树的前序遍历

- 来源： leetcode 144
- 迭代：使用栈来完成,我们先将根节点放入栈中,然后将其弹出,依次将该弹出的节点的右节点,和左节点,**注意顺序,**是右,左,为什么?因为栈是先入后出的,我们要先输出右节点,所以让它先进栈.

## 2. 二叉树的中序遍历

- 来源： leetcode 94

## 3. 二叉树的层序遍历

- 来源： leetcode 102

## 4. 不同的二叉搜索树

- 来源： leetcode 96

- 思路： dp 问题
> - dp[i]:  i个节点组成的二叉树个数
> - dp[i] = dp[i-1] * dp[0] + ... + dp[i-j][j-1] + ... + dp[0][i-1]

## 5. 从前序与中序遍历构造二叉树

- 来源： leetcode 105
- 思路： 需要注意划分的边界

## 6. 二叉搜索树

- 来源： leetcode 98


## 7. 最大 BST 子树

- 来源： leetcode 333

分析：为了获得以某节点为根节点的的搜索二叉子树，我需要以下信息：
  > 1. 左树上搜索二叉子树的大小
  > 2. 右树上搜索二叉子树的大小
  > 3.  左树其搜索二叉子树的头部
  > 4. 右树其搜索二叉子树的头部
  > 5. 左树上的最大值
  > 6. 右树上的最小值

那么，汇总来看，递归需要返回： 
> - 树的搜索二叉子树的大小， 
> - 树的搜索二叉子树的头部， 
> - 树的最大值与最小值。

## 8. 完全二叉树

- 来源： leetcode 958

- 思路： 采用层序遍历的思路做
  > - 当前节点有右节点但是没有左节点 ，则返回 False
  > - 当前节点没有右节点，则后续的所有节点如果不是叶子节点，则返回False


## 9. 平衡二叉树

- 来源： leetcode 110

## 10.  二叉树的直径

- 来源： leetcode 543

## 11. 完全二叉树节点个数

- 来源： leetcode 222

## 12. 从二叉搜索树到更大和树

- 来源： leetcode 1038
- 思路：中序遍历： 右 -> 根 -> 左

## 13. 二叉树最大宽度

- 来源： leetcode 662
- 思路：层序遍历 + 记录首末坐标

## 14. 对称二叉树

- 来源： leetcode 101
- 思路:

## 15. 二叉树的右视图

- 来源： leetcode 199
- 思路：层序遍历，保存每层最后一个节点的值

## 16. 路径总和 2

- 来源： leetcode 113

## 17. 求根到叶子节点数字之和

- 来源： leetcode 129


## 18. 删除二叉搜索树中的节点

- 来源： leetcode 450


## 19. 二叉搜索树中的第k 小的元素

- 来源： leetcode 230


## 20. 二叉树的最近公共祖先

- 来源： leetcode 236

---
Hard

## 1. 二叉树的后序遍历

- 来源： leetcode 145














