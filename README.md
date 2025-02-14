## 项目结构

project/
├── 01_NGram_BoW/
│ └── BoW.ipynb # 词袋模型实现
├── 02_Word2Vec/
│ ├── CBOW.ipynb # CBOW 模型实现
│ ├── SkipGram.ipynb # Skip-Gram 使用 Linear 层实现
│ └── SkipGram-Embedding.ipynb # Skip-Gram 使用 Embedding 层实现
├── 04_Seq2Seq/
│ └── Seq2Seq.ipynb # 序列到序列模型实现
├── 05_Attention/
│ └── Seq2Seq_with_Attention.ipynb # 带注意力机制的序列到序列模型
└── .gitignore # Git 忽略文件配置

## 采用 conda 初始化环境

```bash
conda create -n gptlearn python=3.10
```

## 激活环境

```bash
conda activate gptlearn
```

## 采用 conda 安装 pytorch 依赖

```bash
conda install pytorch torchvision torchaudio cpuonly -c pytorch
```

## 采用 conda 安装 jupyter

```bash
conda install jupyter
```

## 采用 conda 安装 matplotlib

```bash
conda install matplotlib
```

## 采用 jupter notebook 运行代码

```bash
jupyter notebook
```
