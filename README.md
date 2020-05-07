# A Comprehensive API for Visual Question Answering
The goal of this repository is to implement and compare different novel architectures of Visual Question Answering. Initially, several strong baselines are implemented for the **OpenEnded** visual question answering task based on the **MS COCO 2014** dataset. The implementation is mainly in **PyTorch**. 

## Results Summary Board

| Model        | All | Yes/No  | Number | Other |
| ---------- |:---------:| :-----:| :------:| :-------: |
|Baseline 3 (ResNet101, BOW300, Concat)| `[0.431]` | `[0.676]` | `[0.286]` | `[0.283]`|
|Baseline 4 (ResNet101, GloVe50, Concat)| `[0.434]` | `[0.671]` | `[0.294]` | `[0.290]`|
|Baseline 5 (ResNet101, BOW300, RNN, Concat)| `[0.443]` | `[0.675]` | `[0.300]` | `[0.303]`|
|Baseline 6 (ResNet101, BOW300, LSTM, Concat)| `[0.452]` | `[0.672]` | `[0.313]` | `[0.320]`|
|Baseline 7 (ResNet101, BOW300, LSTM, Concat, 2-Step Attention)| `[0.480]` | `[0.720]` | `[0.330]` | `[0.350]`|
|Baseline 8 (Show, Ask, Attend and Answer) | `[0.515]` | `[0.736]` | `[0.338]` | `[0.393]`|

## Presentation Roadmap