[0532] 数组中的K-diff数对
=========================

-  https://leetcode-cn.com/problems/k-diff-pairs-in-an-array

题目描述
--------

.. raw:: html

   <p>

给定一个整数数组和一个整数 k, 你需要在数组里找到不同的 k-diff
数对。这里将 k-diff 数对定义为一个整数对 (i, j), 其中 i 和 j
都是数组中的数字，且两数之差的绝对值是 k.

.. raw:: html

   </p>

.. raw:: html

   <p>

示例 1:

.. raw:: html

   </p>

.. raw:: html

   <pre>
   <strong>输入:</strong> [3, 1, 4, 1, 5], k = 2
   <strong>输出:</strong> 2
   <strong>解释: </strong>数组中有两个 2-diff 数对, (1, 3) 和 (3, 5)。
   尽管数组中有两个1，但我们只应返回不同的数对的数量。
   </pre>

.. raw:: html

   <p>

示例 2:

.. raw:: html

   </p>

.. raw:: html

   <pre>
   <strong>输入:</strong>[1, 2, 3, 4, 5], k = 1
   <strong>输出: </strong>4
   <strong>解释:</strong> 数组中有四个 1-diff 数对, (1, 2), (2, 3), (3, 4) 和 (4, 5)。
   </pre>

.. raw:: html

   <p>

示例 3:

.. raw:: html

   </p>

.. raw:: html

   <pre>
   <strong>输入: </strong>[1, 3, 1, 5, 4], k = 0
   <strong>输出: </strong>1
   <strong>解释:</strong> 数组中只有一个 0-diff 数对，(1, 1)。
   </pre>

.. raw:: html

   <p>

注意:

.. raw:: html

   </p>

.. raw:: html

   <ol>

::

    <li>数对 (i, j) 和数对&nbsp;(j, i) 被算作同一数对。</li>
    <li>数组的长度不超过10,000。</li>
    <li>所有输入的整数的范围在&nbsp;[-1e7, 1e7]。</li>

.. raw:: html

   </ol>

.. raw:: html

   <div>

.. raw:: html

   <div>

Related Topics

.. raw:: html

   </div>

.. raw:: html

   <div>

.. raw:: html

   <li>

数组

.. raw:: html

   </li>

.. raw:: html

   <li>

双指针

.. raw:: html

   </li>

.. raw:: html

   </div>

.. raw:: html

   </div>

题目代码
--------

.. code:: cpp

    class Solution {
    public:
        int findPairs(vector<int>& nums, int k) {

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
