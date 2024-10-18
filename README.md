# Dynamically Modulating VPR Sequence Length

Currently the code uploaded is research quality code. We are working on making it more accessible and readable when possible.

#### 'Dynamically Modulating Visual Place Recognition Sequence Length For Minimum Acceptable Performance Scenarios' \[[IEEE Xplore](https://arxiv.org/abs/2407.00863)]  \[[arXiv](https://arxiv.org/abs/2407.00863)]

### Abstract
Mobile robots and autonomous vehicles are often required to function in environments where critical position estimates from sensors such as GPS become uncertain or unreliable. Single image visual place recognition (VPR) provides an alternative for localization but often requires techniques such as sequence matching to improve robustness, which incurs additional computation and latency costs. Even then, the sequence length required to localize at an acceptable performance level varies widely; and simply setting overly long fixed sequence lengths creates unnecessary latency, computational overhead, and can even degrade performance. In these scenarios it is often more desirable to meet or exceed a set target performance at minimal expense. In this paper we present an approach which uses a calibration set of data to fit a model that modulates sequence length for VPR as needed to exceed a target localization performance. We make use of a coarse position prior, which could be provided by any other localization system, and capture the variation in appearance across this region. We use the correlation between appearance variation and sequence length to curate VPR features and fit a multilayer perceptron (MLP) for selecting the optimal length. We demonstrate that this method is effective at modulating sequence length to maximize the number of sections in a dataset which meet or exceed a target performance whilst minimizing the median length used. We show applicability across several datasets and reveal key phenomena like generalization capabilities, the benefits of curating features and the utility of non-state-of-the-art feature extractors with nuanced properties.

![Error](https://github.com/CMalone-Jupiter/VPR_Seq_Modulation/blob/main/imgs/Dyn_Seq_Len.png)

### Cite
If this repository contributes to your research, please consider citing the publication below.
```
C. Malone, A. Vora, T. Peynot and M.Milford, "Dynamically Modulating Visual Place Recognition Sequence Length For Minimum Acceptable Performance Scenarios," in the IEEE/RSJ International Conference on Intelligent Robots and Systems, Oct 2024.
```
#### Bibtex
```
@inproceedings{malone2024dynamically,
  title={Dynamically Modulating Visual Place Recognition Sequence Length For Minimum Acceptable Performance Scenarios},
  author={Malone, Connor and Vora, Ankit and Peynot, Thierry and Milford, Michael},
  booktitle={2024 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
  year={2024}
}
```


