===============
时间间隔类
===============


+-------------+---------------+
|属性         |值             |
+=============+===============+
|命名空间     |fize\\datetime |
+-------------+---------------+
|类名         |Interval       |
+-------------+---------------+
|父类         |DateInterval   |
+-------------+---------------+


:方法:


+----------+----------------------------+
|方法名    |说明                        |
+==========+============================+
|`diff()`_ |获取两个时间的区间          |
+----------+----------------------------+


方法
======
diff()
------
获取两个时间的区间

.. code-block:: php

  public static function diff (
      string|\DateTime $dt1,
      string|\DateTime $dt2
  ) : \DateInterval


:参数:
  +-------+------------------------------------+
  |名称   |说明                                |
  +=======+====================================+
  |dt1    |时间字符串或者DateTime对象          |
  +-------+------------------------------------+
  |dt2    |时间字符串或者DateTime对象          |
  +-------+------------------------------------+
  
  


