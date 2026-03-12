# SC-Net: 结构即计算 —— 一个开放的低能耗AI基础设施工程

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

&gt; 核心直觉：**智能源于结构对信息的定向传导与精准过滤**，而非迭代生成式计算。

## 论文

- **Zenodo DOI**:10.5281/zenodo.18889585
- **PDF**: https://doi.org/10.5281/zenodo.18889585

## 核心设计

| 组件 | 功能 | 生物启发 |
|------|------|---------|
| 稀疏固定骨干(SFB) | 预设拓扑，权重冻结 | 果蝇固定连接组 |
| 门控高阶关联过滤器(GHOF) | 动态抑制冗余 | 微管阈值放行 |
| 快慢分离学习模块(FSLM) | 推理与学习速率解耦 | 神经异步时钟 |

## 许可证与治理

- **代码**：GNU AGPL-3.0（网络服务强制开源）
- **论文/文档**：CC BY-SA 4.0
- **商标**："SC-Net"及"结构计算"保留所有权利
- **治理**：BDFL（仁慈独裁者）模式

我们**欢迎商业应用**，但**坚决反对闭源吃独食**。

## 当前状态

- [x] 理论框架与架构设计
- [x] 进化机制算法实现
- [x] CIFAR-10初步验证（8.3%损失降低）
- [ ] GLUE任务验证（进行中，预计2026 Q2）
- [ ] 大规模实验（30B+，计划2026 Q4）
- [ ] 完整代码开源（即将发布）

## 参与方式

| 角色 | 行动 | 联系 |
|------|------|------|
| 研究者 | 验证实验、深化理论 | lizhengda@live.cn |
| 开发者 | 代码实现、硬件优化 | GitHub Issues |
| 商业公司 | 产品开发、生态共建 | lizhengda@live.cn "[商业合作]" |

---

**作者**：李政达（独立研究者，上海）  
**邮箱**：lizhengda@live.cn  
**愿景**：让高效AI成为公共基础设施，而非算力巨头的私有领地

## 引用

```bibtex
@software{scnet2026,
  author = {李政达 (Li Zhengda)},
  title = {SC-Net: Structure as Computation for Low-Energy AI},
  year = {2026},
  url = {https://github.com/Canplank/sc-net},
  doi = {10.5281/zenodo.18889585}
}
