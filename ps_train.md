worker:

解析命令行参数

Nacos：负责注册ip发包

训练 记录开始时刻

记录optimizer 

id_async   id异步 nn同步

sync   nn和id都同步

ysnc就是V1



postProcessor



readProcessor

preProcwssor

gradientProcessor

postProcessor

- 前处理
  - 准备训练数据，包括加载、清洗、特征工程和分发。
- 求梯度
  - 通过前向传播、损失计算和反向传播计算模型参数的梯度。
- 后处理
  - 计算评估指标（如 AUC）、推送梯度到参数服务器，并记录日志。