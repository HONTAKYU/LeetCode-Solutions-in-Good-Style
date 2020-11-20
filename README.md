# LeetCode-Solutions-in-Good-Style

大家好，这里是一个算法学习的小教程。可以帮助新手朋友们入门「算法与数据结构」。

+ 特别感谢 [@AbbyDeng](https://github.com/AbbyDeng) 同学的更名建议。

+ 本项目是我在学习《算法与数据结构》的时候，在 [LeetCode（力扣）](https://leetcode-cn.com/) 上做的练习 ；刷题以 Java 语言为主，Python 和 C++ 语言实现为辅；
+ 本项目可以认为是一个《算法与数据结构》的简易教程，适用于零基础和转行的同学；
+ 适用于准备算法面试，不适合于准备算法竞赛；
+ 所有的代码都通过  [LeetCode（力扣）](https://leetcode-cn.com/) 在线测评系统检测；
+ 建议您安装 [Octotree 插件](https://www.octotree.io/?utm_source=lite&utm_medium=extension)，以获得最佳的阅读体验。

![Octotree 插件](http://liweiwei1419.gitee.io/visualgo/github/octotree.png)

可以叫我 weiwei，在我力所能及且时间允许的情况下，我会尽可能回答我知道的问题。如果有不能及时回复的问题，可能是因为我没有看到站内通知，可以发邮件给我 liweiwei1419@gmail.com 。

我的个人网站和算法学习笔记。

+ 个人主页：https://liweiwei1419.gitee.io/leetcode-algo/
+ 语雀笔记：https://www.yuque.com/liweiwei1419/algo
+ CSDN 博客：https://blog.csdn.net/lw_power
+ 微信公众号：（佛系运营，可能没有多少干货）。

![](https://liweiwei1419.gitee.io/visualgo/author/qrcode_for_gh_246ffacb3679_258.jpg)

讲解如有错误，欢迎指正！

我的 LeetBook 是收费教程，投入精力与平时写题解是一样的，只不过 LeetBook 在制作图表上会更细致一点，并且有「力扣」的工作人员和高手参与制作和审核。不排除平时写的题解知识点比 LeetBook 还要多的情况。

# 微信群与 QQ 群

以下原来是写在「力扣」主页里的，由于要配合「力扣」的工作，因此写在了这里。

如果需要一起刷题的朋友，可以加入微信群和 QQ 群。

| 微信群                                                       | QQ 群           |
| ------------------------------------------------------------ | --------------- |
| 每日一题打卡活动和加入微信群可以点 [这里](https://ojeveryday.com/#/check) 。 | 群号：812791932 |

感谢负雪明烛和二哥组织建群。


# 「力扣」分类以及题解目录（按照 LeetBook 的章节编排）

**说明**：题目分类与我的 LeetBook 章节对应，LeetBook 的课程标题、例题、练习都是公开的。

## 第 1 章 时间复杂度

这部分内容介绍了 时间复杂度 这个概念，可以收看 [视频讲解](https://leetcode-cn.com/leetbook/read/learning-algorithms-with-leetcode/xs3ij1/) ，完全免费。 这一章节没有练习。

## 第 2 章 二分查找

+ 可以我的  LeetBook 收看二分查找的知识点 [讲解](https://leetcode-cn.com/leetbook/read/learning-algorithms-with-leetcode/xsq0b7/)，免费；
+ 知识点讲解：[写对二分查找不能靠模板，需要理解加练习 （附练习题，持续更新）](https://leetcode-cn.com/problems/search-insert-position/solution/te-bie-hao-yong-de-er-fen-cha-fa-fa-mo-ban-python-/)、[视频讲解](https://www.bilibili.com/video/av83911694?p=1)。

### 题型一：二分求下标

+ 重点问题

| 题号 | 链接                                                         | 题解                                                         |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 704  | [二分查找](https://leetcode-cn.com/problems/binary-search/)（简单） |                                                              |
| 35   | [搜索插入位置](https://leetcode-cn.com/problems/search-insert-position/)（简单） | [视频讲解](https://www.bilibili.com/video/av83911694?p=2)、[文字题解](https://leetcode-cn.com/problems/search-insert-position/solution/te-bie-hao-yong-de-er-fen-cha-fa-fa-mo-ban-python-/) |
| 34   | [在排序数组中查找元素的第一个和最后一个位置](https://leetcode-cn.com/problems/find-first-and-last-position-of-element-in-sorted-array/)（简单） | [视频讲解](https://www.bilibili.com/video/av83911694?p=3)、[文字题解](https://leetcode-cn.com/problems/find-first-and-last-position-of-element-in-sorted-array/solution/si-lu-hen-jian-dan-xi-jie-fei-mo-gui-de-er-fen-cha/) |
| 1095 | [ 山脉数组中查找目标值](https://leetcode-cn.com/problems/find-in-mountain-array/)（中等） | [视频讲解](https://www.bilibili.com/video/BV1GK4115778)、[文字题解](https://leetcode-cn.com/problems/find-in-mountain-array/solution/shi-yong-chao-hao-yong-de-er-fen-fa-mo-ban-python-/) |
| 4    | [寻找两个有序数组的中位数](https://leetcode-cn.com/problems/median-of-two-sorted-arrays/)（困难） | [视频讲解](https://www.bilibili.com/video/BV1Xv411z76J)、[文字题解](https://leetcode-cn.com/problems/median-of-two-sorted-arrays/solution/he-bing-yi-hou-zhao-gui-bing-guo-cheng-zhong-zhao-/) |


**说明**：

+ 第 34 题：二分查找找边界问题、[CSDN](https://blog.csdn.net/lw_power/article/details/104066739)、[庸才顾子汐：关于 while (left <= right) 写法返回值的详细讨论](https://leetcode-cn.com/problems/find-first-and-last-position-of-element-in-sorted-array/solution/da-jia-bu-yao-kan-labuladong-de-jie-fa-fei-chang-2/)；
+ 第 4 题：二分查找里最难的问题，重点在于理解：① 为什么是在短数组里找边界；② 边界条件的判断。

---

**练习**：


| 题号 | 链接                                                         | 题解                                                         |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 33   | [搜索旋转排序数组](https://leetcode-cn.com/problems/search-in-rotated-sorted-array/)（中等） | [文字题解](https://leetcode-cn.com/problems/search-in-rotated-sorted-array/solution/er-fen-fa-python-dai-ma-java-dai-ma-by-liweiwei141/) |
| 81   | [搜索旋转排序数组 II](https://leetcode-cn.com/problems/search-in-rotated-sorted-array-ii/)（中等） | [文字题解](https://leetcode-cn.com/problems/search-in-rotated-sorted-array-ii/solution/er-fen-cha-zhao-by-liweiwei1419/) |
| 153  | [153. 寻找旋转排序数组中的最小值](https://leetcode-cn.com/problems/find-minimum-in-rotated-sorted-array/)（中等） | [文字题解](https://leetcode-cn.com/problems/find-minimum-in-rotated-sorted-array/solution/er-fen-fa-fen-zhi-fa-python-dai-ma-java-dai-ma-by-/) |
| 154  | [154. 寻找旋转排序数组中的最小值 II](https://leetcode-cn.com/problems/find-minimum-in-rotated-sorted-array-ii/)（困难） | [文字题解](https://leetcode-cn.com/problems/find-minimum-in-rotated-sorted-array-ii/solution/er-fen-fa-fen-zhi-fa-python-dai-ma-by-liweiwei1419/) |
| 275  | [ H指数 II](https://leetcode-cn.com/problems/h-index-ii/)（中等） | [文字题解](https://leetcode-cn.com/problems/h-index-ii/solution/jian-er-zhi-zhi-er-fen-cha-zhao-by-liweiwei1419-2/) |
| 436  | [寻找右区间](https://leetcode-cn.com/problems/find-right-interval/)（中等） | [文字题解](https://leetcode-cn.com/problems/find-right-interval/solution/er-fen-cha-zhao-hong-hei-shu-by-liweiwei1419/) |
| 1237 | [找出给定方程的正整数解](https://leetcode-cn.com/problems/find-positive-integer-solution-for-a-given-equation/)（中等） |                                                              |
| 1300 | [转变数组后最接近目标值的数组和](https://leetcode-cn.com/problems/sum-of-mutated-array-closest-to-target/)（中等） | [文字题解](https://leetcode-cn.com/problems/sum-of-mutated-array-closest-to-target/solution/er-fen-cha-zhao-by-liweiwei1419-2/) |

### 题型二：二分确定一个有范围的整数（二分答案）

**算法思想**：减而治之。如果题目要我们找一个整数，这个整数有确定的范围，可以通过二分查找逐渐缩小范围，最后逼近到一个数。

| 题号 | 链接                                                         | 题解                                                         |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 69   | [x 的平方根](https://leetcode-cn.com/problems/sqrtx/)（简单） | [文字题解](https://leetcode-cn.com/problems/sqrtx/solution/er-fen-cha-zhao-niu-dun-fa-python-dai-ma-by-liweiw/) |
| 287  | [寻找重复数](https://leetcode-cn.com/problems/find-the-duplicate-number/)（中等） | [文字题解](https://leetcode-cn.com/problems/find-the-duplicate-number/solution/er-fen-fa-si-lu-ji-dai-ma-python-by-liweiwei1419/) |
| 374  | [猜数字大小](https://leetcode-cn.com/problems/guess-number-higher-or-lower/)（简单） | [文字题解](https://leetcode-cn.com/problems/guess-number-higher-or-lower/solution/shi-fen-hao-yong-de-er-fen-cha-zhao-fa-mo-ban-pyth/) |
| 1283 | [使结果不超过阈值的最小除数](https://leetcode-cn.com/problems/find-the-smallest-divisor-given-a-threshold/)（中等） | [文字题解](https://leetcode-cn.com/problems/find-the-smallest-divisor-given-a-threshold/solution/er-fen-cha-zhao-ding-wei-chu-shu-by-liweiwei1419/) |
| 1292 | [元素和小于等于阈值的正方形的最大边长](https://leetcode-cn.com/problems/maximum-side-length-of-a-square-with-sum-less-than-or-equal-to-threshold/)（中等） |                                                              |

### 题型三：复杂的判别函数（最大值极小化问题）

**说明**：这一类问题本质上还是「题型二」（二分答案），但是初学的时候会觉得有一些绕。这一类问题的问法都差不多，**关键字是「连续」、「正整数」**，请大家注意捕捉题目中这样的关键信息。

+ [二分查找之「最大值极小化」相关问题及解题步骤](https://juejin.im/post/6862249637161091085)
+ [二分查找之「最大值极小化」例题选讲](https://juejin.im/post/6864407058662457358/)

| 题号   | 链接                                                         | 题解                                                         |
| ------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 875    | [爱吃香蕉的珂珂](https://leetcode-cn.com/problems/koko-eating-bananas/)（中等） | [文字题解](https://leetcode-cn.com/problems/koko-eating-bananas/solution/er-fen-cha-zhao-ding-wei-su-du-by-liweiwei1419/) |
| 410    | [分割数组的最大值](https://leetcode-cn.com/problems/split-array-largest-sum/)（困难） | [文字题解](https://leetcode-cn.com/problems/split-array-largest-sum/solution/er-fen-cha-zhao-by-liweiwei1419-4/) |
| LCP 12 | [小张刷题计划](https://leetcode-cn.com/problems/xiao-zhang-shua-ti-ji-hua/)（中等） |                                                              |
| 1011   | [在 D 天内送达包裹的能力](https://leetcode-cn.com/problems/capacity-to-ship-packages-within-d-days)（中等） |                                                              |
| 1482   | [制作 m 束花所需的最少天数](https://leetcode-cn.com/problems/minimum-number-of-days-to-make-m-bouquets/)（中等） |                                                              |
| 1552   | [两球之间的磁力](https://leetcode-cn.com/problems/magnetic-force-between-two-balls/)（中等） |                                                              |

## 第 3 章 基础排序算法

这一部分包含了四种基础排序算法：选择排序、插入排序、希尔排序、冒泡排序。

「力扣」第 912 题：[排序数组](https://leetcode-cn.com/problems/sort-an-array/) 的 [题解](https://leetcode-cn.com/problems/sort-an-array/solution/fu-xi-ji-chu-pai-xu-suan-fa-java-by-liweiwei1419/)：总结了排序问题的一些要点和学习资料，可以从排序问题开始学习算法。

数组的问题可以作为算法「新手场」，因为这些问题只需要掌握编程语言的基础知识就可以完成。以下问题都很容易想到解决方案，即使没有学习过相关的数据结构和算法知识。

#### 知识点：循环不变量

+ 循环不变量用于证明算法的有效性，也是编码正确的理论依据；
+ 循环不变量定义帮助分清先加还是先赋值，还有一些边界条件。定义清楚循环不变量以后，代码的编写就会很轻松；
+ 建议把「循环不变量」作为注释写在代码里，以方便自己调试和他人阅读。





| 题号 | 链接                                                         | 题解                                                         |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 912  | [排序数组](https://leetcode-cn.com/problems/sort-an-array)（中等） | [文字题解](https://leetcode-cn.com/problems/sort-an-array/solution/fu-xi-ji-chu-pai-xu-suan-fa-java-by-liweiwei1419/) |
| 26   | [删除排序数组中的重复项](https://leetcode-cn.com/problems/remove-duplicates-from-sorted-array)（简单） |                                                              |
| 27   | [移除元素](https://leetcode-cn.com/problems/remove-element/)（简单） |                                                              |
| 283  | [移动零](https://leetcode-cn.com/problems/move-zeroes)（简单） | [文字题解](https://leetcode-cn.com/problems/move-zeroes/solution/zun-shou-xun-huan-bu-bian-shi-java-by-liweiwei1419/) |
|      |                                                              |                                                              |

## 第 4 章 高级排序算法（重要）

这一部分需要重点掌握三种高级排序算法：归并排序、快速排序、堆排序。

| 题号     | 链接                                                         | 题解                                                         |
| -------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 88       | [合并两个有序数组](https://leetcode-cn.com/problems/merge-sorted-array/)（简单） | [从后向前归并](https://leetcode-cn.com/problems/merge-sorted-array/solution/si-xiang-mei-you-chuang-xin-de-di-fang-zhu-yao-ti-/) |
| 《剑》51 | [数组中的逆序对](https://leetcode-cn.com/problems/shu-zu-zhong-de-ni-xu-dui-lcof/)（困难） | [视频讲解](https://leetcode-cn.com/problems/shu-zu-zhong-de-ni-xu-dui-lcof/solution/shu-zu-zhong-de-ni-xu-dui-by-leetcode-solution/)、[文字题解](https://leetcode-cn.com/problems/shu-zu-zhong-de-ni-xu-dui-lcof/solution/bao-li-jie-fa-fen-zhi-si-xiang-shu-zhuang-shu-zu-b/) |
| 75       | [颜色分类](https://leetcode-cn.com/problems/sort-colors/)（中等） | [文字题解](https://leetcode-cn.com/problems/sort-colors/solution/kuai-su-pai-xu-partition-guo-cheng-she-ji-xun-huan/) |
| 215      | [数组中的第K个最大元素](https://leetcode-cn.com/problems/kth-largest-element-in-an-array/)（中等） | [文字题解](https://leetcode-cn.com/problems/kth-largest-element-in-an-array/solution/partitionfen-er-zhi-zhi-you-xian-dui-lie-java-dai-/) |
| 451      | [根据字符出现频率排序](https://leetcode-cn.com/problems/sort-characters-by-frequency)（中等） |                                                              |

**说明**：

+ 第 88 题：归并排序，注意这里从后向前归并；
+ 《剑指 Offer》第 51 题：归并排序、树状数组（选学）；
+ 第 75 题：著名的「荷兰国旗」问题、快排；
+ 第 215 题：快排、优先队列；
+ 第 451 题：快排、优先队列。

## 第 5 章 非比较排序（选学）

这一部分包含了三种非比较排序排序：计数排序、基数排序、桶排序。解决这些问题需要知道 **原地哈希** 这个概念。

| 题号    | 链接                                                         | 题解                                                         |
| ------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 41      | [缺失的第一个正数](https://leetcode-cn.com/problems/first-missing-positive/)（困难） | [视频讲解](https://www.bilibili.com/video/BV167411N7vd)、[文字题解](https://leetcode-cn.com/problems/first-missing-positive/solution/tong-pai-xu-python-dai-ma-by-liweiwei1419/) |
| 《剑》3 | [剑指 Offer 03. 数组中重复的数字](https://leetcode-cn.com/problems/shu-zu-zhong-zhong-fu-de-shu-zi-lcof/)（中等） |                                                              |
| 448     | [找到所有数组中消失的数字](https://leetcode-cn.com/problems/find-all-numbers-disappeared-in-an-array/)（简单） |                                                              |
| 442     | [数组中重复的数据](https://leetcode-cn.com/problems/find-all-duplicates-in-an-array/)（中等） |                                                              |

## 第 6 章 滑动窗口与双指针

### 一、滑动窗口

+ 思想简单，但是代码比较难一次写对；
+ 滑动窗口的思想是：**先向右移动右指针、再向右移动左指针**，这样左右指针交替执行（ **不回头** ），可以完成一些问题；
+ 滑动窗口是 **暴力解法的优化** ，如何 **根据目标函数把暴力解法的一系列解排除掉，是使用滑动窗口的前提** ，一定要分析清楚；
+ 下面提供的是一种参考的写法，请**不要照搬**，应该 **先理解滑动窗口的思想（暴力解法的剪枝）** ，然后多加练习，掌握编写代码的技巧和细节。

滑动窗口的参考写法（不是模板，**请不要原样照搬**，仅供参考，理解算法设计思想是更重要的）：

```java
public class Solution {

    public String minWindow(String s, String t) {
        // 起始的时候，都位于 0，同方向移动
        int left = 0;
        int right = 0;
        while (right < sLen) {
            if ( 在右移的过程中检测是否满足条件 ) {
                // 对状态做修改，好让程序在后面检测到满足条件
            }
            // 右边界右移 1 格
            right++;
            while ( 满足条件 ) {
                // 走到这里是满足条件的，左边界逐渐逐渐左移，可以取最小值
                if ( 在左移的过程中检测是否不满足条件 ) {
                    // 对状态做修改，好让程序在后面检测到不满足条件
                }
                // 左边界左移 1 格
                left++;
            }
            // 走到这里是不满足条件的，右边界逐渐右移，可以取最大值
        }
        return 需要的结果变量;
    }
}
```



**友情提示**：第 3 题和第 76 题是必须要会做的基本问题。上面的问题理解透彻了，下面的问题就可以比较轻松地做出来。

**重点问题**：

| 题号 | 链接                                                         | 题解                                                         |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 3    | [无重复字符的最长子串](https://leetcode-cn.com/problems/longest-substring-without-repeating-characters)（中等） | [文字题解](https://leetcode-cn.com/problems/longest-substring-without-repeating-characters/solution/ge-ban-fa-hua-dong-chuang-kou-dong-tai-gui-hua-pyt/) |
| 76   | [最小覆盖子串](https://leetcode-cn.com/problems/minimum-window-substring)（困难） | [视频讲解]()                                                 |
| 209  | [长度最小的子数组](https://leetcode-cn.com/problems/minimum-size-subarray-sum)（中等） |                                                              |
| 424  | [替换后的最长重复字符](https://leetcode-cn.com/problems/longest-repeating-character-replacement/)（中等） |                                                              |
| 1493 | [ 删掉一个元素以后全为 1 的最长子数组](https://leetcode-cn.com/problems/longest-subarray-of-1s-after-deleting-one-element/)（中等） |                                                              |

**说明**：

+ 第 3 题：先暴力解法，再优化；
+ 第 76 题：滑动窗口的典型问题，重点分析为什么可以使用滑动窗口。字符频数数组可以使用哈希表，也可以直接使用数组；使用 **距离** 的定义加速计算；
+ 第 424 题：重点分析为什么可以使用滑动窗口。设计变量 `maxCount`  的含义：在滑动的过程中，出现的字符频数最多的个数；收集结果的判断语句（`while (right - left > maxCount + k)`）比较难想到。第 424 题同类问题：「力扣」第 1493 题：[删掉一个元素以后全为 1 的最长子数组](https://leetcode-cn.com/problems/longest-subarray-of-1s-after-deleting-one-element/) 。

```Java []
public class Solution {

    // 第 424 题代码：滑动窗口（暴力解法的优化）

    public int longestSubarray(int[] nums) {
        int len = nums.length;
        int left = 0;
        int right = 0;

        // 连续的 1 的个数
        int ones = 0;

        // 删除一个元素以后全为 1 的最长的子串的长度
        int maxCount = 0;
        int res = 0;

        while (right < len) {
            if (nums[right] == 1) {
                ones++;
            }
            maxCount = Math.max(maxCount, ones);
            right++;
            // maxCount + 1 里的 1 就表示删除的那个元素
            while (right - left > maxCount + 1) {
                if (nums[left] == 1) {
                    ones--;
                }
                left++;
            }
            res = Math.max(res, right - left);
        }
        // 注意：这里返回 res 要减 1
        return res - 1;
    }
}
```

**练习**：

| 题号 | 题目                                                         | 题解 | 知识点 |
| ---- | ------------------------------------------------------------ | ---- | ------ |
| 438  | [找到字符串中所有字母异位词](https://leetcode-cn.com/problems/find-all-anagrams-in-a-string/)（中等） |      |        |
| 567  | [字符串的排列](https://leetcode-cn.com/problems/permutation-in-string)（中等） |      |        |
| 643  | [子数组最大平均数 I](https://leetcode-cn.com/problems/maximum-average-subarray-i)（简单） |      |        |
| 978  | [最长湍流子数组](https://leetcode-cn.com/problems/longest-turbulent-subarray)（中等） |      |        |
| 992  | [K 个不同整数的子数组](https://leetcode-cn.com/problems/subarrays-with-k-different-integers)（困难） |      |        |

**说明**：

+ 第 209 题：题目中给出的关键信息：**数组里的元素全部是正整数**。一共有以下 3 种方法。

  + 方法一：暴力解法

  + 方法二：滑动窗口（分析可以使用滑动窗口的原因）

  + 方法三：构造前缀和数组，然后使用二分查找

+ 第 438 题：同第 76 题；
+ 第 567 题：同第 76 题，收集符合条件的语句不一样而已。

### 二、双指针

「双指针」问题其实也是朴素算法的优化，一下子排序掉很多不符合题意的解，「滑动窗口」技巧也是这样的。依然是分析为什么可以使用双指针是更重要的。

二分查找算法应用于查找下标也可以认为是双指针的解法。

| 题号 | 链接                                                         | 题解                                                         | 知识点 |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------ |
| 11   | [盛最多水的容器](https://leetcode-cn.com/problems/container-with-most-water)（中等） |                                                              |        |
| 15   | [三数之和](https://leetcode-cn.com/problems/3sum)（中等）    |                                                              |        |
| 16   | [最接近的三数之和](https://leetcode-cn.com/problems/3sum-closest/)（中等） | [文字题解](https://leetcode-cn.com/problems/3sum-closest/solution/shuang-zhi-zhen-dui-zhuang-python-dai-ma-java-dai-/) |        |
| 42   | [接雨水](https://leetcode-cn.com/problems/trapping-rain-water/)（困难） | [文字题解](https://leetcode-cn.com/problems/trapping-rain-water/solution/bao-li-jie-fa-yi-kong-jian-huan-shi-jian-zhi-zhen-/) |        |
| 167  | [两数之和 II - 输入有序数组](https://leetcode-cn.com/problems/two-sum-ii-input-array-is-sorted/)（简单） | [文字题解](https://leetcode-cn.com/problems/two-sum-ii-input-array-is-sorted/solution/shuang-zhi-zhen-dui-zhuang-er-fen-fa-python-dai-ma/) |        |
| 925  | [长按键入](https://leetcode-cn.com/problems/long-pressed-name/)（简单） |                                                              |        |

## 第 7 章 链表

（内容待添加。）

## 第 8 章 栈与队列

### 一、栈

#### 题型一：基本的使用栈解决的问题

下面的问题非常基础，一定需要掌握：

| 题号 | 链接                                                         | 题解                                                         |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 20   | [有效的括号](https://leetcode-cn.com/problems/valid-parentheses)（简单） |                                                              |
| 71   | [简化路径](https://leetcode-cn.com/problems/simplify-path)（中等） |                                                              |
| 155  | [最小栈](https://leetcode-cn.com/problems/min-stack)（简单） | [文字题解](https://leetcode-cn.com/problems/min-stack/solution/shi-yong-fu-zhu-zhan-tong-bu-he-bu-tong-bu-python-/) |
| 225  | [用队列实现栈](https://leetcode-cn.com/problems/implement-stack-using-queues/)（简单） | [文字题解](https://leetcode-cn.com/problems/implement-stack-using-queues/solution/peek-he-pop-shi-yi-ci-jiang-dui-shou-yuan-su-chu-d/) |
| 232  | [用栈实现队列](https://leetcode-cn.com/problems/implement-queue-using-stacks)（简单） | [文字题解](https://leetcode-cn.com/problems/implement-queue-using-stacks/solution/shi-yong-liang-ge-zhan-yi-ge-zhuan-men-ru-dui-yi-g/) |
| 946  | [946. 验证栈序列](https://leetcode-cn.com/problems/validate-stack-sequences)（中等） |                                                              |


#### 练习

| 题号 | 链接                                                         | 题解                                                         |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 284  | [顶端迭代器](https://leetcode-cn.com/problems/peeking-iterator)（中等） |                                                              |
| 341  | [扁平化嵌套列表迭代器](https://leetcode-cn.com/problems/flatten-nested-list-iterator)（中等） |                                                              |
| 946  | [验证栈序列](https://leetcode-cn.com/problems/validate-stack-sequences)（中等） |                                                              |
| 1111 | [有效括号的嵌套深度](https://leetcode-cn.com/problems/maximum-nesting-depth-of-two-valid-parentheses-strings/)（中等） | [文字题解](https://leetcode-cn.com/problems/maximum-nesting-depth-of-two-valid-parentheses-strings/solution/qian-tao-shen-du-wan-cheng-gua-hao-pi-pei-wen-ti-s/) |

#### 题型二：单调栈

单调栈就是普通的栈，在使用的过程中恰好符合了「后进先出」，栈内元素单调的特点。「单调栈」和「单调队列」的问题通常来说很特殊，掌握例题和一些练习就可以了。

经验：单调栈中一般存下标。

| 题号 | 链接                                                         | 题解                                                         |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 84   | [柱状图中最大的矩形](https://leetcode-cn.com/problems/largest-rectangle-in-histogram/)（困难） | [视频题解](https://leetcode-cn.com/problems/largest-rectangle-in-histogram/solution/zhu-zhuang-tu-zhong-zui-da-de-ju-xing-by-leetcode-/)、[文字题解](https://leetcode-cn.com/problems/largest-rectangle-in-histogram/solution/bao-li-jie-fa-zhan-by-liweiwei1419/) |
| 42   | [接雨水](https://leetcode-cn.com/problems/trapping-rain-water/)（困难） | [文字题解](https://leetcode-cn.com/problems/trapping-rain-water/solution/bao-li-jie-fa-yi-kong-jian-huan-shi-jian-zhi-zhen-/) |
| 739  | [每日温度](https://leetcode-cn.com/problems/daily-temperatures/)（中等） | [文字题解](https://leetcode-cn.com/problems/daily-temperatures/solution/bao-li-jie-fa-dan-diao-zhan-by-liweiwei1419/) |
| 316  | [去除重复字母](https://leetcode-cn.com/problems/remove-duplicate-letters/)（困难） | [文字题解](https://leetcode-cn.com/problems/remove-duplicate-letters/solution/zhan-by-liweiwei1419/) |

**说明**：

+ 第 739 题：推荐阅读 [程序员的自我修养：739. Daily Temperatures](https://leetcode-cn.com/problems/daily-temperatures/solution/cheng-xu-yuan-de-zi-wo-xiu-yang-739-daily-temperat/)；

**练习**：

| 序号 | 题目                                                         | 题解                                                         |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 496  | [下一个更大元素 I（简单）](https://leetcode-cn.com/problems/next-greater-element-i/) | [暴力解法、单调栈](https://leetcode-cn.com/problems/next-greater-element-i/solution/bao-li-jie-fa-dan-diao-zhan-by-liweiwei1419-2/) |
| 503  | [下一个更大元素 II（中等）](https://leetcode-cn.com/problems/next-greater-element-ii/) |                                                              |
| 901  | [股票价格跨度（中等）](https://leetcode-cn.com/problems/online-stock-span/) | [LeetCode 第 901 题：股票价格跨度（单调栈）](https://blog.csdn.net/lw_power/article/details/103957702) |

### 二、队列

#### 题型一：基本的使用队列解决的问题

所有的使用广度优先遍历解决的问题，都使用了队列。

| 题号 | 题目序号                                                     | 题解                                                         |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 622  | [设计循环队列](https://leetcode-cn.com/problems/design-circular-queue)（中等） | [数组实现的循环队列](https://leetcode-cn.com/problems/design-circular-queue/solution/shu-zu-shi-xian-de-xun-huan-dui-lie-by-liweiwei141/) |
| 641  | [设计循环双端队列](https://leetcode-cn.com/problems/design-circular-deque)（中等） | [数组实现的循环双端队列](https://leetcode-cn.com/problems/design-circular-deque/solution/shu-zu-shi-xian-de-xun-huan-shuang-duan-dui-lie-by/) |
| 621  | [任务调度器](https://leetcode-cn.com/problems/task-scheduler)（中等） |                                                              |
| 1306 | [跳跃游戏 III（中等）](https://leetcode-cn.com/problems/jump-game-iii)（中等） |                                                              |

#### 题型二：单调队列

单调队列就是普通的队列。「力扣」上的单调队列目前就发现这一个问题，关键分析清楚为什么设计的算法恰好使得单调队列。另外，「背包问题」中有使用单调队列进行优化的例子，感兴趣的朋友可以了解一下，是竞赛方面的知识。

经验：单调队列中一般存下标。

| 题号 | 链接                                                         | 题解                                                         |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 239  | [滑动窗口最大值](https://leetcode-cn.com/problems/sliding-window-maximum)（中等） | [文字题解](https://leetcode-cn.com/problems/sliding-window-maximum/solution/zui-da-suo-yin-dui-shuang-duan-dui-lie-cun-suo-yin/) |

## 第 9 章 优先队列

说明：了解「堆」作为「优先队列」的实现是有必要的，有助于理解 `remove()` 、`replace()` 这些编码的细节，使用堆的时候才会更加有效。

应用：**动态** 选取当前队列中优先级最高的元素，重点理解「动态」的含义。

| 题号 | 链接                                                         | 题解                                                         |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 23   | [合并K个排序链表](https://leetcode-cn.com/problems/merge-k-sorted-lists/)（困难） | [文字题解](https://leetcode-cn.com/problems/merge-k-sorted-lists/solution/tan-xin-suan-fa-you-xian-dui-lie-fen-zhi-fa-python/) |
| 215  | [数组中的第K个最大元素](https://leetcode-cn.com/problems/kth-largest-element-in-an-array/)（中等） | [文字题解](https://leetcode-cn.com/problems/kth-largest-element-in-an-array/solution/partitionfen-er-zhi-zhi-you-xian-dui-lie-java-dai-/) |
| 295  | [数据流的中位数](https://leetcode-cn.com/problems/find-median-from-data-stream)（困难） | [文字题解](https://leetcode-cn.com/problems/find-median-from-data-stream/solution/you-xian-dui-lie-python-dai-ma-java-dai-ma-by-liwe/) |
| 347  | [前 K 个高频元素](https://leetcode-cn.com/problems/top-k-frequent-elements)（中等） |                                                              |
| 703  | [数据流中的第K大元素](https://leetcode-cn.com/problems/kth-largest-element-in-a-stream)（简单） |                                                              |
| 973  | [最接近原点的 K 个点](https://leetcode-cn.com/problems/k-closest-points-to-origin)（中等） |                                                              |
| 1296 | [划分数组为连续数字的集合](https://leetcode-cn.com/problems/divide-array-in-sets-of-k-consecutive-numbers)（中等） |                                                              |

## 第 10 章 并查集

并查集知识点的视频讲解在第 990 题视频题解里有。基础且常见的问题有：

|      | 题目序号                                                     | 题解                                                         |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 990  | [等式方程的可满足性](https://leetcode-cn.com/problems/satisfiability-of-equality-equations)（中等） | [视频题解](https://leetcode-cn.com/problems/satisfiability-of-equality-equations/solution/deng-shi-fang-cheng-de-ke-man-zu-xing-by-leetcode-/)、[文字题解](https://leetcode-cn.com/problems/satisfiability-of-equality-equations/solution/shi-yong-bing-cha-ji-chu-li-bu-xiang-jiao-ji-he-we/) |
| 547  | [朋友圈（中等）](https://leetcode-cn.com/problems/friend-circles)（中等） | [文字题解](https://leetcode-cn.com/problems/friend-circles/solution/bing-cha-ji-python-dai-ma-java-dai-ma-by-liweiwei1/) |
| 200  | [岛屿数量（中等）](https://leetcode-cn.com/problems/number-of-islands)（中等） | [文字题解](https://leetcode-cn.com/problems/number-of-islands/solution/dfs-bfs-bing-cha-ji-python-dai-ma-java-dai-ma-by-l/) |
| 684  | [冗余连接](https://leetcode-cn.com/problems/redundant-connection/)（中等） |                                                              |
| 1319 | [连通网络的操作次数](https://leetcode-cn.com/problems/number-of-operations-to-make-network-connected)（中等） | [文字题解](https://leetcode-cn.com/problems/number-of-operations-to-make-network-connected/solution/bing-cha-ji-by-liweiwei1419/) |
| 128  | [最长连续序列（困难）](https://leetcode-cn.com/problems/longest-consecutive-sequence)（中等） |                                                              |

选做问题：

| 题号 | 链接                                                         | 题解                                                         |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 945  | [使数组唯一的最小增量](https://leetcode-cn.com/problems/minimum-increment-to-make-array-unique/)（中等） | [文字题解](https://leetcode-cn.com/problems/minimum-increment-to-make-array-unique/solution/tan-xin-suan-fa-bing-cha-ji-java-by-liweiwei1419/) |
| 399  | [除法求值](https://leetcode-cn.com/problems/evaluate-division)（中等） |                                                              |
| 685  | [冗余连接 II](https://leetcode-cn.com/problems/redundant-connection-ii/)（困难） |                                                              |
| 721  | [账户合并](https://leetcode-cn.com/problems/accounts-merge/)（中等） |                                                              |
| 765  | [情侣牵手](https://leetcode-cn.com/problems/couples-holding-hands)（困难） |                                                              |
| 952  | [按公因数计算最大组件大小](https://leetcode-cn.com/problems/largest-component-size-by-common-factor)（困难） | [文字题解](https://leetcode-cn.com/problems/largest-component-size-by-common-factor/solution/bing-cha-ji-java-python-by-liweiwei1419/) |

## 第 11 章 树（二叉树与二分搜索树）

| 题号 | 题目序号                                                     | 题解                                                         |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 105  | [从前序与中序遍历序列构造二叉树](https://leetcode-cn.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/) | [视频题解](https://leetcode-cn.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/solution/cong-qian-xu-yu-zhong-xu-bian-li-xu-lie-gou-zao-9/)、[文字题解](https://leetcode-cn.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/solution/qian-xu-bian-li-python-dai-ma-java-dai-ma-by-liwei/) |
| 106  | [从中序与后序遍历序列构造二叉树](https://leetcode-cn.com/problems/construct-binary-tree-from-inorder-and-postorder-traversal/) | [文字题解](https://leetcode-cn.com/problems/construct-binary-tree-from-inorder-and-postorder-traversal/solution/hou-xu-bian-li-python-dai-ma-java-dai-ma-by-liwe-2/) |
| 94   | [二叉树的中序遍历](https://leetcode-cn.com/problems/binary-tree-inorder-traversal/) | [文字题解](https://leetcode-cn.com/problems/binary-tree-inorder-traversal/solution/mo-ni-xi-tong-zhan-wan-cheng-fei-di-gui-zhong-xu-b/) |
| 109  | [有序链表转换二叉搜索树](https://leetcode-cn.com/problems/convert-sorted-list-to-binary-search-tree/) | [文字题解](https://leetcode-cn.com/problems/convert-sorted-list-to-binary-search-tree/solution/fen-zhi-fa-python-dai-ma-java-dai-ma-by-liweiwei14/) |
| 199  | [二叉树的右视图](https://leetcode-cn.com/problems/binary-tree-right-side-view/) | [文字题解](https://leetcode-cn.com/problems/binary-tree-right-side-view/solution/dfs-he-bfspython-dai-ma-by-liweiwei1419/) |
| 230  | [二叉搜索树中第K小的元素](https://leetcode-cn.com/problems/kth-smallest-element-in-a-bst/) | [文字题解](https://leetcode-cn.com/problems/kth-smallest-element-in-a-bst/solution/di-gui-yu-fei-di-gui-xie-fa-tong-li-wan-cheng-di-1/) |
| 226  | [题目：翻转二叉树](https://leetcode-cn.com/problems/invert-binary-tree/) | [文字题解](https://leetcode-cn.com/problems/invert-binary-tree/solution/qian-zhong-hou-xu-bian-li-ceng-xu-bian-li-by-liwei/) |
| 108  | [将有序数组转换为二叉搜索树](https://leetcode-cn.com/problems/convert-sorted-array-to-binary-search-tree/) | [文字题解](https://leetcode-cn.com/problems/convert-sorted-array-to-binary-search-tree/solution/fen-er-zhi-zhi-di-gui-by-liweiwei1419/) |







[题目：257. 二叉树的所有路径](https://leetcode-cn.com/problems/binary-tree-paths/)  [回溯算法（Python 代码、Java 代码）](https://leetcode-cn.com/problems/binary-tree-paths/solution/shen-du-you-xian-bian-li-python-dai-ma-by-liweiwei/)









