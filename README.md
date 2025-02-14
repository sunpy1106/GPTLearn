## 项目结构

```
.
├── 01_NGram_BoW
│   ├── BiGram.ipynb
│   └── BoW.ipynb
├── 02_Word2Vec
│   ├── CBOW.ipynb
│   ├── SkipGram-Enbedding.ipynb
│   └── SkipGram.ipynb
├── 03_NPLM
│   ├── NPLM.ipynb
│   └── RNN.ipynb
├── 04_Seq2Seq
│   └── Seq2Seq.ipynb
├── 05_Attention
│   ├── Dot-Product_Attention.ipynb
│   ├── Multiheads-Self-Attention.ipynb
│   ├── QKV.ipynb
│   ├── Scaled_Dot-Product_Attention.ipynb
│   ├── Self-Attention.ipynb
│   └── Seq2Seq_with_Attention.ipynb
├── 06_Transformer
│   └── Transformer.ipynb
├── 07_GPT
│   ├── GPT.ipynb
│   ├── Transformer_with_GreedyDecoder.ipynb
│   ├── WikiGPT.ipynb
│   └── lang.txt
├── 08_ChatGPT
│   ├── GPT_Model.py
│   ├── Pretrain_ChatGPT.ipynb
│   ├── RLHF_Reward_ChatGPT.py
│   ├── SelfTrain_ChatGPT.ipynb
│   └── chat.txt
├── 09_OpenAI_API
│   ├── ChatBot.ipynb
│   └── ChatBot.py
└── README.md
```

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
