# CubeGS-Cube-wise-Motion-Residual-Prediction-for-Gaussian-Splatting-Streaming
Official repository for ACM MMSys 2026 CubeGS paper. <br>

| [Paper](https://dl.acm.org/doi/10.1145/3793853.3795750)  |<br>

Official repository for the paper CubeGS: Cube-wise Motion Residual Prediction for Gaussian Splatting Streaming <br>
**Accepted by ACM Multimedia Systems Conference 2026 (MMSys'26)** <br>

<p float="middle">
  <img src="assets/teaser.png" width="99%" />
</p>

## Code Availability Notice
Due to licensing issues, we are unable to release the source code publicly.

The authors, however, remain open to technical discussions and are willing to provide clarifications regarding the implementation through academic or professional exchange.

## Citation
```
@inproceedings{10.1145/3793853.3795750,
author = {Naqvi, Syed Ali John and Wang, Mea and Halepovic, Emir},
title = {CubeGS: Cube-wise Motion Residual Prediction for Gaussian Splatting Streaming},
year = {2026},
isbn = {9798400724817},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3793853.3795750},
doi = {10.1145/3793853.3795750},
abstract = {Volumetric video promises rich 6DoF experiences, but current 3D Gaussian Splatting (3DGS) pipelines are inefficient for dynamic content: each frame is trained independently, ignoring temporal redundancy, which leads to high storage and bandwidth requirements. In this paper, we propose CubeGS, a lightweight, streaming-oriented compression mechanism for 3DGS video that preserves visual fidelity and rendering efficiency of 3DGS while substantially reducing the data footprint. CubeGS organizes frames using a Group-of-Pictures (GoP) structure, introducing reference frames and predictive frames within dynamic 3DGS sequences. Central to our design is cube-wise motion residual capturing, which reuses Gaussian parameters across time and encodes only localized changes in appearance and geometry. To further reduce storage and transmission cost, we integrate a modified Draco geometry encoder tailored to Gaussian parameterization. Together, these components make on-demand Gaussian Splatting streaming feasible over commercial networks with CubeGS averaging 193 Mbps for streaming a 24 fps video. CubeGS achieves approximately 7.7\texttimes{} data reduction and up to 16.9\% higher video quality compared to 3DGStream, the state-of-the-art dynamic 3DGS method. Importantly, CubeGS retains the rendering speed of 3DGS while scaling efficiently to complex dynamic scenes with much lower storage and bandwidth overhead than existing approaches.},
booktitle = {Proceedings of the ACM Multimedia Systems Conference 2026},
pages = {96–106},
numpages = {11},
keywords = {Volumetric Video, Gaussian Splatting, Inter-frame Prediction},
location = {
},
series = {MMSys '26}
}
```
