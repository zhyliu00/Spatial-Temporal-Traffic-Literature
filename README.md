# Spatial-Temporal-Traffic-Literature


### Spatial-Temporal Prediction
| Year        | Title   |  Target Task | Target Model     | Venue    | Paper        |
|-------|--------|--------|--------|-----------|------------|
| 2018 | **DIFFUSION CONVOLUTIONAL RECURRENT NEURAL NETWORK: DATA-DRIVEN TRAFFIC FORECASTING (DCRNN)** | Volume Prediction | Spatial: Diffusion & Graph Conv; Temporal: GRU based on Graph Conv | ICLR |  [Link](https://github.com/liyaguang/DCRNN) |
| 2018 | **Spatio-Temporal Graph Convolutional Networks: A Deep Learning Framework for Traffic Forecasting(STGCN)** | Volume Prediction | Spatial: Graph Conv; Temporal: Gated CNN | IJCAI-2018 | [Link](https://www.ijcai.org/Proceedings/2018/0505.pdf) |
|  2019 | **Graph WaveNet for Deep Spatial-Temporal Graph Modeling** | Volume Prediction |Spatial: 2 diffusion + adaptive; Temporal: gated & dilation conv  | IJCAI | [Link](https://www.ijcai.org/proceedings/2019/0264.pdf)|
|  2019|**Attention Based Spatial-Temporal Graph Convolutional Networks for Traffic Flow Forecasting(ASTGCN)**| Volume Prediction| Spatial & Temporal: Volume to conduct attention; Add feature  |AAAI|[Link](https://ojs.aaai.org/index.php/AAAI/article/download/3881/3759)|
|2020|**Adaptive Graph Convolutional Recurrent Network for Traffic Forecasting(AGCRN)**|Volume Prediction|Learnable pattern pool; Spatial: Embedding matrix mult; Temporal: GRU |NIPS|[Link](https://proceedings.neurips.cc/paper/2020/file/ce1aad92b939420fc17005e5461e6f48-Paper.pdf)|
|2020|**Spatial-Temporal Synchronous Graph Convolutional Networks: A New Framework for Spatial-Temporal Network Data Forecasting(STSGCN)**|Volume Prediction|Localized spatial-temporal graph; |AAAI|[Link](https://ojs.aaai.org/index.php/AAAI/article/download/5438/5294)|
|2021|**MDTP: A Multi-source Deep Traffic Prediction Framework over Spatio-Temporal Trajectory Data(MDTP)**|Traffic in/out prediction|Trajectory as edge and node feature; base GCN & LSTM|VLDB|[Link](http://vldb.org/pvldb/vol14/p1289-gao.pdf)|
|2021|**Dynamic and Multi-faceted Spatio-temporal Deep Learning for Traffic Speed Forecasting(DMSTGCN)**|Volume-auxiliaried speed pediction|Spatial: Tucker decomposition based dynamic matrix; Temporal: dilation & gated conv; Auxiliary data|KDD|[Link](https://dl.acm.org/doi/pdf/10.1145/3447548.3467275)|