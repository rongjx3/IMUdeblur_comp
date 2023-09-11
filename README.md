# Supplementary Material of IMU-Assisted Robust Blur Kernel Re-Estimation in Non-Uniform Image Deblurring

This supplementary material contains additional comparative experimental results.

## Comparison Results

We compare the proposed method with BDSI[1], DSPSI[2], ASPDC[3], M3SNet[4], CIMBID[5] and GAMD[6]

| <sub>Example #01</sub>                                  |
|:------------------------------------------------------:|
| ![](./img/2.svg) |

| <sub>Example #04</sub>                                  |
|:------------------------------------------------------:|
| ![](./img/1.svg) |

| <sub>Example #18</sub>                                  |
|:------------------------------------------------------:|
| ![](./img/4.svg) |

| <sub>Example #24</sub>                                  |
|:------------------------------------------------------:|
| ![](./img/3.svg) |

For a quantitative comparison of different methods using these real-world images, we use a deblurring metric introduced by [7]. This metric allows us to assess deblurring results quantitatively, where higher values signify better deblurring quality.

Quantitative comparison with BDSI, DSPSI, ASPDC, M3SNet, CIMBID and GAMD on the full proposed dataset is shown in the table below.

| Examples   | Blurred  | Ours    | BDSI     | DSPSI    | ASPDC    | M3SNet   | CIMBID   | GAMD    |
| ---------- | -------- | ------- | -------- | -------- | -------- | -------- | -------- | ------- |
| #01 | -14.2299  | **-8.4303**  | -10.1202  | -12.7717  | -12.6820  | -12.2690  | -11.5402  | -9.5651  |
| #02 | -9.5827  | **-7.2969**  | -7.7550  | -11.1013  | -8.8022  | -9.3464  | -11.5618  | -7.9661  |
| #03 | -10.3344  | **-7.0323**  | -13.0681  | -13.9908  | -9.4709  | -9.2892  | -12.3192  | -8.7487  |
| #04 | -9.8327  | **-6.1239**  | -8.9568  | -12.9896  | -8.6422  | -8.8448  | -9.3871  | -7.2160  |
| #05 | -8.8548  | -7.2641  | -7.5804  | -13.3703  | -7.9663  | -8.6411  | -10.3126  | **-6.3930**  |
| #06 | -9.3332  | **-7.3985**  | -7.8739  | -11.8843  | -8.8000  | -8.4624  | -9.1245  | -7.6856  |
| #07 | -10.8297  | **-8.7588**  | -9.1372  | -11.1475  | -9.8556  | -10.0528  | -11.4211  | -9.9066  |
| #08 | -10.7252  | **-7.7959**  | -8.1523  | -10.6616  | -9.9333  | -10.1115  | -9.7506  | -8.9586  |
| #09 | -8.7098  | **-7.6488**  | -7.9736  | -9.9873  | -8.2491  | -8.5292  | -8.7069  | -7.9521  |
| #10 | -10.1788  | **-6.6942**  | -9.4736  | -11.9584  | -8.8406  | -9.1617  | -10.9666  | -7.2690  |
| #11 | -8.8784  | **-5.7760**  | -10.8301  | -14.3212  | -7.8421  | -8.0221  | -9.4377  | -7.2537  |
| #12 | -10.5998  | **-7.2472**  | -12.2370  | -15.6571  | -9.9911  | -9.5484  | -12.7794  | -8.7189  |
| #13 | -10.0377  | **-5.9846**  | -8.8257  | -11.1666  | -8.8226  | -8.6641  | -10.2588  | -6.3445  |
| #14 | -13.5860  | -11.4174  | -15.3101  | -15.1848  | -12.3165  | -12.3554  | -12.1475  | **-11.0398**  |
| #15 | -10.6250  | **-6.3864**  | -8.5152  | -14.4129  | -8.7517  | -8.7065  | -11.7873  | -7.2836  |
| #16 | -12.7760  | **-7.6617**  | -12.0659  | -15.7520  | -11.1233  | -11.4754  | -13.2840  | -9.5225  |
| #17 | -9.1349  | -7.8922  | **-7.5550**  | -14.8067  | -8.6824  | -8.8737  | -10.5132  | -8.2917  |
| #18 | -7.8139  | **-6.3981**  | -7.0177  | -9.9497  | -6.9071  | -7.2169  | -9.4315  | -6.5126  |
| #19 | -7.7791  | **-5.1361**  | -6.1350  | -10.0236  | -6.6488  | -6.9675  | -7.3381  | -5.2859  |
| #20 | -8.7288  | **-6.8535**  | -6.8611  | -10.1206  | -8.4232  | -8.1812  | -8.7366  | -8.5228  |
| #21 | -9.9892  | **-7.4999**  | -7.8347  | -10.3566  | -9.3880  | -9.6060  | -10.1805  | -8.6313  |
| #22 | -8.2565  | **-6.4141**  | -7.0828  | -10.3714  | -7.9356  | -7.9838  | -9.2537  | -7.3795  |
| #23 | -10.5596  | **-8.4695**  | -11.0236  | -10.9863  | -10.0703  | -10.1117  | -11.5786  | -8.8920  |
| #24 | -7.4290  | **-6.3265**  | -6.5829  | -9.9197  | -7.2999  | -7.3520  | -7.8655  | -6.8204  |
| #25 | -8.6966  | **-7.3209**  | -7.3584  | -10.2487  | -8.4268  | -8.6375  | -9.5188  | -8.2231  |
| #26 | -10.4036  | **-8.1406**  | -9.8170  | -10.7759  | -9.7252  | -9.9475  | -11.7137  | -9.0665  |
| #27 | -8.3085  | **-6.9525**  | -9.0720  | -8.6901  | -7.8611  | -8.1246  | -8.3824  | -7.7096  |
| #28 | -10.3143  | **-8.2867**  | -11.8390  | -12.3479  | -9.1013  | -9.5453  | -9.3942  | -8.9728  |
| #29 | -9.2996  | -8.7272  | -9.7385  | -11.1071  | -9.0587  | -9.2425  | **-8.4608**  | -8.6932  |
| #30 | -8.1476  | **-6.9149**  | -9.4497  | -9.5444  | -7.3556  | -7.5423  | -10.4707  | -6.9506  |
| #31 | -8.9102  | -8.1518  | -9.3229  | -11.1002  | -8.5296  | -8.5982  | -11.3062  | **-8.0516**  |
| #32 | -9.8999  | **-7.6313**  | -8.0334  | -10.4726  | -8.2374  | -8.2785  | -8.0141  | -8.7550  |
| Average | -9.7745  | **-7.3760**  | -9.1437  | -11.7868  | -8.9294  | -9.0528  | -10.2170  | -8.0807  |

Full proposed dataset is available in [here](https://www.dropbox.com/scl/fi/p7n0lmjq1fbn2msm2ohly/IMU_deblur_dataset.rar?rlkey=bb67jn700d3k1uakfux9ht82p&dl=0).

# Reference

[1]: https://openaccess.thecvf.com/content_CVPR_2019/html/Chen_Blind_Image_Deblurring_With_Local_Maximum_Gradient_Prior_CVPR_2019_paper.html "L. Chen, F. Fang, T. Wang, and G. Zhang, “Blind image deblurring with local maximum gradient prior,” in Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, 2019, pp. 1742–1750."

[2]: https://link.springer.com/article/10.1007/s11263-014-0727-3 "Whyte O, Sivic J, Zisserman A. Deblurring shaken and partially saturated images[J]. International journal of computer vision, 2014, 110: 185-201."

[3]: https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/html/Huo_Blind_Non-Uniform_Motion_Deblurring_Using_Atrous_Spatial_Pyramid_Deformable_Convolution_CVPRW_2022_paper.html "Huo D, Masoumzadeh A, Yang Y H. Blind non-uniform motion deblurring using atrous spatial pyramid deformable convolution and deblurring-reblurring consistency[C]//Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2022: 437-446."

[4]: https://arxiv.org/abs/2305.05146 "Gao H, Yang J, Zhang Y, et al. A Mountain-Shaped Single-Stage Network for Accurate Image Restoration[J]. arXiv preprint arXiv:2305.05146, 2023."

[5]: https://ieeexplore.ieee.org/abstract/document/7463539 "Zhang Y, Hirakawa K. Combining inertial measurements with blind image deblurring using distance transform[J]. IEEE Transactions on Computational Imaging, 2016, 2(3): 281-293."

[6]: https://ieeexplore.ieee.org/abstract/document/8658406 "Mustaniemi J, Kannala J, Särkkä S, et al. Gyroscope-aided motion deblurring with deep networks[C]//2019 IEEE winter conference on applications of computer vision (WACV). IEEE, 2019: 1914-1922."

[7]: https://oar.princeton.edu/handle/88435/pr1fk0n "Liu Y, Wang J, Cho S, et al. A no-reference metric for evaluating the quality of motion deblurring[J]. ACM Transactions on Graphics, 2013."
