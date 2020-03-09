[LCP 2] 分式化简
================

-  https://leetcode-cn.com/problems/deep-dark-fraction

题目描述
--------

.. raw:: html

   <p>

有一个同学在学习分式。他需要将一个连分数化成最简分数，你能帮助他吗？

.. raw:: html

   </p>

.. raw:: html

   <p>

.. raw:: html

   </p>

.. raw:: html

   <p>

连分数是形如上图的分式。在本题中，所有系数都是大于等于0的整数。

.. raw:: html

   </p>

.. raw:: html

   <p>

 

.. raw:: html

   </p>

.. raw:: html

   <p>

输入的cont代表连分数的系数（cont[0]代表上图的a0，以此类推）。返回一个长度为2的数组[n,
m]，使得连分数的值等于n / m，且n, m最大公约数为1。

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

   <pre><strong>输入：</strong>cont = [3, 2, 0, 2]
   <strong>输出：</strong>[13, 4]
   <strong>解释：</strong>原连分数等价于3 + (1 / (2 + (1 / (0 + 1 / 2))))。注意[26, 8], [-13, -4]都不是正确答案。</pre>

.. raw:: html

   <p>

示例 2：

.. raw:: html

   </p>

.. raw:: html

   <pre><strong>输入：</strong>cont = [0, 0, 3]
   <strong>输出：</strong>[3, 1]
   <strong>解释：</strong>如果答案是整数，令分母为1即可。</pre>

.. raw:: html

   <p>

限制：

.. raw:: html

   </p>

.. raw:: html

   <ol>

::

    <li><code>cont[i] &gt;= 0</code></li>
    <li><code>1 &lt;= cont的长度 &lt;= 10</code></li>
    <li><code>cont</code>最后一个元素不等于0</li>
    <li>答案的<code>n, m</code>的取值都能被32位int整型存下（即不超过<code>2 ^ 31 - 1</code>）。</li>

.. raw:: html

   </ol>

题目代码
--------

.. code:: cpp

    class Solution {
    public:
        vector<int> fraction(vector<int>& cont) {

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
