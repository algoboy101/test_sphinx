[1078] Bigram 分词
==================

-  https://leetcode-cn.com/problems/occurrences-after-bigram

题目描述
--------

.. raw:: html

   <p>

给出第一个词 first 和第二个词 second，考虑在某些文本 text 中可能以
"first second third"
形式出现的情况，其中 second 紧随 first 出现，third 紧随 second 出现。

.. raw:: html

   </p>

.. raw:: html

   <p>

对于每种这样的情况，将第三个词 "third" 添加到答案中，并返回答案。

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

   <pre><strong>输入：</strong>text = &quot;alice is a good girl she is a good student&quot;, first = &quot;a&quot;, second = &quot;good&quot;
   <strong>输出：</strong>[&quot;girl&quot;,&quot;student&quot;]
   </pre>

.. raw:: html

   <p>

示例 2：

.. raw:: html

   </p>

.. raw:: html

   <pre><strong>输入：</strong>text = &quot;we will we will rock you&quot;, first = &quot;we&quot;, second = &quot;will&quot;
   <strong>输出：</strong>[&quot;we&quot;,&quot;rock&quot;]
   </pre>

.. raw:: html

   <p>

 

.. raw:: html

   </p>

.. raw:: html

   <p>

提示：

.. raw:: html

   </p>

.. raw:: html

   <ol>

::

    <li><code>1 &lt;= text.length &lt;= 1000</code></li>
    <li><code>text</code>&nbsp;由一些用空格分隔的单词组成，每个单词都由小写英文字母组成</li>
    <li><code>1 &lt;= first.length, second.length &lt;= 10</code></li>
    <li><code>first</code> 和&nbsp;<code>second</code>&nbsp;由小写英文字母组成</li>

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

哈希表

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
        vector<string> findOcurrences(string text, string first, string second) {

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
