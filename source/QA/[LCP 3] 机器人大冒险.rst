[LCP 3] 机器人大冒险
====================

-  https://leetcode-cn.com/problems/programmable-robot

题目描述
--------

.. raw:: html

   <p>

力扣团队买了一个可编程机器人，机器人初始位置在原点(0,
0)。小伙伴事先给机器人输入一串指令command，机器人就会无限循环这条指令的步骤进行移动。指令有两种：

.. raw:: html

   </p>

.. raw:: html

   <ol>

::

    <li><code>U</code>: 向<code>y</code>轴正方向移动一格</li>
    <li><code>R</code>: 向<code>x</code>轴正方向移动一格。</li>

.. raw:: html

   </ol>

.. raw:: html

   <p>

不幸的是，在 xy
平面上还有一些障碍物，他们的坐标用obstacles表示。机器人一旦碰到障碍物就会被损毁。

.. raw:: html

   </p>

.. raw:: html

   <p>

给定终点坐标(x,
y)，返回机器人能否完好地到达终点。如果能，返回true；否则返回false。

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

   <pre><strong>输入：</strong>command = &quot;URR&quot;, obstacles = [], x = 3, y = 2
   <strong>输出：</strong>true
   <strong>解释：</strong>U(0, 1) -&gt; R(1, 1) -&gt; R(2, 1) -&gt; U(2, 2) -&gt; R(3, 2)。</pre>

.. raw:: html

   <p>

示例 2：

.. raw:: html

   </p>

.. raw:: html

   <pre><strong>输入：</strong>command = &quot;URR&quot;, obstacles = [[2, 2]], x = 3, y = 2
   <strong>输出：</strong>false
   <strong>解释：</strong>机器人在到达终点前会碰到(2, 2)的障碍物。</pre>

.. raw:: html

   <p>

示例 3：

.. raw:: html

   </p>

.. raw:: html

   <pre><strong>输入：</strong>command = &quot;URR&quot;, obstacles = [[4, 2]], x = 3, y = 2
   <strong>输出：</strong>true
   <strong>解释：</strong>到达终点后，再碰到障碍物也不影响返回结果。</pre>

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

    <li><code>2 &lt;= command的长度 &lt;= 1000</code></li>
    <li><code>command</code>由<code>U，R</code>构成，且至少有一个<code>U</code>，至少有一个<code>R</code></li>
    <li><code>0 &lt;= x &lt;= 1e9, 0 &lt;= y &lt;= 1e9</code></li>
    <li><code>0 &lt;= obstacles的长度 &lt;= 1000</code></li>
    <li><code>obstacles[i]</code>不为原点或者终点</li>

.. raw:: html

   </ol>

题目代码
--------

.. code:: cpp

    class Solution {
    public:
        bool robot(string command, vector<vector<int>>& obstacles, int x, int y) {

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
