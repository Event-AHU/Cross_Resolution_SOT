<div align="center">
<img src="https://github.com/Event-AHU/Cross_Resolution_SOT/blob/main/figures/CRSOT_logo.png" width="600">
  
**A New Large-scale Benchmark Dataset for Cross-Resolution RGB-Event Single Object Tracking**

------

<p align="center">
</p>
</div>

> "**CRSOT: Cross-Resolution Object Tracking using Unaligned Frame and Event Cameras**." Yabin Zhu, Xiao Wang, Chenglong Li, Bo Jiang, Lin Zhu, Zhixiang Huang, Yonghong Tian, Jin Tang. arXiv preprint arXiv:2401.02826 (2024).
[[arXiv](https://arxiv.org/abs/2401.02826)] 




# :collision: Update Log 

* [2024.01.08] arXiv paper and dataset are all released [[arXiv](https://arxiv.org/abs/2401.02826)] [[Baidu-Disk](https://github.com/Event-AHU/Cross_Resolution_SOT/blob/main/README.md#dvd-crsot-dataset-download)]


# :dart: Abstract 
Existing datasets for RGB-DVS tracking are collected with DVS346 camera and their resolution ($346 \times 260$) is low for practical applications. Actually, only visible cameras are deployed in many practical systems, and the newly designed neuromorphic cameras may have different resolutions. The latest neuromorphic sensors can output high-definition event streams, but it is very difficult to achieve strict alignment between events and frames on both spatial and temporal views. Therefore, how to achieve accurate tracking with unaligned neuromorphic and visible sensors is a valuable but unresearched problem. In this work, we formally propose the task of object tracking using unaligned neuromorphic and visible cameras. We build the first unaligned frame-event dataset CRSOT collected with a specially built data acquisition system, which contains 1,030 high-definition RGB-Event video pairs, 304,974 video frames. In addition, we propose a novel unaligned object tracking framework that can realize robust tracking even using the loosely aligned RGB-Event data. Specifically, we extract the template and search regions of RGB and Event data and feed them into a unified ViT backbone for feature embedding. Then, we propose uncertainty perception modules to encode the RGB and Event features, respectively, then, we propose a modality uncertainty fusion module to aggregate the two modalities. These three branches are jointly optimized in the training phase. Extensive experiments demonstrate that our tracker can collaborate the dual modalities for high-performance tracking even without strictly temporal and spatial alignment.

<p align="center">
  <img src="https://github.com/Event-AHU/Cross_Resolution_SOT/blob/main/figures/crsot_device.jpg" alt="crsot_device" width="800"/>
  </a>
</p> 




# :triangular_flag_on_post: Framework 
<p align="center">
  <img src="https://github.com/Event-AHU/Cross_Resolution_SOT/blob/main/figures/framework_CRSOT.jpg" alt="framework_CRSOT.jpg" width="800"/>
  </a>
</p> 



# :hammer: Environment 




# :hourglass: Training and Testing 



# :chart_with_upwards_trend: Experimental Results 

*  **benchmarked tracking results** [[Baiduyun]()] [[GoogleDrive]()]
*  
 

# :triangular_ruler: Evaluation Toolkit






# :dvd: CRSOT Dataset Download 
:floppy_disk: **Download from Baidu Disk:** 
```
  Link: https://pan.baidu.com/s/1vs7JjWq3UntjnHGqz-3sSg 
  Password:9b94
```

:floppy_disk: **Download from DropBox:** 
```
TO BE UPDATED ...
```


# :cupid: Acknowledgement 

[[**OSTrack**](https://github.com/botaoye/OSTrack)]  [[**CEUTrack**](https://github.com/Event-AHU/COESOT)]  [[**VisEvent**](https://github.com/wangxiao5791509/VisEvent_SOT_Benchmark)]


# :newspaper: License 
MIT License








# :newspaper: Citation 
  If you find this work useful for your research, please cite the following papers: 
```bibtex
@misc{zhu2024crsot,
  title={CRSOT: Cross-Resolution Object Tracking using Unaligned Frame and Event Cameras}, 
  author={Yabin Zhu and Xiao Wang and Chenglong Li and Bo Jiang and Lin Zhu and Zhixiang Huang and Yonghong Tian and Jin Tang},
  year={2024},
  eprint={2401.02826},
  archivePrefix={arXiv},
  primaryClass={cs.CV}
    }
```

Please leave an issue, if you have any questions about this work. 

























