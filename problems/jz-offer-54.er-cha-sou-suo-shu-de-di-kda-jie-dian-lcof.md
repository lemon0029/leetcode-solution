[剑指 Offer 54. 二叉搜索树的第k大节点](https://leetcode-cn.com/problems/er-cha-sou-suo-shu-de-di-kda-jie-dian-lcof/)

```java
int t = 0;
int k = 0;

public int kthLargest(TreeNode root, int k) {
    this.k = k;
    dfs(root);
    return t;
}

private void dfs(TreeNode node) {
    if (node != null && k > 0) {
        dfs(node.right);
        if (k > 0) {
            t = node.val;
            k--;
        }
        dfs(node.left);
    }
}
```

