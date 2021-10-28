# Pyxis: An Open-Source Performance Dataset of Sparse Accelerators

Pyxis collects sparse accelerators and their perforamnce data. We hope this dataset is helpful for inereted researchers in the fileds of computer architecture, FPGA, systems, perforamnce and algorithm. Specifically, 
* (1) the collected acclerators may be a good refrence design for hardware related researchers,
* (2) the collected performance data serves as a large scale (73.8K) labels of graphs with various sizes and my be helpful for graph algorithm researchers.


## U250 SpMM Accelerator and Perforamnce 

* HLS tool: Vitis 2020.2
* U250 SpMM Accelerator: [Sextans-U250](https://github.com/linghaosong/Sextans/tree/hls/U250)
* Number of collected perforamnce instances: 18,459
* Runing on 2,637 sparse matrices from [SuiteSparse](https://sparse.tamu.edu)
* Files: Pyxis/perfdata/20211003_U250_binary.txt, Pyxis/perfdata/20211003_U250_real.txt.
* One line is a perforamcne instance showing 8 properties: [Matrix ID] [Row Number: M] [Column Number: K] [NNZ] [N] [Latency(ms)] [Throughput(GFLOP/s)]


## U280 SpMM Accelerator and Perforamnce 

* HLS tool: Vitis 2020.2
* U280 SpMM Accelerator: [Sextans-U280](https://github.com/linghaosong/Sextans/tree/hls/U280)
* Number of collected perforamnce instances: 18,459
* Runing on 2,637 sparse matrices from [SuiteSparse](https://sparse.tamu.edu)
* Files: Pyxis/perfdata/20211003_U280_binary.txt, Pyxis/perfdata/20211003_U280_real.txt.
* One line is a perforamcne instance showing 8 properties: [Matrix ID] [Row Number: M] [Column Number: K] [NNZ] [N] [Latency(ms)] [Throughput(GFLOP/s)]


We also collocted perfoamnce data on two GPUs.

## K80 SpMM Perforamnce 

* CUDA version: 10.2
* Number of collected perforamnce instances: 18,459
* Runing on 2,637 sparse matrices from [SuiteSparse](https://sparse.tamu.edu)
* Files: Pyxis/perfdata/20211003_K80_binary.txt, Pyxis/perfdata/20211003_K80_real.txt.
* One line is a perforamcne instance showing 8 properties: [Matrix ID] [Row Number: M] [Column Number: K] [NNZ] [N] [Latency(ms)] [Throughput(GFLOP/s)]


## V100 SpMM Perforamnce 

* CUDA version: 10.2
* Number of collected perforamnce instances: 18,459
* Runing on 2,637 sparse matrices from [SuiteSparse](https://sparse.tamu.edu)
* Files: Pyxis/perfdata/20211003_V100_binary.txt, Pyxis/perfdata/20211003_V100_real.txt.
* One line is a perforamcne instance showing 8 properties: [Matrix ID] [Row Number: M] [Column Number: K] [NNZ] [N] [Latency(ms)] [Throughput(GFLOP/s)]


More details coming soon. 

Or you can go to [this link](https://arxiv.org/abs/2110.04280) to find details.



If you find this dataset useful, please cite:

    @misc{pyxis2021,
    Author = {Linghao Song and Yuze Chi and Jason Cong},
    Title = {Pyxis: An Open-Source Performance Dataset of Sparse Accelerators},
    Year = {2021},
    Eprint = {arXiv:2110.04280},
    }
