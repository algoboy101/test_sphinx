[0712] 两个字符串的最小ASCII删除和
==================================

-  https://leetcode-cn.com/problems/minimum-ascii-delete-sum-for-two-strings

题目描述
--------

.. raw:: html

   <p>

给定两个字符串s1,
s2，找到使两个字符串相等所需删除字符的ASCII值的最小和。

.. raw:: html

   </p>

.. raw:: html

   <p>

示例 1:

.. raw:: html

   </p>

.. raw:: html

   <pre>
   <strong>输入:</strong> s1 = &quot;sea&quot;, s2 = &quot;eat&quot;
   <strong>输出:</strong> 231
   <strong>解释:</strong> 在 &quot;sea&quot; 中删除 &quot;s&quot; 并将 &quot;s&quot; 的值(115)加入总和。
   在 &quot;eat&quot; 中删除 &quot;t&quot; 并将 116 加入总和。
   结束时，两个字符串相等，115 + 116 = 231 就是符合条件的最小和。
   </pre>

.. raw:: html

   <p>

示例 2:

.. raw:: html

   </p>

.. raw:: html

   <pre>
   <strong>输入:</strong> s1 = &quot;delete&quot;, s2 = &quot;leet&quot;
   <strong>输出:</strong> 403
   <strong>解释:</strong> 在 &quot;delete&quot; 中删除 &quot;dee&quot; 字符串变成 &quot;let&quot;，
   将 100[d]+101[e]+101[e] 加入总和。在 &quot;leet&quot; 中删除 &quot;e&quot; 将 101[e] 加入总和。
   结束时，两个字符串都等于 &quot;let&quot;，结果即为 100+101+101+101 = 403 。
   如果改为将两个字符串转换为 &quot;lee&quot; 或 &quot;eet&quot;，我们会得到 433 或 417 的结果，比答案更大。
   </pre>

.. raw:: html

   <p>

注意:

.. raw:: html

   </p>

.. raw:: html

   <ul>

::

    <li><code>0 &lt; s1.length, s2.length &lt;= 1000</code>。</li>
    <li>所有字符串中的字符ASCII值在<code>[97, 122]</code>之间。</li>

.. raw:: html

   </ul>

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

动态规划

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
        int minimumDeleteSum(string s1, string s2) {

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
