Nvidia Benchmarking
--------------------
Environment Setup: Nvidia Titan X + Nvidia Jetson TX1 + Ubuntu 

AlexNet

| Network: Alexnet           | Batch Size | Tegra X1 (FP32) | Tegra X1 (FP16) | Titan X (FP32) |
| -------------------------- |:----------:| ---------------:|:---------------:| --------------:|
| Average Forward Pass (ms)  | 1          | 21.86           | 15.37           | 2.45           |
| Average Forward Pass (fps) | 1          | 45.7            | 65.1            | 408.2          |
| Memory (Mbytes)            | 1          | 1372            | 930             |                |
| GPU Utilization Average    | 1          | 97%             | 32%             |                |
| GPU Frequency (MHz)        | 1          | 691             | 691             |                |
| Average Forward Pass (ms)  | 64         | 21.86           | 15.37           | 2.45          |
| Average Forward Pass (fps) | 64         | 45.7            | 65.1            | 408.2         |
| Memory (Mbytes)            | 64         | 1372            | 930             |               |
| GPU Utilization Average    | 64         | 97%             | 32%             |               |
| GPU Frequency (MHz)        | 64         | 691             | 691             |               |


