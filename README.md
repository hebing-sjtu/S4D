## S4D: Streaming 4D Real-World Reconstruction with Gaussians and 3D Control Points
<div align="center">
<a href="https://arxiv.org/abs/2408.13036"><img src='https://img.shields.io/badge/arXiv-2408.13036-b31b1b.svg'></a> &nbsp;
<a href="https://hebing-sjtu.github.io/S4D_page/"><img src='https://img.shields.io/badge/Project-In%20Progress-brightgreen.svg'></a> &nbsp;

_**[Bing He<sup>1*;</sup>](https://github.com/hebing-sjtu), 
[Yunuo Chen<sup>1*</sup>](https://github.com/YunuoChen), 
[Guo Lu<sup>1 </sup>](https://guolusjtu.github.io/guoluhomepage/), 
[Li Song <sup>1&dagger;</sup>](https://ee.sjtu.edu.cn/FacultyDetail.aspx?id=22&infoid=66&flag=66), 
[Wenjun Zhang<sup>1</sup>](https://ee.sjtu.edu.cn/FacultyDetail.aspx?id=14&infoid=66&flag=66)**_
<br><br>
<sup>1</sup>Shanghai Jiao Tong University

arXiv preprint, 2024

</div>


## 🔆 Introduction

**S4D** is a generalized streaming workflow for dynamic 3D scene reconstruction. The full process includes the 3D segmentation, 3D control points generation, object-wise motion manipulation, and residual compensation. 

**3D Control Point** is a discrete 3D motion representation. Each control point characterizes local translations and rotations around its space. By introducing a finely designed ray coordinate system, partial parameters of the 3D control points can be obtained directly from the optical flow without training.

<p align="center"> All Code will be released soon...  🔨 🚧 </p>


## 📜 Citation

If you find our work useful, please consider citing:

```
@article{he2024s4d,
  title={S4D: Streaming 4D Real-World Reconstruction with Gaussians and 3D Control Points},
  author={He, Bing and Chen, Yunuo and Lu, Guo and Song, Li and Zhang, Wenjun},
  journal={arXiv preprint arXiv:2408.13036},
  year={2024}
}
```

