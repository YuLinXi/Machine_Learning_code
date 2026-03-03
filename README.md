

# Machine Learning Code

机器学习代码仓库，包含吴恩达机器学习专项课程的完整代码实现。

## 课程概述

本仓库包含了机器学习专项课程的三门课程的代码实现：

1. **监督学习回归与分类 (Supervised Machine Learning: Regression and Classification)**
2. **高级学习算法 (Advanced Learning Algorithms)**
3. **无监督学习、推荐系统与强化学习 (Unsupervised Learning, Recommenders, Reinforcement Learning)**

## 课程内容

### 第一门课程：监督学习回归与分类

| 周次 | 内容 |
|------|------|
| Week 1 | 监督学习 vs 无监督学习、回归模型、梯度下降 |
| Week 2 | 多元线性回归、特征缩放、学习率调整 |
| Week 3 | 逻辑回归分类、决策边界、过拟合问题、正则化 |

### 第二门课程：高级学习算法

| 周次 | 内容 |
|------|------|
| Week 1 | 神经网络直观理解、神经网络模型、TensorFlow实现 |
| Week 2 | 神经网络训练、激活函数、多分类问题 |
| Week 3 | 机器学习应用建议、偏差与方差分析 |
| Week 4 | 决策树、树集成方法 |

### 第三门课程：无监督学习、推荐系统与强化学习

| 周次 | 内容 |
|------|------|
| Week 1 | 聚类算法、K-means、异常检测 |
| Week 2 | 协同过滤推荐系统、基于内容的推荐 |
| Week 3 | 强化学习基础、深度Q学习 |

## 主要文件说明

### 工具函数库

- `lab_utils_common.py` - 通用工具函数（梯度下降、代价函数等）
- `lab_utils_uni.py` - 单元回归可视化工具
- `lab_utils_multi.py` - 多元回归可视化工具
- `lab_utils_relu.py` - ReLU激活函数可视化
- `lab_utils_softmax.py` - Softmax可视化
- `lab_utils_multiclass_TF.py` - 多分类TensorFlow工具

### 实践作业

每个课程都包含：

- **Jupyter Notebook实验** - 交互式编程练习
- **实践测验** - 章节知识检测
- **编程作业** - 综合练习项目
- **数据集** - 课程使用的示例数据

## 环境要求

- Python 3.x
- NumPy
- Matplotlib
- TensorFlow
- Scikit-learn

安装依赖：

```bash
pip install numpy matplotlib tensorflow scikit-learn
```

## 使用说明

1. 克隆仓库：
   ```bash
   git clone https://gitee.com/yulinxibest/Machine_Learning_code
   ```

2. 进入对应课程目录：
   ```bash
   cd "One Supervised Machine Learning Regression and Classification"
   ```

3. 使用Jupyter Notebook打开并运行`.ipynb`文件：
   ```bash
   jupyter notebook
   ```

## 课程参考

本仓库代码基于Coursera上吴恩达的Machine Learning Specialization课程。

- 课程链接：https://www.coursera.org/specializations/machine-learning-introduction

## 目录结构

```
Machine_Learning_code/
├── One Supervised Machine Learning Regression and Classification/
│   ├── week1/          # 监督学习基础
│   ├── week2/          # 多元线性回归
│   └── week3/          # 逻辑回归
├── Two Advanced Learning Algorithms/
│   ├── week1/          # 神经网络基础
│   ├── week2/          # 神经网络训练
│   ├── week3/          # 偏差与方差
│   └── week4/          # 决策树
└── Three Unsupervised learning recommenders reinforcement learning/
    ├── week1/          # 聚类与异常检测
    ├── week2/          # 推荐系统
    └── week3/          # 强化学习
```

## 许可证

本仓库仅供学习交流使用，请尊重课程版权。

## 致谢

感谢吴恩达教授及其团队提供的优质机器学习课程内容。