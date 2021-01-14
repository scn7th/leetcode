一、 字符串问题
1. 最长字串问题——滑动窗口
《leetcode-No424 最长重复字符替换——滑动窗口》
《leetcode-No003 无重复字符的最大 substring——滑动窗口》
《lc11-Container With Most Water》
《leetcode-No567 字符串中的排列组合——滑动窗口》
2. 回文——动态规划
1) 二维动态规划
《leetcode-No005 找出字符串中的最长回文》
《leetcode-No131 回文划分》
2) Manacher 算法
《leetcode-No005 找出字符串中的最长回文》
3. 字符串查询——最长前缀后缀
《leetcode-No028 字符串 indexOf、KMP 和 Sunday》
《leetcode-No214 构建最小回文》
4. 字符串模板匹配
《leetcode-No010 字符串匹配模板——二维动态规划》
《leetcode-No459 重复字串模式》
5. 编辑距离
《leetcode-No72 可编辑距离》
《leetcode-No583 两个符串相等删除操作——最长公共子序列和可编辑距离》
《Minimum ASCII Delete Sum for Two Strings》
6. longest common sequence——编辑距离的反向问题
《1143. Longest Common Subsequence》
《1035. Uncrossed Lines》
7. longest common subArray——longest common sequence 的同类问题
《leetcode-No718 最长重复子数组——动态规划》
8. 翻转判断
《leetcode-No777 翻转 LR 字符串——数组判断》

二、 栈
1. 括号问题
前置问题：divide and conquer：

《leetcode-No022 生成括号和卡塔兰数》
闭包法的相似问题：《leetcode-No790 模块铺地——数学归纳法》
《leetcode-No032 满足括号格式的最长子串》
《leetcode-No241 不同括号生成的不同结果》
《leetcode-No301-移除不合规的括号》
栈：
《leetcode-No678 验证带有星号的括号字符串》

三、 数组问题
1. 桶
《leetcode-No041 找到第一个缺失的正整数——bucket 和 cyclic permatation》
《leetcode-No220 判断是否存在一定范围内几乎相同的数》
《leetcode-No539 最小时间差》
2. 排序
1) 归并排序及其扩展
《leetcode-No023 合并 k 个有序链表》
《leetcode-No632 覆盖 k 列表元素的最小范围——合并 k 个有序序列》
《leetcode-No148 链表排序》
《leetcode-No315-之后比当前值小的个数》归并+dp
《leetcode-No493 统计数组中比当前小的右侧元素个数——mergeSort》
No315, No493, No327
2) 交换位置
《179.Largest Number》
3. 双指针——数组中 k 个数求和与 target 比较
对数组进行 k-1 重循环，时间复杂度 O(n^(k-1))。
利用数组有序性，在最内层循环，使用双指针可以降低 1 层循环的计算，是原本 O(n^k)
的时间复杂度降低为 O(n^(k-1))。
《leetcode-No015 找出数组中所有 3 个数之和为 0 的组合》
《Lc16-3Sum Closest》
《lc18-4Sum》
《leetcode-No611 三角形数量——有序序列的三指针法削减时间复杂度》
《leetcode-No633 是否可以等于 2 个数的平方——双指针法》
《leetcode-No581 最短未排序连续子数组》
4. 按照规则完美切分数组为子序列
《leetcode-No659 把数组分成连续子序列》
5. 单调序列
1) 基本单调序列
《leetcode-No239 滑动窗口的最大值——单调队列》
《leetcode-No300 最长递增序列——patience sorting》
《leetcode-No673 最长递增序列的个数》——动态规划
《leetcode-No496 序列中下一个比它大的数——单调序列》
《leetcode-No402 删除数字》
2) 找到左/右侧比当前小的第一个位置——动态规划
《leetcode-No084 计算矩阵的面积》
3) 利用单独序列得到比当前最大值稍小的那个元素
《leetcode-No456 模式 123》 + 2
6. cyclic swap 循环置换
《leetcode-No041 找到第一个缺失的正整数——bucket 和 cyclic permatation》
《leetcode-No765 情侣牵手——循环置换汇总》
《565. Array Nesting》
7. 数组扩展的序列的第 k 个数
1) 中位数
《leetcode-No004 找出两个有序数组的中位数》
《leetcode-No295 找寻数据流中的中位数》
《leetcode-No480 滑动窗口的中位数》
2) 找到无序序列中第 k 个数——快排和堆
《leetcode-No215 找到无序序列中第 k 大的数》
《leetcode-No632 覆盖 k 列表元素的最小范围——合并 k 个有序序列》
3) 复杂序列第 k 个数——贪心算法和二分查找
《leetcode-No786 复杂序列第 k 个数——优化后的贪心算法和二分查找》
《leetcode-No264ugly 数——动态规划无法执行 256 中贪心算法》
8. 置换与虚拟指针
《leetcode-No75 与 No324 三分法》
《leetcode-No324-摆动问题》
9. 连续区间问题
1) 区间范围查询
区间不可变：presum《303. Range Sum Query - Immutable》
区间可变：segment tree《leetcode-No307-可更改的区间求和》
2) 连续子区间求和等于 k
《leetcode-No560presum 与数组中连续子序列之和等于 k》
1546 

《leetcode-No437 路径求和 III》
3) 反向问题：满足上下限的区间个数统计
前置问题：《leetcode-No611 三角形数量——有序序列的三指针法削减时间复杂度》
《leetcode-No493 统计数组中比当前小的右侧元素个数——mergeSort》
4) 连续子数组数量
《leetcode-No413 等差数列切割》
《leetcode-No467 循环字符串的唯一子串数量》
10. 遍历问题
1) 倒序
《leetcode-No238 数组中每个元素除了自己的乘积》
2) 对角线遍历
《leetcode-No498 矩阵对角走》
3) 最大最小交替
《leetcode-No152 相邻子数组的最大乘积》 + 1

四、 链表
1. 区间遍历
《leetcode-No019 从链表尾部移除第 n 个节点》

五、 树
1. 遍历问题
1) 基础遍历
《leetcode-No094 二叉树中序遍历和线索树》
《leetcode-No144 二叉树前序遍历》
《leetcode-No145 二叉树后序遍历》
《leetcode-No589n 节点树的前序遍历》
2) 扩展问题
《leetcode-No105 根据前序遍历和中序遍历结果恢复二叉树》
《leetcode-No114 二叉树按照先序顺序扁平成列表》
3) 二叉搜索树与中序遍历
《98. Validate Binary Search Tree》
《69-leetcode-No099 恢复二叉搜索树（只有两个节点需要互换）》
4) 二叉搜索树平衡问题

《leetcode-No110 判断是否是平衡二叉树》
5) 二叉搜索树与前序遍历
《leetcode-No449 二叉搜索树的序列化和反序列化》
6) 二叉树路径求和问题
二叉树中从根节点到叶子节点组成的路径《leetcode-No113判断树节点的路径之和等于sum》
二叉树中任意从上到下组成的路径《leetcode-No437 路径求和 III》
二叉树中任意连续节点组成的路径《124. Binary Tree Maximum Path Sum》
7) 反向遍历——从叶节点到根节点遍历
《leetcode-No780 移动坐标点——二叉树》
8) 二叉搜索树节点删除
《leetcode-No450 删除二叉搜索树节点》
9) 判断子树
《leetcode-No572 是否是另一棵树的子树》，判断 t 是否是 s 的子树，2 次递归，可以使用序
列化
《leetcode-No652 找寻重复的子树》，找出所有重复子树，使用序列化 + 1
10) lca
《236. Lowest Common Ancestor of a Binary Tree》
2. 序列化
普通二叉树的序列化使用 BFS+Null 节点标识即可，而二叉搜索树可以使用前序遍历和
归并，则可以不需要额外的空节点标识。
《leetcode-No449 二叉搜索树的序列化和反序列化》
《leetcode-No652 找寻重复的子树》
3. 归并构建
《leetcode-No096 二叉搜索树组合数量和卡塔兰数》
《leetcode-No109 根据有序链表构建一个平衡二叉树》
4. 前缀树
《leetcode-No212 和 336 回文对——前缀树与系统设计》

六、 图
1. 是否有环：
链表：龟兔赛跑法《leetcode-No142 判断链表是否有环 II》
《leetcode-No287 找到那个唯一重复的数》
无向图：并查集/深度优先 《leetcode-No684 冗余连接——无向图中的环》
有向图：拓扑排序/深度优先《leetcode-No207 课程表——有向图是否有环》

2. 最短路径
《leetcode-No743 网络延迟时间——有向图的最短路径汇总》
3. 双向搜索
《leetcode-No126 和 No752——图的双端搜索》
4. 节点分组
《785. Is Graph Bipartite?》

七、 贪心算法
1. 重叠区域问题——排序
《leetcode-No731 我的日历汇总——重叠区域计算》
《56. Merge Intervals》排序+队列
2. 二维贪心——排序
一般可以根据每个数据进行排序，然后依次判断是否符合条件，二维贪心必需提供一个堆来
进一步获取最优解。
《leetcode-二维贪心-No1383 一个组的最大表现》
3. 不断扩展边界
《leetcode-No045 跳跃游戏》
《leetcode-No763 分割标签——贪心》
《330. Patching Array》
4. 短板
《leetcode-No407 积水——短板与 Dijkstra》
5. 分析题设设计贪心过程
《leetcode-No754 到达一个数——贪心》
《leetcode-No767 重组字符串——数组相邻限制下的贪心算法》
《leetcode-No316-消除重复字母》
《leetcode-No621 任务调度》
《leetcode-No782 转化成象棋盘——观察法》

八、 动态规划
二维动态规划思路：
 如果有 dp[i][j] = dp[i-1][j]相关，即需要之前得到的 i-1 的结果，则可以按照 i=0 递增进行，
j 随意。例如：《59-leetcode-No062 唯一路径——二维路径动态规划》.
 如果有有 dp[i][j]=dp[i][j-1]相关，即需要之前得到的 j-1 的结果，则需要互换 i 和 j 的位

置，即此时 dp[j][i]，i 从 0 开始递增。
 有 dp[i][j]=dp[i][j]，i 必须从 j 开始递减。例如《193-leetcode-No486 预测谁能赢》
 也可以从 0 开始递增，例如上面《27-leetcode-No003 无重复字符的最大 substring
——滑动窗口》，当然直接推荐 i 从 j 递减就好啦。
总结：
 对于普通二维动态规划，我们的目标只有 1 个（1 个入参），那么 dp[i][j]就代表输入参
数中对应数组的下标情况下的最优解，那么最终结果就是 dp[0][n-1].此时最优雅的解法
就是从 length=1 开始，则 j = i + length，当然也可以使用倒序，参见 1 中的题目；
 如果入参有 2 组，那么 dp[i][j]中的 i 和 j 就对应两组入参的位置，参见 2 中的题目，以
及必要时可能需要三维数组 dp
1. 一维目标动态规划
《leetcode-No464 我能否赢》递归+memory
《leetcode-No486 预测谁能赢》
《leetcode-No375-猜数是大还是小 II》
《leetcode-No1406 石头游戏谁能赢 III——动态规划》
《leetcode-No629k 倒序对数组》
2. 二维维目标动态规划
《leetcode-No062 唯一路径——二维路径动态规划》
《leetcode-No312-气球爆炸——reverse thinking》
《leetcode-No688 马在棋盘中概率——反向思维动态规划》
3. 数学归纳法
《leetcode-No790 模块铺地——数学归纳法》
《leetcode-No233 十进制 1 的个数——动态规划》
《leetcode-No740 删除获取最大受益与 No198 打家劫舍总结——动态规划》
4. 动态规划+自定义指针
《leetcode-No368-最大可除子集》

九、 背包问题
背包问题用于求解集合元素的最值不大的情况下，集合元素的组成情况。本质是桶的
动态规划。
1. 元素只能使用 1 次
《leetcode-No416 数组按照求和等分成 2 个子集——一维背包》
《leetcode-No474 装载最多的 0 和 1——二维背包问题》
2. 元素能使用无数次
《leetcode-No322 与 No518 换零钱》
注意，有些问题非常像，单不能使用背包，比如《leetcode-No698 数组分割成 k 个和相等的
子集——dfs》

十、 查找
1. 带有窗口的二分查找
《leetcode-No658 找到最近的 k 个元素》
《leetcode-No786 复杂序列第 k 个数——优化后的贪心算法和二分查找》
2. 有序翻转数组的二分查找
《33. Search in Rotated Sorted Array》
《81. Search in Rotated Sorted Array II》
《153. Find Minimum in Rotated Sorted Array》
3. 局部极大值查询
《leetcode-No162 找到序列中的一个极大值》
4. 查找刚好比自己大和小的值
《475. Heaters》
十一、 数学
1. Bit 异或
《leetcode-No136 单身数》
《leetcode-No137 单身数 2》
《leetcode-No260 单身数 3》
《leetcode-No779 语法中第 k 个标识——数学位运算》
《leetcode-No421 数组中任意 2 个值异或的最大值》
《693. Binary Number with Alternating Bits》
2. Bit 操作
《leetcode-No050 乘方——折半求解》
3. Boyer-Moor voting
《leetcode-No229 找到序列中超过三分之一的数》
4. 概率问题
1) Reject sampling
《leetcode-No470 使用 random7 实现 random10——rejection sampling》
2) 水塘抽样
《leetcode-No382-链表的随机节点——水塘抽样》
3) 极坐标
《leetcode-No478 在圆内生成一个随机数》

4) 随机抽样
《leetcode-No519 随机翻转矩阵》
5. 因式分解
《leetcode-No343-分割整数》
6. 简单公式
《leetcode-No453 最小移动次数使得所有数相等》
7. 质数
《leetcode-No204 计算素数个数》
《leetcode-No650 两键的键盘》
十二、 递归及回溯问题
1. 回溯
《leetcode-No037 数独求解》
《leetcpde-No039 求解所有组合等于指定值》
《40. Combination Sum II》
《51. N-Queens》
《leetcode-No200 孤岛数量》
《leetcode-No698 数组分割成 k 个和相等的子集——dfs》
《leetcode-No417 海水流动》
2. 拆分递归
《leetcode-No638 购物——拆分递归》
3. 巧妙将 2 个递归合并成 1 个
《leetcode-No756 金字塔转移矩阵——完美递归和 dp》
4. 2 次递归
《leetcode-No572 是否是另一棵树的子树》
十三、 hashMap
《leetcode-No676——实现魔术字典——临近构建》
十四、 排列问题
《46. Permutations》
《47. Permutations II》
《31. Next Permutation》

《60. Permutation Sequence》
十五、 状态机
《leetcode-No137 单身数 2》
《leetcode-No714 买卖股票的最佳时机汇总——状态机》
十六、 并查集
原理：《不相交集合（并查集）》
应用：
1. 无向图是否有环：
《leetcode-No684 冗余连接——无向图中的环》
《leetcode-No1320 所需网络连接——并查集》
2. 是否属于同一类：
《leetcode-No721 合并账户——并查集》
《leetcode-No547 朋友圈》
十七、 系统设计
1. 计算器
《43. Multiply Strings》
2. LRU 和 LFU
《leetcode-No146LRU 设计》
《leetcode-No460LFU 设计》
3. 栈和堆
《leetcode-No232 用栈实现队列》
《leetcode-No225 用队列实现栈》
4. 删除注释
《722. Remove Comments》复杂字符串处理
十八、 sql
《176. Second Highest Salary》
《178. Rank Scores》
《180. Consecutive Numbers》
《181. Employees Earning More Than Their Managers》
《182. Duplicate Emails》
《183. Customers Who Never Order》
《184. Department Highest Salary》
《leetcode-No185 各个部门前三工资最高的人》
《leetcode-No262 查询每天的的士取消率》
《leetcode-No626 改变座位 sql——if》
