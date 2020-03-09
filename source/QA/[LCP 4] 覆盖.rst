[LCP 4] 覆盖
============

-  https://leetcode-cn.com/problems/broken-board-dominoes

题目描述
--------

.. raw:: html

   <p>

你有一块棋盘，棋盘上有一些格子已经坏掉了。你还有无穷块大小为1 \*
2的多米诺骨牌，你想把这些骨牌不重叠地覆盖在完好的格子上，请找出你最多能在棋盘上放多少块骨牌？这些骨牌可以横着或者竖着放。

.. raw:: html

   </p>

.. raw:: html

   <p>

 

.. raw:: html

   </p>

.. raw:: html

   <p>

输入：n, m代表棋盘的大小；broken是一个b \*
2的二维数组，其中每个元素代表棋盘上每一个坏掉的格子的位置。

.. raw:: html

   </p>

.. raw:: html

   <p>

输出：一个整数，代表最多能在棋盘上放的骨牌数。

.. raw:: html

   </p>

.. raw:: html

   <p>

 

.. raw:: html

   </p>

.. raw:: html

   <p>

示例 1：

.. raw:: html

   </p>

.. raw:: html

   <pre><strong>输入：</strong>n = 2, m = 3, broken = [[1, 0], [1, 1]]
   <strong>输出：</strong>2
   <strong>解释：</strong>我们最多可以放两块骨牌：[[0, 0], [0, 1]]以及[[0, 2], [1, 2]]。（见下图）</pre>

.. raw:: html

   <p>

.. raw:: html

   </p>

.. raw:: html

   <p>

 

.. raw:: html

   </p>

.. raw:: html

   <p>

示例 2：

.. raw:: html

   </p>

.. raw:: html

   <pre><strong>输入：</strong>n = 3, m = 3, broken = []
   <strong>输出：</strong>4
   <strong>解释：</strong>下图是其中一种可行的摆放方式
   </pre>

.. raw:: html

   <p>

.. raw:: html

   </p>

.. raw:: html

   <p>

 

.. raw:: html

   </p>

.. raw:: html

   <p>

限制：

.. raw:: html

   </p>

.. raw:: html

   <ol>

::

    <li><code>1 &lt;= n &lt;= 8</code></li>
    <li><code>1 &lt;= m &lt;= 8</code></li>
    <li><code>0 &lt;= b &lt;= n * m</code></li>

.. raw:: html

   </ol>

题目代码
--------

.. code:: cpp

    class Solution {
    public:
        int domino(int n, int m, vector<vector<int>>& broken) {

        }
    };

题目解析
--------

方法一
~~~~~~

分析
^^^^

思路
^^^^

注意
^^^^

知识点
^^^^^^

复杂度
^^^^^^

参考
^^^^

答案
^^^^

.. code:: cpp

    //

方法二
~~~~~~

分析
^^^^

思路
^^^^

注意
^^^^

知识点
^^^^^^

复杂度
^^^^^^

参考
^^^^

答案
^^^^

.. code:: cpp

    //
