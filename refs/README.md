# Roadmap
## VR Protocol
### Goal
- [VRRevisted](./Viewstamped%20Replication%20Revisited.pdf)
  - [ ] 论文报告
- [ViewStamped-Replication-TLA](https://github.com/pkj415/ViewStamped-Replication-TLA)
  - [ ] 阅读报告、了解建模现状与不足
### Resources
- [Paper #74: VSR Revisited](https://www.bilibili.com/video/BV1rU4y1p7t5?p=38&share_source=copy_web)
  - 重要参考
- [Viewstamped Replication Made Famous (Zig SHOWTIME #28)](https://www.bilibili.com/video/BV1Ma411e7xC?share_source=copy_web)
  - 重要参考
- [Hacker News](https://news.ycombinator.com/item?id=29018988)
  - 关于 VSR 的讨论
- [VR@Programming Methodology Group](https://pmg.csail.mit.edu/vr/)
  > This project aims to produce a highly available and consistent service through state-machine replication. Viewstamped Replication is intended to preserve consistency despite fail-stop (crash) faults and network unavailability; the BFT project later extended this work to handle arbitrary kinds of node failures.
  - [VRPhDThesis1988](./PhD%20Thesis1988%20Viewstamped%20Replication%20for%20Highly%20Available%20Distributed%20Systems.pdf)
    - 相应的博士论文 (暂时不需要阅读)
  - [VR:PODC1988](./PODC1988%20Viewstamped%20Replication%20A%20New%20Primary%20Copy%20Method%20to%20Support%20Highly%20Available%20Distrbuted%20Systems.pdf)
    - VR 协议原始论文 (暂时不需要阅读)
  - [VR2BFT](./From%20Viewstamped%20Replication%20to%20Byzantine%20Fault%20Tolerance.pdf)
    - VR 的 Byzantine 版本; 本项目暂时不需要
  - [PaxosVRZab:TDSC2015](./TDSC2015%20Vive%20La%20Difference%20Paxos%20vs.%20Viewstamped%20Replication%20vs.%20Zab.pdf)
    - VR 与 Paxos、Zab 协议的比较; 本项目暂时不需要

## VR Impl.
  - [ ] VR 实现详细报告

## Testing VR Impl.
  - [ ] Jepsen 测试
  - [ ] 基于模型的测试
    - [ ] TLA+ for VR Impl.

## Storage Fault Model
- [PAR:FAST2018](./FAST2018%20Protocol-Aware%20Recovery%20for%20Consensus-Based%20Storage.pdf)