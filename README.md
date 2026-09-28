# DivOPD: Spread Wide, Look Close for Asynchronous On-Policy Distillation of Multi-turn Agents

**Code releasing soon.**

This repository will host the official implementation of **DivOPD**, a learner-side batch-selection method for asynchronous on-policy distillation (OPD) of multi-turn agents. DivOPD spreads a fixed turn budget across more rollouts and, within each rollout, prioritizes turns with larger cumulative teacher–student disagreement. An optional teacher-intervention extension (DivOPD+R) briefly hands control to the teacher on no-progress rollouts.

Across six teacher–student settings on ALFWorld, ScienceWorld, and WebShop (1.5B–7B students), DivOPD raises the cross-setting mean peak success rate from 77.4 to 84.4 and reaches all setting-specific targets with geometric-mean speedups of 1.84× in training tokens and 1.87× in learner GPU time over vanilla OPD.

## Authors

Hanyang Wang¹, Zeyuan Liu², Zhengyu Chen², Jingqing Ruan², Chaoxu Pang², Zhongda Su², Wulin Xie³, Zhizhao Zeng², Ke Zeng², Tianxiang Zhao⁴

¹University of Chicago ²Meituan LongCat Interaction Team ³University of the Chinese Academy of Sciences ⁴The Hong Kong University of Science and Technology (Guangzhou)

## Citation

Coming soon (arXiv link will be added here).
