# neural-global-shutter

> Neural Global Shutter: Learn to Restore Video from a Rolling Shutter Camera with Global Reset Feature
> CVPR, 2022

[paper]()
| [project website]() | [dataset](https://drive.google.com/file/d/1gkZpdtDPMGyQF6t-GVq6YgjQ3QfknVRv/view?usp=sharing)

## Introduction

<div align="center">
  <img src="resources/RSGR_problem.png" width="800"/>
</div>

> **Abbreviation:** [RS](https://en.wikipedia.org/wiki/Rolling_shutter)&rarr;rolling shutter; GS&rarr;global shutter; [RSGR](https://www.baumer.com/ca/en/service-support/technical-information-industrial-cameras/rolling-shutter-global-shutter-two-principles-of-exposure-/a/rolling-shutter-global-shutter#:~:text=Some%20rolling%20shutter%20sensors%20provide,typical%20for%20rolling%20shutter%20sensors.)&rarr;rolling shutter with global reset

- We offer an alternative and new solution for RS rectification by turning the rectification problem into a deblur-like one with RSGR, a widely ignored feature of RS sensors. 
- We propse a method to restore clean video from RSGR inputs by eliminating the spatial-varying distortions.
- We collect a dataset with paired RSGR and GS videos under real scenes for developing and evaluating algorithms.

## Updates

- 2022/03/11: We make the RSGR-GS [dataset](https://drive.google.com/file/d/1gkZpdtDPMGyQF6t-GVq6YgjQ3QfknVRv/view?usp=sharing) public available.


## Citation

If you find this project useful in your research, please consider cite:

```BibTeX
@inproceedings{Wang_2022_CVPR,
author = {Wang, Zhixiang and Ji, Xiang and Huang, Jia-Bin and Satoh, Shin'ichi and Zhou, Xiao and Zheng, Yinqiang},
title = {Neural Global Shutter: Learn to Restore Video from a Rolling Shutter Camera with Global Reset Feature},
booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
month = {June},
year = {2022}
}
```

## Contact

If you have any questions, please contact wangzx1994 -a-t- gmail.com or yqzheng -a-t ai.u-tokyo.ac.jp

<!-- ## FAQ
TBA -->


## License

[![CC0](https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-nd/4.0/)