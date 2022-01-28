# 简单题目合集



基本上所有的二叉树问题都可以用遍历问题来概括，但是从方法语义上来说，很多问题只是在遍历的过程中做了某些记录，这样的话其遍历并不是其实际的要求，可以说并不是看重遍历的结果，而是这个过程。

## 遍历问题

树是图的一种，因此其遍历的方式是一致的，也就是都可以使用 BFS 和 DFS 来解决。

一般来说，树的 DFS 都是通过递归的形式来解决的，而 BFS 则是使用队列来辅助实现，当然也存在使用迭代 + 栈的形式来完成 DFS，但是难度会高一些。

- [94. 二叉树的中序遍历](../problems/94.binary-tree-inorder-traversal.md)
- [102. 二叉树的层序遍历](../problems/102.binary-tree-level-order-traversal.md)
- [144. 二叉树的前序遍历](../problems/144.binary-tree-preorder-traversal.md)
- [145. 二叉树的后序遍历](../problems/145.binary-tree-postorder-traversal.md)
- [637. 二叉树的层平均值](../problems/637.average-of-levels-in-binary-tree.md)
- [872. 叶子相似的树](../problems/872.leaf-similar-trees.md)
- [LCP 44. 开幕式焰火](../problems/lcp-44.sZ59z6.md)
- [606. 根据二叉树创建字符串](../problems/606.construct-string-from-binary-tree.md)
- [993. 二叉树的堂兄弟节点](../problems/993.cousins-in-binary-tree.md)
- [671. 二叉树中第二小的节点](../problems/671.second-minimum-node-in-a-binary-tree.md)
- [703. 数据流中的第 K 大元素](../problems/703.kth-largest-element-in-a-stream.md)

## 基础问题

一些与普通二叉树相关的基础问题，都是使用递归的思想来解决的，也就是将整个问题不断分化成小问题。

- [100. 相同的树](../problems/100.same-tree.md)
- [101. 对称二叉树](../problems/101.symmetric-tree.md)
- [110. 平衡二叉树](../problems/110.balanced-binary-tree.md)
- [226. 翻转二叉树](../problems/226.invert-binary-tree.md)
- [104. 二叉树的最大深度](../problems/104.maximum-depth-of-binary-tree.md)
- [111. 二叉树的最小深度](../problems/111.minimum-depth-of-binary-tree.md)
- [543. 二叉树的直径](../problems/543.diameter-of-binary-tree.md)
- [563. 二叉树的坡度](../problems/563.binary-tree-tilt.md)
- [108. 将有序数组转换为二叉搜索树](../problems/108.convert-sorted-array-to-binary-search-tree.md)
- [面试题 04.02. 最小高度树](../problems/mst-04-02.minimum-height-tree-lcci.md)
- [面试题 04.04. 检查平衡性](../problems/mst-04-04.check-balance-lcci.md)
- [617. 合并二叉树](../problems/617.merge-two-binary-trees.md)
- [653. 两数之和 IV - 输入 BST](../problems/653.two-sum-iv-input-is-a-bst.md)
- [897. 递增顺序搜索树](../problems/897.increasing-order-search-tree.md)
- [236. 二叉树的最近公共祖先](../problems/236.lowest-common-ancestor-of-a-binary-tree.md)
- [965. 单值二叉树](../problems/965.univalued-binary-tree.md)
- [572. 另一棵树的子树](../problems/572.subtree-of-another-tree.md)

## 路径问题

- [112. 路径总和](../problems/112.path-sum.md)
- [257. 二叉树的所有路径](../problems/257.problemsbinary-tree-paths.md)
- [1022. 从根到叶的二进制数之和](../problems/1022.sum-of-root-to-leaf-binary-numbers.md)
- [404. 左叶子之和](../problems/404.sum-of-left-leaves.md)

## 二叉搜索树

- [235. 二叉搜索树的最近公共祖先](../problems/235.lowest-common-ancestor-of-a-binary-search-tree.md)
- [501. 二叉搜索树中的众数](../problems/501.find-mode-in-binary-search-tree.md)
- [530. 二叉搜索树的最小绝对差](../problems/530.minimum-absolute-difference-in-bst.md)
- [700. 二叉搜索树中的搜索](../problems/700.search-in-a-binary-search-tree.md)
- [938. 二叉搜索树的范围和](../problems/938.range-sum-of-bst.md)
- [783. 二叉搜索树节点最小距离](../problems/783.minimum-distance-between-bst-nodes.md)