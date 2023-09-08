# Supplementary Material of IMU-Assisted Robust Blur Kernel Re-Estimation in Non-Uniform Image Deblurring

This supplementary material contains additional comparative experimental results.

## Comparison Results

We compare the proposed method with BDSI[1], DSPSI[2], ASPDC[3], M3SNet[4], CIMBID[5] and GAMD[6]

| <sub>Example #1</sub>                                  |
|:------------------------------------------------------:|
| ![](E:\Internet_share\my%20paper\fig\补充\git\img\1.svg) |

| <sub>Example #2</sub>                                  |
|:------------------------------------------------------:|
| ![](E:\Internet_share\my%20paper\fig\补充\git\img\2.svg) |

| <sub>Example #3</sub>                                  |
|:------------------------------------------------------:|
| ![](E:\Internet_share\my%20paper\fig\补充\git\img\3.svg) |

| <sub>Example #4</sub>                                  |
|:------------------------------------------------------:|
| ![](E:\Internet_share\my%20paper\fig\补充\git\img\4.svg) |

For a quantitative comparison of different methods using these real-world images, we use a deblurring metric introduced by [7]. This metric allows us to assess deblurring results quantitatively, where higher values signify better deblurring quality.

Quantitative comparison with BDSI, DSPSI, ASPDC, M3SNet, CIMBID and GAMD.

| Examples   | Blurred  | Ours    | BDSI     | DSPSI    | ASPDC    | M3SNet   | CIMBID   | GAMD    |
| ---------- | -------- | ------- | -------- | -------- | -------- | -------- | -------- | ------- |
| Example #1 | -9.8327  | -6.1239 | -8.9568  | -12.9896 | -8.6422  | -8.8448  | -9.3871  | -7.2160 |
| Example #2 | -14.2299 | -8.4303 | -10.1202 | -12.7717 | -12.6820 | -12.2690 | -11.5402 | -9.5651 |
| Example #3 | -7.4290  | -6.3265 | -6.5829  | -9.9197  | -7.2999  | -7.3520  | -7.8655  | -6.8204 |
| Example #4 | -7.8139  | -6.3981 | -7.0177  | -9.9497  | -6.9071  | -7.2169  | -9.4315  | -6.5126 |

# Reference

[1]: https://openaccess.thecvf.com/content_CVPR_2019/html/Chen_Blind_Image_Deblurring_With_Local_Maximum_Gradient_Prior_CVPR_2019_paper.html "L. Chen, F. Fang, T. Wang, and G. Zhang, “Blind image deblurring with local maximum gradient prior,” in Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, 2019, pp. 1742–1750."

[2]: https://link.springer.com/article/10.1007/s11263-014-0727-3 "Whyte O, Sivic J, Zisserman A. Deblurring shaken and partially saturated images[J]. International journal of computer vision, 2014, 110: 185-201."

[3]: https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/html/Huo_Blind_Non-Uniform_Motion_Deblurring_Using_Atrous_Spatial_Pyramid_Deformable_Convolution_CVPRW_2022_paper.html "Huo D, Masoumzadeh A, Yang Y H. Blind non-uniform motion deblurring using atrous spatial pyramid deformable convolution and deblurring-reblurring consistency[C]//Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2022: 437-446."

[4]: https://arxiv.org/abs/2305.05146 "Gao H, Yang J, Zhang Y, et al. A Mountain-Shaped Single-Stage Network for Accurate Image Restoration[J]. arXiv preprint arXiv:2305.05146, 2023."

[5]: https://ieeexplore.ieee.org/abstract/document/7463539 "Zhang Y, Hirakawa K. Combining inertial measurements with blind image deblurring using distance transform[J]. IEEE Transactions on Computational Imaging, 2016, 2(3): 281-293."

[6]: https://ieeexplore.ieee.org/abstract/document/8658406 "Mustaniemi J, Kannala J, Särkkä S, et al. Gyroscope-aided motion deblurring with deep networks[C]//2019 IEEE winter conference on applications of computer vision (WACV). IEEE, 2019: 1914-1922."

[7]: https://oar.princeton.edu/handle/88435/pr1fk0n "Liu Y, Wang J, Cho S, et al. A no-reference metric for evaluating the quality of motion deblurring[J]. ACM Transactions on Graphics, 2013."
