# Hi, I'm Yue Zhang 👋

[![GitHub followers](https://img.shields.io/github/followers/zytechnova?style=social)](https://github.com/zytechnova)

**Graduate Researcher** in High-Performance Computing  
**Focus:** GPU/CPU Parallelization | Lossless Data Compression | Heterogeneous Computing

---

## 🔬 Research Interests

- Portable parallel programming across heterogeneous architectures (GPUs, CPUs)
- Memory-bound kernel optimization
- Stream-based lossless compression algorithms
- Real-time systems and embedded computing

## 📝 Publications

**2026**
- **Yue Zhang**, Yuki Hara, Oliver Sinnen, Shinichi Yamagiwa  
  *"Parallelising Stream-Based Lossless Data Compression on GPUs and CPUs"*  
  Proceedings of the International Workshop on Big Data eXploration, Compression and Systems (BDXCS), 2026

## 💻 Technical Stack

### Parallel & High-Performance Computing
![OpenCL](https://img.shields.io/badge/OpenCL-000000?style=for-the-badge&logo=opencl&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![OpenMP](https://img.shields.io/badge/OpenMP-0071C5?style=for-the-badge)

### Programming Languages
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white)

### Development Tools
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### Hardware Platforms
- **NVIDIA GPUs:** RTX 4090, CUDA cores
- **Intel GPUs:** Arc A770, Xe cores  
- **Qualcomm SoCs:** Adreno X1-85
- **Multi-core CPUs:** AMD Ryzen, Intel Core

## 🚀 Featured Projects

### 🔥 Portable ASE Compression Parallelization
*OpenCL implementation achieving 1.82 GB/s decompression throughput on NVIDIA RTX 4090*

**Key achievements:**
- Cross-platform compatibility across NVIDIA, Intel, AMD, and Qualcomm architectures
- 12.3× speedup over sequential baseline on CPU
- 2× improvement over prior CPU-parallel implementations
- Published at BDXCS 2026

**Technical highlights:**
- Byte-aligned bit encoding for memory coalescing
- Double-buffered pipeline architecture
- Unified parameter set achieving 37-48% peak memory bandwidth utilization

> 📝 Main implementation in private collaboration repository. Selected artifacts and evaluation results available upon request.

---

### 🎮 Pokemon Showdown Expert Agent
*Rule-based AI system for competitive Pokemon battles (COMPSYS726)*

**Design approach:**
- Expert system architecture with transparent decision logic
- Layered priority rules combining mandatory constraints and tactical heuristics
- Deterministic action selection with failure analysis support

**Features:**
- State extraction and candidate generation pipeline
- Type effectiveness and tempo signal evaluation
- Reproducible results with CSV-based evaluation framework

[View Repository →](https://github.com/zytechnova/compsys726-showdown-expert-agent)

---

### 🤖 Pokemon Showdown RL Environment
*Custom reinforcement learning environment with Rainbow DQN agent (COMPSYS726)*

**Environment design:**
- Compact 23-D observation space capturing board state
- Two-action intent interface (attack/switch) with legal-action controller
- Reward shaping based on board-value differential

**Results:**
- Trained Rainbow DQN agent on episodic MDP formulation
- Evaluation protocol: 100 battles per seed against max-damage expert
- Ablation studies comparing Rainbow vs vanilla DQN and controller complexity

[View Repository →](https://github.com/zytechnova/compsys726-showdown-rl-env)

---

### ⚡ Triton-Accelerated Canny Edge Detection
*GPU-optimized edge detection using custom Triton kernels*

**Implementation:**
- Custom GPU kernel implementations in Triton
- Pure PyTorch baseline for comparison
- Comprehensive benchmarking framework

**Features:**
- High-performance GPU acceleration
- Side-by-side visualization and performance analysis
- Modular processing pipeline

[View Repository →](https://github.com/zytechnova/triton-canny-edge-detection)

---

## 📊 GitHub Activity

<div align="center">

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=zytechnova&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=zytechnova&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

## 🔍 Current Focus

Working on portable parallelization strategies for stream-based algorithms across heterogeneous architectures, with emphasis on achieving sustained throughput while preserving algorithmic effectiveness on real-world datasets.

---

💡 *Interested in collaborations on HPC, GPU computing, and parallel algorithms*