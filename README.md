# slam-demo
内容:
a) 编写了简单的 Camera, Frame, Map, Mappoint, config 以及 visual_odometry
类
b) Camera 类实现了个坐标系的转换;Map 类管理全部的路标点;Mappoint 类已当前帧特
征点与上一帧结合估计当前位姿,存储描述子以及路标点被观测次数;Config 类实现了
文件的读取;visual_odometry 类以 PnP 计算相机运动
根据《SLAM十四讲》
