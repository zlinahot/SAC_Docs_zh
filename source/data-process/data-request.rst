数据申请
========

申请地震波形数据，按照具体的需求，大致可以分为两大类，即事件波形数据
和连续波形数据。这两者的主要区别在于如何确定要申请的数据时间窗，前者
需要震相到时信息，后者则不需要。

事件波形数据
------------

#. **筛选事件**\ ：从地震目录中找出某个特定事件的信息，或根据条件
   筛选出需要的事件，筛选条件通常包括：经纬度范围、深度范围、时间范围、
   震级范围等
#. **筛选台站**\ ：台站位置、仪器类型（宽频段、长周期或短周期）、
   分量类型（三分量或 Z 分量）
#. **确定起始和结束时间**\ ：根据发震时刻和震中距信息，计算震相理论到时，
   由此确定要申请的数据时间窗

事件波形数据又可以进一步分成两类：以事件为中心的事件波形数据（比如地震
定位、震源机制）和以台站为中心的事件波形数据（比如接收函数）。对于以
事件为中心的事件波形数据，通常先筛选地震事件，在筛选台站时，还可以加上
震中距范围和方位角范围的约束；对于以台站为中心的事件波形数据，通常先
确定要使用的台站，在筛选地震事件时，还可以加上震中距和反方位角范围的
约束。

连续波形数据
------------

连续波形数据中没有地震事件的信息，因而都是以台站为中心的，比如背景噪声相关研究。

#. **选择台站**\ ：台站位置、仪器类型、分量类型
#. **确定时间范围**\ ：选择合适的时间范围

当然也可以根据地震事件的信息，确定申请数据的时间范围，所以，某种程度上，
事件波形数据属于连续波形数据的一个子集。
