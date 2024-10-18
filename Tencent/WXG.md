#### 洗牌算法

大概就是给定一个数组然后让数组上的数字打乱。

```js
function shuffleArray(array) {
    // 创建一个数组的副本，避免修改原始数组
    let arr = array.slice();

    for (let i = arr.length - 1; i > 0; i--) {
        // 随机选择一个小于当前元素索引的数字
        let j = Math.floor(Math.random() * (i + 1));
        // 交换当前元素与随机选择的元素
        [arr[i], arr[j]] = [arr[j], arr[i]];
    }

    return arr;
}
```



#### [寻找重复数](https://leetcode.cn/problems/find-the-duplicate-number/description/)——leetcode原题



#### [路径总和](https://leetcode.cn/problems/path-sum/description/)——leetcode原题





#### [最长递增子序列](https://leetcode.cn/problems/longest-increasing-subsequence/)——leetcode原题



