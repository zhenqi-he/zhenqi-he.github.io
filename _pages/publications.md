---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<div class="text-justify">


<div class="w3-card-4 w3-margin w3-Dark Gray">
<div class="w3-container w3-Dark Gray">
<h2><b> TransNuSeg: A Lightweight Multi-Task Transformer for Nuclei Segmentation </b><i> MICCAI 2023</i> </h2>
<div>
<img src="https://zhenqi-he.github.io/images/TransNuSeg_Model.png" alt="TransNuSeg Model Architecture" class="responsivepost">
</div>

<div class="w3-container">
<p>This paper proposes a lightweight multi-task framework for nuclei segmentation, namely TransNuSeg, as the first attempt at an entirely Swin-Transformer driven architecture. Innovatively, to alleviate the prediction inconsistency between branches, we propose a self-distillation loss that regulates the consistency between the nuclei decoder and normal edge decoder. And an innovative attention-sharing scheme that shares attention heads amongst all decoders is employed to leverage the high correlation between tasks. [<a href="https://zhenqi-he.github.io/files/TransNuSeg A Lightweight Multi-task Transformer for Nuclei Segmentation.pdf"> paper</a>] [ <a href="https://github.com/zhenqi-he/transnuseg"> code</a> ]</p>
</div>


<div class="w3-card-4 w3-margin w3-Dark Gray">
<div class="w3-container w3-Dark Gray">
<h2><b>Artifact Restoration in Histology Images with Diffusion Probabilistic Models </b><i> MICCAI 2023</i> </h2>
<div>
<img src="https://zhenqi-he.github.io/images/artifusion.png" alt="Reconstructed Visualized Results" class="responsivepost">
</div>

<div class="w3-container">
<p>This is the first attempt at a denoising diffusion probabilistic model for histological artifact restoration, called ArtiFusion. Specifically, ArtiFusion formulates the artifact region restoration as a gradual denoising process, and its training relies solely on artifact-free images to simplify the training complexity. Furthermore, to capture local-global correlations in the regional artifact restoration, a novel Swin-Transformer denoising architecture is designed, along with a time token scheme. Our extensive evaluations demonstrate the effectiveness of ArtiFusion as a pre-processing method for histology analysis, which can successfully preserve the tissue structures and stain style in artifact-free regions during the restoration.[<a href="https://zhenqi-he.github.io/files/Artifact Restoration in Histology Images with Diffusion Probabilistic Models.pdf"> paper</a>] [ <a href="https://github.com/zhenqi-he/ArtiFusion"> code</a> ]</p>
</div>

<div class="w3-card-4 w3-margin w3-Dark Gray">
<div class="w3-container w3-Dark Gray">
<h2><b> LatentArtiFusion: an Effective and Efficient Histological Artifacts Restoration Framework </b><i> DGM4MICCAI 2024</i> </h2>
<div>
<img src="https://zhenqi-he.github.io/images/LatentArtifusion.png" alt="LatentArtiFusion Model Architecture" class="responsivepost">
</div>

<div class="w3-container">
<p>In this paper, we propose a novel framework, namely LatentArtiFusion, which leverages the latent diffusion model (LDM) to reconstruct histological artifacts with high performance and computational efficiency. Unlike traditional pixel-level diffusion frameworks, LatentArtiFusion executes the restoration process in a lower-dimensional latent space, significantly improving computational efficiency. Through extensive experiments on real-world histology datasets, LatentArtiFusion demonstrates remarkable speed, outperforming state-of-the-art pixel-level diffusion frameworks by more than 30×.  [<a href="https://github.com/bugs-creator/LatentArtiFusion"> code</a>]</p>
</div>
</div>
