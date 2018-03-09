Vehicle-to-everything (V2X) communications, enabled by cellular device-to-device (D2D) links, have recently drawn much attention due to its potential to improve traffic safety, efficiency, and comfort. In this context, however, intracell interference combined with demanding latency and reliability requirements of safety vehicular users (V-UEs) are challenging issues. In this paper, we study a resource allocation problem among safety V-UEs, non-safety V-UEs, and conventional cellular UEs (C-UEs). Firstly, the resource allocation problem is formulated as a three-dimensional matching problem, where the objective is to maximize the total throughput of non-safety V-UEs on condition of satisfying the requirements on C-UEs and on safety V-UEs. Due to its NP-hardness, we then exploit hypergraph theory and propose a local search based approximation algorithm to solve it. Through simulation results, we show that the proposed algorithm outperforms the existing scheme in terms of both throughput performance and computational complexity.


由于蜂窝设备到设备（D2D）链路的支持，车对一切（V2X）通信由于其提高交通安全性，效率和舒适性的潜力而近来备受关注。然而，在这种情况下，小区内干扰加上安全车载用户（V-UE）的严格的等待时间和可靠性要求是具有挑战性的问题。在本文中，我们研究安全V-UE，非安全V-UE和传统蜂窝UE（C-UE）之间的资源分配问题。首先，将资源分配问题表述为三维匹配问题，其目标是在满足C-UE和安全V-UE的要求的条件下最大化非安全V-UE的总吞吐量。由于其NP硬度，我们然后利用超图理论，并提出一个局部搜索的近似算法来解决它。通过仿真结果表明，所提出的算法在吞吐量性能和计算复杂度方面均优于现有方案。



In this paper, we investigate the methods for multidimensional matching problems. Most existing methods fall into two categories: 1) transform the multidimensional matching problem into the two-dimensional matching problems, i.e., the IHM in [11], the pairing algorithm in [12], and the parallel implementation of Hopcroft-Karp in [13]; 2) construct the hypergraph model [14]- [17] ork-set packing problem [19]-[22]. Among the methods applied in the latter, local search has been used successfully to solve such computationally hard optimization problem and studied in many research domains [23]- [25].


在本文中，我们研究了多维匹配问题的方法。 大多数现有的方法分为两类：1）将多维匹配问题转化为二维匹配问题，即[11]中的IHM，[12]中的配对算法以及Hopcroft-Karp的并行实现[13]; 2）构造超图模型[14] - [17] ork-set打包问题[19] - [22]。 在后者的应用方法中，局部搜索已被成功地用来解决这种计算困难的优化问题，并在许多研究领域进行了研究[23] - [25]。


The novelty of our work mainly lies in introducing a 3D-matching based V2X resource allocation algorithm (3DVRAA) to solve the RRM problem joint with safety V-UEs, non-safety V-UEs, and C-UEs. The main contributions of this paper are summarized as follows:

formulation of a joint RRM problem for safety V-UEs, non-safety V-UEs, and conventional C-UEs;

construction of a hypergraph model for the associated RRM problem;

proposed a 3D-matching based algorithm to solve the RRM problem;

performance evaluation of the proposed scheme with other methods.

我们工作的新颖之处主要在于引入基于3D匹配的V2X资源分配算法（3DVRAA）来解决与安全V-UE，非安全V-UE和C-UE联合的RRM问题。 本文的主要贡献归纳如下：

为安全V-UE，非安全V-UE和传统C-UE制定联合RRM问题;

为相关RRM问题构建超图模型;

提出了一种基于三维匹配的算法来解决RRM问题;

用其他方法对该方案进行绩效评估。