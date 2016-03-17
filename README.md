Nvidia Benchmarking
--------------------
Environment Setup: Nvidia Titan X + Nvidia Jetson TX1 + Ubuntu 

**AlexNet**
`Batch Size: 1`

| Network: Alexnet           |Tegra X1 (FP32) | Tegra X1 (FP16) | Titan X (FP32) |
| -------------------------- | :--------------:|:---------------:| :-------------:|
| Average Forward Pass (ms)  | 21.9            | 15.4            | 2.5            |
| Average Forward Pass (fps) | 45.7            | 65.1            | 408.2          |
| Memory (Mbytes)            | 1372            | 930             |                |
| GPU Utilization Average    | 97%             | 32%             |                |
| GPU Frequency (MHz)        | 691             | 691             |                |

| Network: Alexnet           | Batch Size | Tegra X1 (FP32) | Tegra X1 (FP16) | Titan X (FP32) |
| -------------------------- |:----------:| :--------------:|:---------------:| :-------------:|
| Average Forward Pass (ms)  | 64         | 501.2           | 252.8           | 23.4           |
| Average Forward Pass (fps) | 64         | 127.7           | 253.1           | 2732.7         |
| Memory (Mbytes)            | 64         | 2679            | 972             |                |
| GPU Utilization Average    | 64         | 99%             | 99%             |                |
| GPU Frequency (MHz)        | 64         | 691             | 691             |                |

| Network: Alexnet           | Batch Size | Tegra X1 (FP32) | Tegra X1 (FP16) | Titan X (FP32) |
| -------------------------- |:----------:| :--------------:|:---------------:| :-------------:|
| Average Forward Pass (ms)  | 128        | 834.2           | 496.6           | 40.3           |
| Average Forward Pass (fps) | 128        | 153.4           | 257.8           | 3178.5         |
| Memory (Mbytes)            | 128        | 2886            | 1146            |                |
| GPU Utilization Average    | 128        | 99%             | 99%             |                |
| GPU Frequency (MHz)        | 128        | 691             | 691             |                |

