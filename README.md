shanghai_subway_find
====================

socket通信原理实现简单的地鉄线路查询(最短路径，且此路径上的最少换乘)系统.
　
　此程序中的数据是保存在mysql数据库中的，数据就是那几个txt文本文件，只要导入数据库中就行，
但在建立表时要把表的名字和txt文本文件的名字一样，不然的话就要修改程序中所读的表的名字为你
所新起的名字。
    注意：38_station.txt保存的是38　× 38的邻接矩阵，sub_info.txt中的后五个数应按整型存储。
  　此程序是在Linux系统的Ubuntu版本下开发的。
