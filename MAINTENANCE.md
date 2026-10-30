# network-exercise 维护说明

《神经网络与深度学习》课程的练习与 Notebook。

- 上游：https://github.com/nndl/nndl-practice
- 在线文档：https://xiaoshecode.github.io/xiaoshecode/repos/network-exercise/
- 检查日期：2026-10-30

## 环境与使用

- 为具体章节准备 NumPy、Jupyter 及相应深度学习框架，不能假定所有章节共用环境。

使用/检查入口（需先满足依赖条件）：

- `jupyter notebook`

## 目录职责

- chap1_warmup/ — NumPy 热身
- chap5_CNN/ / chap6_RNN/ — 神经网络练习
- chap12_RBM/rbm.py — RBM 练习骨架
- chap14_reinforcement_learning/ — 强化学习练习

## 本次整理

- 新增维护文档和在线文档入口，补全用途、目录、使用路径及验证边界。
- 将 RBM 脚本 Python 2 print 语法改为 Python 3，保留待填写的课程练习。

## 检查记录

- **仓库目录与入口盘点**（passed）：检查 Git 索引中的 60 个路径、README 和项目配置；不等于功能验收。
- **Python AST**（passed）：8 个文件通过解析；不导入依赖、不执行应用。
- **JSON/notebook parse**（passed）：19 个文件通过解析；不导入依赖、不执行应用。
- **完整构建与端到端运行**（not_run）：RBM 等练习刻意留有 pass/待填写代码，语法修复不代表完成题目。未训练模型或执行 Notebook。

## 验证边界与待办

- RBM 等练习刻意留有 pass/待填写代码，语法修复不代表完成题目。未训练模型或执行 Notebook。

## 后续维护约定

保留上游许可证与作者信息。沿用现有模块边界和格式配置；修复功能时同步最小回归验证。依赖或接口变更需写明迁移步骤，避免仅为目录美观搬动公开入口。
