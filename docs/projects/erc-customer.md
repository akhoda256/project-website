---
title: ERC CUSTOMER
parent: Projects
---

# ERC CUSTOMER: Customizable Embedded Real-Time Systems
(Supported by ERC advanced grant)

---
## Motivation
Today, many industrial products are defined by software and therefore customizable: their functionalities as well as economical values implemented by software can be modified and extended by dynamic software updates on demand. This trend towards customizable products is rapidly expanding into all domains of IT, including Embedded Real-Time Systems (ERTS) deployed in Cyber-Physical Systems such as cars, medical devices etc. However, the current state-of-practice in safety-critical systems allows hardly any modifications once they are put in operation. The lack of techniques to preserve crucial safety conditions for customizable systems severely restricts the benefits of advances in software-defined systems engineering.

## Goals
CUSTOMER is to provide the missing paradigm and technology for designing, building and updating ERTS after deployment – subject to stringent timing constraints, dynamic workloads, and limited resources on complex platforms. CUSTOMER explores research areas crossing two fields: Real-Time Computing and Formal Verification to develop the key techniques enabling (1) designing systems that allow for dynamic updates of ERTS in the field, (2) incremental updates over the products life time and (3) safe updates by verification to avoid updates that may compromise system safety.

# Current work
CUSTOMER i is currently developing the MIMOS tool chain, based on a timed version of Kahn Process Networks, supporting (1) Modelling/Design (composable embedded systems), (2) Code generation for simulation on the abstract model of a target platform, Scheduling and timing analysis, (3) Code generation for final implementation/deployment on the target platform, and (4) finally Model-based Dynamic Updates, which is essentially to "incrementally" repeat step (1)-(3) for the case of composable systems.

# Team
- Gaoyang Dai
- Susanne Graf
- Nikolaus Huber
- Behnam Khodabandeloo
- Morteza Mohaqeqi
- Petros Voudouris
- Xu Jiang
- Wang Yi (PI)

## Software tools
- DATooR: a scheduling and analysis tool for real-time systems (under construction)
- MIMOS: a design and programming environment for embedded and real-time systems (under construction)

## Publications
- Gaoyang Dai, Morteza Mohaqeqi, Petros Voudouris, Wang Yi: Response-Time Analysis of Limited-Preemptive Sporadic DAG Tasks, Proc. of EMSFOT 2022.
- Morteza Mohaqeqi, Gaoyang Dai, Behnam Khodabandeloo, Petros Voudouris and Wang Yi: A Scheduling and Analysis Tool for Parallel Real-Time Applications on Multicore Platforms. RTSS@work, RTSS 2022.
- Morteza Mohaqeqi, Gaoyang Dai, Wang Yi: Counting Priority Inversions: Computing Maximum Additional Core Requests of DAG Tasks. DATE 2022: 1281-1286
- Yang Wang, Xu Jiang, Nan Guan, Mingsong Lv, Dong Ji, Wang Yi: Scheduling and analysis of real-time tasks with parallel critical sections. DAC 2022: 1255-1260
- Yue Tang, Nan Guan, Wang Yi: Real-Time Task Models. Handbook of Real-Time Computing 2022: 469-487
- Wang Yi, Morteza Meqeqi, Susanne Graf. MIMOS: A Deterministic Model for the Design and Update of Real-Time Systems, arXiv 2020. (pdf), COORDINATION 2022.
- Gaoyang Dai, Morteza Mohaqeqi, and Wang Yi. Timing-Anomaly Free Dynamic Scheduling of Periodic DAG Tasks with Non-Preemptive Nodes. RTCSA, 2021.
- Xinyang Dong, Gang Chen, Mingsong Lv, Weiguang Pang, Wang Yi: Flexible Mixed-Criticality Scheduling with Dynamic Slack Management. J. Circuits Syst. Comput. 30(10): (2021)
- He Du, Xu Jiang, Mingsong Lv, Tao Yang, Wang Yi: Scheduling and analysis of real-time task graph models with nested locks. J. Syst. Archit. 114: 101969 (2021)
- Jinghao Sun, Nan Guan, Rongxiao Shi, Guozhen Tan, Wang Yi: Schedulability Analysis for Timed Automata With Tasks. ACM Trans. Embed. Comput. Syst. 20(5s): 89:1-89:26 (2021)
- Yang Wang, Xu Jiang, Nan Guan, Zhishan Guo, Xue Liu, Wang Yi: Partitioning-Based Scheduling of OpenMP Task Systems With Tied Tasks. IEEE Trans. Parallel Distributed Syst. 32(6): 1322-1339 (2021)
- Ernst-Rüdiger Olderog, Bernhard Steffen, Wang Yi: Model Checking, Synthesis, and Learning. Model Checking, Synthesis, and Learning 2021: 1-7
- Jakaria Abdullah, Wang Yi: Cause-Effect Reaction Latency in Real-Time Systems. Model Checking, Synthesis, and Learning 2021: 41-56
- Yue Tang, Nan Guan, Zhiwei Feng, Xu Jiang, Wang Yi: Response Time Analysis of Lazy Round Robin. DATE 2021: 258-263
- Jinghao Sun, Nan Guan, Feng Li, Huimin Gao, Chang Shi, Wang Yi: Real-Time Scheduling and Analysis of OpenMP DAG Tasks Supporting Nested Parallelism. IEEE Trans. Computers 69(9): 1335-1348 (2020)
- Gang Chen, Nan Guan, Kai Huang, Wang Yi: Fault-tolerant real-time tasks scheduling with dynamic fault handling. J. Syst. Archit. 102 (2020)
- Zhiwei Feng, Nan Guan, Mingsong Lv, Wenchen Liu, Qingxu Deng, Xue Liu, Wang Yi: Efficient drone hijacking detection using two-step GA-XGBoost. J. Syst. Archit. 103: 101694 (2020)
- Jinghao Sun, Nan Guan, Shuangshuang Chang, Feng Li, Qingxu Deng, Wang Yi: Capacity Augmentation Function for Real Time Parallel Tasks With Constrained Deadlines Under GEDF Scheduling. IEEE Trans. Comput. Aided Des. Integr. Circuits Syst. 39(12): 4537-4548 (2020)
- Jinghao Sun, Feng Li, Nan Guan, Wentao Zhu, Minjie Xiang, Zhishan Guo, Wang Yi: On Computing Exact WCRT for DAG Tasks†. DAC 2020: 1-6
- Jinghao Sun, Yaoyao Chi, Tianfei Xu, Lei Cao, Nan Guan, Zhishan Guo, Wang Yi: On the Volume Calculation for Conditional DAG Tasks: Hardness and Algorithms*. DATE 2020: 204-209
- Wang Yi: Design and Dynamic Update of Real-Time Systems. RTSS 2019: 1-3

## Funding
ERC advanced grant
Start date: 2019-10-01, End date: 2024-09-30 (extended)

