[LCP 44. 开幕式焰火](https://leetcode-cn.com/problems/sZ59z6/)

```java
Set<Integer> set = new HashSet<>();

public int numColor(TreeNode root) {
    dfs(root);
    return set.size();
}

private void dfs(TreeNode node) {
    if (node != null) {
        set.add(node.val);
        dfs(node.left);
        dfs(node.right);
    }
}
```

