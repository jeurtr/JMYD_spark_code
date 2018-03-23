JMYD_spark_code
====

#江门移动信令数据spark处理过程
##样本示例
*811078192773333,23,1492098117,1492098118,江门恩平小岛新村F-ZLH-2,112.31395,22.18322,恩平,恩城镇,否,宏站,室外,城区道路,\N,\N

USER_ID = 0                   # 用户 id
START_HOUR = 1                # 开始的小时数  int
START_TIME = 2                # 开始时间戳    int
END_TIME = 3                  # 结束时间戳    int
STATION = 4                   # 基站
LON = 5                       # 经纬度        float
LAT = 6                       # 经纬度        float
COUNTRY = 7                   # 区县
TOWN = 8                      # 镇
STATION_ROAD = 9              # 是/否 是否为江门大道上的基站
STATION_TYPE = 10             # 宏站
STATION_SIDE = 11             # 室外
COUNTRY_ROAD = 12             # 城区道路
# 13 \N
# 14 \N

