Code and Data for our CVPR 2022 paper Compressive Single-Photon 3D Cameras.

This repository builds upon the official codebase released for the CVPR 2022 paper Compressive Single-Photon 3D Cameras.

Original Work & Copyright ©
Gutierrez-Barragan, Felipe; Ingle, Atul; Seets, Trevor; Gupta, Mohit; and Velten, Andreas.

Project Page: https://pages.cs.wisc.edu/~felipe/project-pages/2022-compressive-histograms/

@InProceedings{Gutierrez-Barragan_2022_CVPR,
    author    = {Gutierrez-Barragan, Felipe and Ingle, Atul and Seets, Trevor and Gupta, Mohit and Velten, Andreas},
    title     = {Compressive Single-Photon 3D Cameras},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
    month     = {June},
    year      = {2022},
    pages     = {17854-17864}
}

This repository does not claim ownership of the original methodology or implementation.
All credits for the novel algorithmic contributions and original code belong to the authors listed above.

As an undergraduate research assistant, I worked with this codebase to:
- Understand compressive single-photon imaging and time-of-flight reconstruction.
- Run scene simulations and depth reconstruction pipelines.
- Generate coding matrices, transient histograms, depth maps, and error heatmaps.
- Experiment with multiple coding schemes (e.g., Gray, Fourier, P-Series, Truncated Fourier).
- Visualize 3D coding trajectories and reconstruction performance.
- Adapt the code to modern Python environments (fixing deprecated NumPy + Matplotlib calls).
- Troubleshoot simulation issues, IRF handling, and Poisson noise modeling.
- Produce and save publication-style figures and evaluation metrics.

This repository documents my modified version of the research code, including compatibility updates and scripts used for running simulations, generating figures, and exploring coding trade-offs.

If you use this code, or derivative versions of it, please cite the original CVPR 2022 paper above.
My modifications are strictly for academic learning, experimentation, and reproducibility.
