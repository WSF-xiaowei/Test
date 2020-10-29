reStructuredText入门
============================
.. default-domain:: reStructuredText入门
.. py:module:: reStructuredText入门

本节简要介绍了reStructuredText (reST)的概念和语法，旨在提供足够的信息来高效地编写文档。因为reST是一个简单的，不显眼的标记语言，这不会花费太长时间来入门。

.. _my-reference:

行内标记
-------------
- 单星号： ``*text*`` 强调 (斜体),
- 双星号： ``**text**`` 重点强调 (粗体)
- 反引号： ````text```` 代码示例。

列表标记
-------------
::

 1. one
 2. two

 #. one
 #. two

 - one
 - two



代码块标记
-------------
段尾加入特殊标记 :: 引入

.. caution::
   注意空行

::

 代码块...

表格标记
-------------
=====  =====  =======
A      B      A and B
=====  =====  =======
False  False  False
True   False  False
False  True   False
True   True   True
=====  =====  =======

超链接标记
-------------
外部链接::
https://github.com/SeayXu/
 `a link`_
 .. _a link: http://www.baidu.com/

 `a link<http://www.baidu.com/>`_

`a link`_
.._a link: http://www.baidu.com/

内部链接::

 .. _my-reference:

 行内标记
 my-reference_

行内标记 my-reference_

章节标记
-------------
::

 ========
 大标题
 ========

 小标题
 --------


图片
-------------
::

..  imagea:a.png