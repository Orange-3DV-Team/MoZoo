# MoZoo:Towards Unleashing Video Diffusion Power in Animal Fur and Muscle Simulation

<p align="center">
    <a href=""><img src='https://img.shields.io/badge/arXiv-MoZoo-red?logo=arxiv' alt='Paper PDF'></a>
    <a href='https://orange-3dv-team.github.io/MoZoo/'><img src='https://img.shields.io/badge/Project_Page-MoZoo-green' alt='Project Page'></a>
    <a href=''><img src='https://img.shields.io/badge/Huggingface-Online_Demo-yellow' alt='Online Demo'></a>
    <!-- <a href='https://colab.research.google.com/drive/1LtnxgBU7k4gyymOWuonpOxjatdJ7AI8z?usp=sharing'><img src='https://img.shields.io/badge/Colab_Demo-Director3D-yellow?logo=googlecolab' alt='Project Page'></a> -->
</p>

<div align="center">
  <video src="https://github.com/user-attachments/assets/07bc481c-2eda-4c0d-8618-9ab2a0f9a533" width="100%" autoplay loop muted playsinline></video>
</div>



**TL;DR:** MoZoo synthesizes high-fidelity animal dynamics from coarse meshes using Role-Aware RoPE and Asymmetric Decoupled Attention, achieving superior fur and muscle simulation across diverse species.

## 📖 Abstract

The creation of cinematic-quality animal effects necessitates the precise modeling of muscle and fur dynamics, a process that remains both labor-intensive and computationally expensive within traditional production workflows. While generative diffusion models have shown promise in diverse artistic workflows, their capacity for high-fidelity animal simulation remains largely unexploited. We present <strong>MoZoo</strong>, a generative dynamics solver that bypasses conventional refinement to synthesize high-fidelity animal videos from coarse meshes under multimodal guidance. We propose <strong>Role-Aware RoPE (RAR-RoPE)</strong> which employs role-based index remapping to synchronize motion alignment while decoupling reference information via fixed temporal offsets. Complementing this, <strong>Asymmetric Decoupled Attention</strong> partitions the latent sequence to enforce a unidirectional information flow, effectively preventing feature interference and improving computational efficiency. To address the scarcity of high-quality training data, we introduce <strong>MoZoo-Data</strong>, a synthetic-to-real pipeline that leverages a rendering engine and an inverse mapping approach to construct a large-scale dataset of paired sequences. Furthermore, we establish <strong>MoZooBench</strong>, a comprehensive benchmark with 120 mesh-video pairs. Experimental results demonstrate that <strong>MoZoo</strong> achieves high-fidelity fur simulation across diverse animal skeletons and layouts, preserving superior temporal and structural consistency.

## 🔥 News:

- [2026.4.04] Paper and local demo code released.


## 🎥 Preview

Visit our [Project Page]() to view complete demo videos and visual results.

## ⭐ Star

If you're interested in this project, please give us a Star ⭐ to receive timely open-source notifications!

## 🌟 Citation

Please leave us a star 🌟 and cite our repo if you find our work helpful.
```
@misc{liu2026mozoounleashingvideodiffusionpower,
      title={MoZoo:Unleashing Video Diffusion power in animal fur and muscle simulation}, 
      author={Dongxia Liu and Jie Ma and Xiaochen Yang and Jiancheng Zhang and Bin Xia and Zhehan Kan and Nisha Huang and Jun Liang and Wenming Yang and Jin Li},
      year={2026},
      eprint={2605.13857},
      archivePrefix={arXiv},
      primaryClass={cs.GR},
      url={https://arxiv.org/abs/2605.13857}, 
}

```
