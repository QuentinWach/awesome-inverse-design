# Awesome Inverse Design [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
> A curated list for engineers, physicists and hobbyists interested in inverse design of photonic devices.

## FDTD Engines
- [MEEP](https://github.com/NanoComp/meep) - MIT's open-source FDTD engine with adjoint solver, the most widely used in photonics.
- [Tidy3D](https://github.com/flexcompute/tidy3d) - Cloud-based FDTD with built-in adjoint optimization and mode solver. *(Flexcompute; originated in Fan Group, Stanford)*
- [FDTDx](https://github.com/ymahlau/fdtdx) - GPU-accelerated, differentiable FDTD with memory-efficient autodiff for 3D inverse design with Jax.
- [BEAMZ](https://github.com/QuentinWach/beamz) - GPU-accelerated, general FDTD and gradient-based optimization with JAX for photonic chip designers.
- [fdtdz](https://github.com/spinsphotonics/fdtdz) - GPU-accelerated FDTD in JAX. *(SPINS Photonics)*
- [Khronos.jl](https://github.com/facebookresearch/Khronos.jl) - Alec Hammond's new Julia FDTD solver for photonics. *(Meta Research)*
- [Luminescent.jl](https://github.com/paulxshen/Luminescent.jl) - GPU + autodiff FDTD in Julia for photonics, acoustics, and RF.

## FDFD & Frequency Domain

> ***Fan Group, Stanford:***
- [Ceviche](https://github.com/fancompute/ceviche) - Differentiable FDFD and FDTD simulator with autograd for gradient-based inverse design.
- [Angler](https://github.com/fancompute/angler) - Frequency-domain electromagnetic simulator with adjoint-based optimization.

> ***Vuckovic Group, Stanford:***
- [SPINS-B](https://github.com/stanfordnqp/spins-b) - Gradient-based photonic optimization library using FDFD.


## Other Inverse Design & Optimization Tools
- [EMopt](https://github.com/anstmichaels/emopt) - Shape and topology optimization for 2D/3D EM structures using the adjoint method.
- [PhoTOS](https://github.com/aadityacs/PhoTOS) - Topology optimization with shape libraries and VAE-based feature mapping for fabrication-aware photonic design.
- [NIDN](https://github.com/esa/NIDN) - Neural inverse design of nanostructures with PyTorch, RCWA and FDTD forward models. *(ESA)*
- [lumopt](https://github.com/chriskeraly/lumopt) - Adjoint optimization wrapper for Lumerical FDTD.
- [PreFab](https://github.com/PreFab-Photonics/PreFab) - Deep learning model predicting post-fabrication structures from GDS layouts for fab-aware optimization.


## Tutorials & Challenges
- [Inverse Design Workshop](https://github.com/fancompute/workshop-invdesign) - Hands-on workshop materials. *(Fan Group, Stanford)*
- [Ceviche Challenges](https://github.com/google/ceviche-challenges) - Suite of photonic inverse design challenge problems. *(Google)*
- [invrs-io Gym](https://github.com/invrs-io/gym) - Collection of nanophotonic inverse design challenges with common interface.
- [Inverse Design Tutorial (Christiansen & Sigmund, 2021)](https://doi.org/10.1364/JOSAB.406048) - Comprehensive tutorial on topology optimization for photonics.
- [DTU TopOpt MATLAB Codes](https://www.topopt.mek.dtu.dk/Apps-and-software/Matlab-codes-electromagnetic-topology-optimization) - Companion MATLAB/COMSOL code for the Christiansen & Sigmund tutorial.
- [Tidy3D Inverse Design Lectures](https://www.flexcompute.com/tidy3d/learning-center/inverse-design/) - Free video lecture series on inverse design methods.
- [Tidy3D Example Library](https://www.flexcompute.com/tidy3d/learning-center/example-library) - Collection of simulation and optimization examples.
- [MEEP Adjoint Optimization Notebooks](https://github.com/NanoComp/meep/tree/master/python/examples/adjoint_optimization) - Jupyter notebooks teaching MEEP's adjoint solver.
- [A Newcomer's Guide to DL for Inverse Design (Khaireh-Walieh et al., 2023)](https://doi.org/10.1515/nanoph-2023-0527) - Practical tutorial with companion Python notebooks.
- [Validation and Characterization of Algorithms for Photonics Inverse Design (Chen et al., 2024)](https://doi.org/10.1364/JOSAB.506412) - Reproducible multi-solver benchmark suite.

## Key Papers & Reviews
- [Jensen & Sigmund (2011)](https://doi.org/10.1002/lpor.201000014) - "Topology optimization for nano-photonics." *Laser Photonics Rev.*
- [Piggott et al. (2015)](https://doi.org/10.1038/nphoton.2015.69) - First experimental inverse-designed silicon photonic device. *Nature Photonics*
- [Molesky et al. (2018)](https://doi.org/10.1038/s41566-018-0246-9) - "Inverse design in nanophotonics." *Nature Photonics*
- [Peurifoy et al. (2018)](https://doi.org/10.1126/sciadv.aar4206) - Neural networks for nanophotonic inverse design. *Science Advances*
- [Hughes et al. (2019)](https://doi.org/10.1021/acsphotonics.9b01238) - Forward-mode differentiation of Maxwell's equations. *ACS Photonics*
- [Christiansen & Sigmund (2021)](https://doi.org/10.1364/JOSAB.406048) - Tutorial on topology optimization for photonics. *JOSA B*
- [Jiang, Chen & Fan (2021)](https://doi.org/10.1038/s41578-020-00260-1) - DNNs for evaluation and design of photonic devices. *Nature Reviews Materials*
- [Ma et al. (2021)](https://doi.org/10.1038/s41566-020-0685-y) - Deep learning for design of photonic structures. *Nature Photonics*

## Also See
- [Optics & Photonics](https://github.com/Cherish0925/optics-photonics) - English/Chinese software directory comparing physical methods, licenses, native APIs and compute requirements, with documentation for electromagnetic and differentiable optical solvers.
- [Awesome Photonics](https://github.com/joamatab/awesome_photonics) - Comprehensive list of open-source photonics projects.
- [Awesome PDA](https://github.com/zhengqigao/Awesome-PDA) - Papers on photonic design automation.

<details><summary>More tools (less actively maintained or more niche)</summary>

- [GRCWA](https://github.com/weiliangjinca/grcwa) - autoGradable RCWA. *(Stanford)*
- [jaxwell](https://github.com/stanfordnqp/jaxwell) - JAX-based FDFD solver. *(Vuckovic Group, Stanford)*
- [fdtd](https://github.com/flaport/fdtd) - Python FDTD with PyTorch backend.
- [wavetorch](https://github.com/fancompute/wavetorch) - Wave equation backpropagation in PyTorch. *(Fan Group)*
- [pjz](https://github.com/spinsphotonics/pjz) - JAX workflow framework on top of fdtdz.
- [DL4TO](https://github.com/dl4to/dl4to) - Deep learning for 3D topology optimization in PyTorch.
- [OpenEMS](https://github.com/thliebig/openEMS) - EC-FDTD electromagnetic solver.
- [InverseBench](https://github.com/devzhk/InverseBench) - Benchmarks for diffusion-based scientific inverse problems. *(ICLR 2025)*
- [TMM](https://github.com/sbyrnes321/tmm) - Transfer matrix method for thin/thick multilayer film optics.

## RCWA & Transfer Matrix
- [S4](https://github.com/victorliu/S4) - Rigorous coupled-wave analysis (RCWA) for layered periodic structures. *(Fan Group, Stanford)*
- [FMMAX](https://github.com/facebookresearch/fmmax) - Fourier Modal Method in JAX with Brillouin zone integration. *(Meta Research)*
- [Meent](https://github.com/kc-ml2/meent) - RCWA with NumPy, JAX, and PyTorch backends for differentiable optimization.
- [torcwa](https://github.com/kch3782/torcwa) - GPU-accelerated RCWA with PyTorch automatic differentiation.
- [tmmax](https://github.com/bahremsd/tmmax) - GPU-accelerated transfer matrix method in JAX.

## Mode Solvers & Photonic Crystals
- [MPB](https://github.com/NanoComp/mpb) - MIT Photonic-Bands: Bloch-mode solver for photonic band structures in periodic media.
- [Legume](https://github.com/fancompute/legume) - Guided-mode expansion for photonic crystal slabs with automatic differentiation. *(Fan Group, Stanford)*
- [femwell](https://github.com/HelgeGehring/femwell) - FEM waveguide mode solver for photonics.
- [meow](https://github.com/flaport/meow) - Eigenmode expansion (EME) solver for photonic waveguides.

</details>
