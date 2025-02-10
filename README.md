<h1 align="center">When Pre-trained Visual Representations Fall Short: Limitations in Visuo-Motor Robot Learning</h1>


<p align="center">
<a target="_blank" href="https://tsagkas.github.io/">Nikolaos Tsagkas</a><sup>1,2</sup>,
<a target="_blank" href="linkedin.com/in/andreas-sochopoulos-abab5417a">Andreas Sochopoulos</a><sup>1</sup>,
<a target="_blank" href="https://danier97.github.io/">Duolikun Danier</a><sup>1</sup>,
<a target="_blank" href="https://christopherlu.github.io/"> Chris Xiaoxuan Lu</a><sup>3</sup>,
<a target="_blank" href="https://homepages.inf.ed.ac.uk/omacaod/">Oisin Mac Aodha</a><sup>1</sup>
</p>
<p align="center">
<sup>1</sup>University of Edinburgh,
<sup>2</sup>Edinburgh Centre for Robotics,
<sup>3</sup>UCL,
</p>
</p>

<p align="center">
  <a href="https://tsagkas.github.io/pvrobo/">Website</a> | 
  <a href="https://arxiv.org/abs/2502.03270">Paper</a>
</p>

**Code will become available early June. Until then, read the [paper](https://arxiv.org/abs/2502.03270) and browse our [project page](https://tsagkas.github.io/pvrobo/).** 

## Abstract
The integration of pre-trained visual representations (PVRs) into visuo-motor robot learning has emerged as a promising alternative to training visual encoders from scratch. However, PVRs face critical challenges in the context of policy learning, including temporal entanglement and an inability to generalise even in the presence of minor scene perturbations. These limitations hinder performance in tasks requiring temporal awareness and robustness to scene changes. This work identifies these shortcomings and proposes solutions to address them. First, we augment PVR features with temporal perception and a sense of task completion, effectively disentangling them in time. Second, we introduce a module that learns to selectively attend to task-relevant local features, enhancing robustness when evaluated on out-of-distribution scenes. Our experiments demonstrate significant performance improvements, particularly in PVRs trained with masking objectives, and validate the effectiveness of our enhancements in addressing PVR-specific limitations.

## Citation
Consider giving as a :star: to reveive a notification when the code becomes available in June. Also, if you found the paper useful for your research, consider citing the paper. Finally, consider citing the following works that made ours possible:  [For Pre-Trained Vision Models in Motor Control, Not All Policy Learning Methods are Created Equal](https://arxiv.org/abs/2304.04591v2), [R3M: A Universal Visual Representation for Robot Manipulation](https://arxiv.org/abs/2203.12601), [The Unsurprising Effectiveness of Pre-Trained Vision Models for Control](https://arxiv.org/abs/2203.03580).
```
@article{tsagkas2025pretrainedvisualrepresentationsfall,
    title={When Pre-trained Visual Representations Fall Short: Limitations in Visuo-Motor Robot Learning}, 
    author={Nikolaos Tsagkas and Andreas Sochopoulos and Duolikun Danier and Chris Xiaoxuan Lu and Oisin Mac Aodha},
    journal={arxiv preprint arXiv:2502.03270},
    year={2025},
}
```

