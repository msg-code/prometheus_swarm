Prometheus_swarm

## prometheus项目的扩展(https://github.com/amov-lab/Prometheus/wiki)

**step 1：替换swarm__control 文件夹为该文件（本项目只修改了swarm相关代码）**

​			具体而言：在swarm_control 中加入合围控制选项，提供目标点（无人机或者其他物体位置的坐标）

**step 2：  将提供的launch文件放入 simulator/launch_swarm文件夹内作为启动文件**

**step 3：启动后在终端输入解锁、起飞指令后输入9进入containment模式**

**参考文献 Bearing-based Bionic Encirclement Control Inspired by Dolphins（doi:10.1109/ICCA.2019.8900008）
   和 Event-triggered encirclement control of multi-agent systems with bearing rigidity(doi:10.1007/s11432-017-9109-9) **

   注：采用方位刚性的图论知识进行合围队形的控制 本质上上是编队的构型和移动

最终效果：
![](image-storage/containment_formation.gif)

