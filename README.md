# Othello_Python

中山大学 人工智能项目：Othello黑白棋.

python实现，DQN框架。



## Readme

#### 文件组织

code文件夹：

- data文件夹：
  - 训练216000次的defensive和offensive文件，表示后手和先手；
  - board.jpg，表示棋盘；
- 运行黑白棋程序时，可直接运行`run.py`，通过`me_first`变量来修改是人先手还是电脑先手。
  - `run_cuda.ipynb`是在训练迭代时的文件，在cuda环境下的jupyter notebook中运行。

#### 优化

这是简单版本的黑白棋，效果并不好。可优化点如下：

1. 修改得分策略：若4个边角位可占据，则先下边角位；
2. minimax
3. 使用MCTS蒙特卡罗树搜索。

