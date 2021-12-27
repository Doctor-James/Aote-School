slam.launch: 建图（建好图之后保存）
map_save.launch: 保存地图（yaml，pgm）
map_server.launch: 发布地图服务
amcl_diff.launch: 定位
test_amcl.launch: 从保存的地图中订阅地图服务，集成amcl定位，通过键盘控制移动
path.launch: move_base节点调用
move_path.launch: 从保存的地图中订阅地图服务，集成amcl定位，move_base路径规划
auto_slam.launch: 不提供静态全局地图，一边运动一边建图（建好图之后保存）
