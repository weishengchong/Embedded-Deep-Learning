Nvidia Benchmarking
--------------------
Simple benchmarking of public open-source implementations of caffe. A summary is provided in the section below.

Machine: 6-core Intel Xeon E5-2620 v3 CPU @ 2.4GHz + NVIDIA Titan X + Ubuntu 14.04.03 LTS
Jetson: Nvidia TX1 + Ubuntu 14.04.1 LTS

**AlexNet**

`Batch Size: 1`

| Network: Alexnet           | Tegra X1 (FP32) | Tegra X1 (FP16) | Titan X (FP32) |
| -------------------------- |:---------------:|:---------------:|:--------------:|
| Average Forward Pass (ms)  | 21.9            | 15.4            | 2.5            |
| Average Forward Pass (fps) | 45.7            | 65.1            | 408.2          |
| Memory (Mbytes)            | 1372            | 930             |                |
| GPU Utilization Average    | 97%             | 32%             |                |
| GPU Frequency (MHz)        | 691             | 691             |                |

`Batch Size: 64`

| Network: Alexnet           | Tegra X1 (FP32) | Tegra X1 (FP16) | Titan X (FP32) |
| -------------------------- |:---------------:|:---------------:|:--------------:|
| Average Forward Pass (ms)  | 501.2           | 252.8           | 23.4           |
| Average Forward Pass (fps) | 127.7           | 253.1           | 2732.7         |
| Memory (Mbytes)            | 2679            | 972             |                |
| GPU Utilization Average    | 99%             | 99%             |                |
| GPU Frequency (MHz)        | 691             | 691             |                |

`Batch Size: 128`

| Network: Alexnet           | Tegra X1 (FP32) | Tegra X1 (FP16) | Titan X (FP32) |
| -------------------------- |:---------------:|:---------------:| :-------------:|
| Average Forward Pass (ms)  | 834.2           | 496.6           | 40.3           |
| Average Forward Pass (fps) | 153.4           | 257.8           | 3178.5         |
| Memory (Mbytes)            | 2886            | 1146            |                |
| GPU Utilization Average    | 99%             | 99%             |                |
| GPU Frequency (MHz)        | 691             | 691             |                |

