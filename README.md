Prometheus_swarm

## prometheus项目的扩展

**step 1：替换swarm__control 文件夹为该文件（本项目只修改了swarm相关代码）**

​			具体而言：在swarm_control 中加入合围控制选项，提供目标点（无人机或者其他物体位置的坐标）

**step 2：  将提供的launch文件放入 simulator/launch_swarm文件夹内作为启动文件**

**step 3：启动后在终端输入解锁、起飞指令后输入9进入containment模式**

最终效果：

<img src="/home/msg/Pictures/Screenshot from 2021-11-03 20-36-29.png" style="zoom:80%;" />
