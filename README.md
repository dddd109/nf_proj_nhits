# N-HiTS 

- implementation of N-HiTS: Neural Hierarchical Interpolation for Time Series Forecasting.
![N-HiTS-blocks](./asset/blocks.png)

## 简介

N-HiTS（Neural Hierarchical Interpolation for Time Series Forecasting）是一种用于时间序列预测的神经网络架构，采用分层插值模块来捕捉不同时间尺度的模式。本仓库提供了实现代码与可运行的 notebook 演示，方便复现与快速试验。

## 特性

- 简洁可复现的实现
- 支持训练与评估的实验脚本和 notebook
- 适合做基线比较和快速原型验证

## 快速开始

1. 克隆仓库并进入目录：

```bash
git clone <repo-url>
cd nf_proj
```

2. 创建虚拟环境并安装依赖（示例）：

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

如果仓库没有提供 `requirements.txt`，请根据需要安装 `numpy`, `torch` 等依赖。

## 使用示例

- 在 Jupyter 中打开并运行演示 notebook：

```bash
jupyter notebook n-hits.ipynb
```

- 在 Python 中按需导入并运行（示例）：

```python
# 示例：根据项目内实际脚本调整
# from train import main
# main(...)
```

## 贡献

欢迎提交 issue 和 pull request。建议在贡献前先在 issue 中描述你的改动计划以便讨论。

## 许可证

请在仓库根目录添加 LICENSE 文件以明确许可信息（例如 MIT、Apache-2.0 等）。
