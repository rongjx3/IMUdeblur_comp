# Supplementary Material of IMU-Assisted Robust Blur Kernel Re-Estimation in Non-Uniform Image Deblurring

This supplementary material contains additional comparative experimental results.

## Visual Comparison Results on Public Dataset

We compare the proposed method with BDSI[1], DSPSI[2], ASPDC[3], M3SNet[4], NAFNet[5], EFDT[6], SelfDeblur[7], VDIP[8], CIMBID[9] and GAMD[10] on the public dataset from CIMBID[9].

| <sub>Example #01</sub>                                  |
|:------------------------------------------------------:|
| ![](./img/YZ1.svg) |

| <sub>Example #02</sub>                                  |
|:------------------------------------------------------:|
| ![](./img/YZ2.svg) |

| <sub>Example #03</sub>                                  |
|:------------------------------------------------------:|
| ![](./img/YZ3.svg) |

| <sub>Example #04</sub>                                  |
|:------------------------------------------------------:|
| ![](./img/YZ4.svg) |

## Quantitative Comparison Results on Public Dataset

For a quantitative comparison of different methods using these real-world images, we use a deblurring metric introduced by [11]. This metric allows us to assess deblurring results quantitatively, where higher values signify better deblurring quality.

Quantitative comparison with BDSI, DSPSI, ASPDC, M3SNet, NAFNet, EFDT, SelfDeblur, VDIP, CIMBID and GAMD on the public dataset is shown in the table below.

| Example | Blur | Ours | BDSI | DSPSI | ASPDC | M3SNet | NAFNet | EFDT | SelfDeblur | VDIP | CIMBID | GAMD |
| ------- | -------- | ------- | -------- | -------- | -------- | -------- | -------- | ------- | ------- | ------- | ------- | ------- |
| #01 | -11.2445  | **-6.6010**  | -7.7394  | -9.5686  | -9.6105  | -10.2199  | -9.3732  | -9.5096  | -12.3482  | -8.9269  | -7.3765  | -9.5880 |
| #02 | -12.7530  | **-7.4661**  | -9.4947  | -10.8203  | -10.5854  | -11.3890  | -11.7498  | -11.5662  | -11.1049  | -10.3702  | -9.2331  | -10.7731 |
| #03 | -13.8704  | **-7.8338**  | -9.4071  | -11.6113  | -12.1604  | -11.8839  | -11.9703  | -11.9748  | -11.6265  | -10.8526  | -8.2509  | -11.1112 |
| #04 | -12.5138  | -8.3505  | -8.9111  | -10.9472  | -12.6569  | -13.1406  | -11.8283  | -10.9859  | -11.8240  | -11.7918  | **-6.8767**  | -10.0561 |
| Average | -12.5954  | **-7.5629**  | -8.8881  | -10.7369  | -11.2533  | -11.6584  | -11.2304  | -11.0091  | -11.7259  | -10.4854  | -7.9343  | -10.3821 |

## Visual Comparison Results on Proposed Dataset

We compare the proposed method with BDSI[1], DSPSI[2], ASPDC[3], M3SNet[4], NAFNet[5], EFDT[6], SelfDeblur[7], VDIP[8], CIMBID[9] and GAMD[10] on the proposed dataset.

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

## Quantitative Comparison Results on Proposed Dataset

Quantitative comparison with BDSI, DSPSI, ASPDC, M3SNet, NAFNet, EFDT, SelfDeblur, VDIP, CIMBID and GAMD on the full proposed dataset is shown in the table below.

| Example | Blur | Ours | BDSI | DSPSI | ASPDC | M3SNet | NAFNet | EFDT | SelfDeblur | VDIP | CIMBID | GAMD |
| ------- | -------- | ------- | -------- | -------- | -------- | -------- | -------- | ------- | ------- | ------- | ------- | ------- |
| #01 | -14.2299  | **-8.4303**  | -10.1202  | -12.7717  | -12.7610  | -11.4985  | -14.3875  | -11.4029  | -14.0889  | -13.7468  | -11.5402  | -9.5651 |
| #02 | -9.5827  | **-7.2969**  | -7.7550  | -11.1013  | -9.3064  | -8.6934  | -10.2131  | -8.6472  | -9.7206  | -9.7240  | -11.5618  | -7.9661 |
| #03 | -10.3344  | **-7.0323**  | -13.0681  | -13.9908  | -9.8253  | -9.9756  | -10.5314  | -9.7753  | -10.6578  | -10.5409  | -12.3192  | -8.7487 |
| #04 | -9.8327  | **-6.1239**  | -8.9568  | -12.9896  | -9.1821  | -9.0354  | -10.8401  | -8.5073  | -10.0383  | -9.7866  | -9.3871  | -7.2160 |
| #05 | -8.8548  | -7.2641  | -7.5804  | -13.3703  | -8.8874  | -8.1637  | -9.4952  | -7.8183  | -8.7094  | -8.2746  | -10.3126  | **-6.3930** |
| #06 | -9.3332  | **-7.3985**  | -7.8739  | -11.8843  | -8.6003  | -9.1244  | -9.6251  | -8.9136  | -9.0634  | -8.9603  | -9.1245  | -7.6856 |
| #07 | -10.8297  | **-8.7588**  | -9.1372  | -11.1475  | -10.2976  | -10.3487  | -10.8866  | -10.5002  | -11.1224  | -10.7797  | -11.4211  | -9.9066 |
| #08 | -10.7252  | **-7.7959**  | -8.1523  | -10.6616  | -10.1765  | -10.8158  | -10.5758  | -11.0737  | -11.4531  | -10.7046  | -9.7506  | -8.9586 |
| #09 | -8.7098  | **-7.6488**  | -7.9736  | -9.9873  | -8.4407  | -8.9775  | -8.9690  | -9.2261  | -8.8128  | -8.7977  | -8.7069  | -7.9521 |
| #10 | -10.1788  | **-6.6942**  | -9.4736  | -11.9584  | -9.0191  | -9.5080  | -10.6799  | -8.6291  | -10.2060  | -10.1041  | -10.9666  | -7.2690 |
| #11 | -8.8784  | **-5.7760**  | -10.8301  | -14.3212  | -8.5333  | -8.7637  | -9.6886  | -8.2267  | -8.9774  | -8.8247  | -9.4377  | -7.2537 |
| #12 | -10.5998  | **-7.2472**  | -12.2370  | -15.6571  | -9.6602  | -9.7213  | -11.1770  | -9.2494  | -9.8322  | -8.8489  | -12.7794  | -8.7189 |
| #13 | -10.0377  | **-5.9846**  | -8.8257  | -11.1666  | -7.9502  | -8.9996  | -10.1970  | -9.3490  | -9.4370  | -9.0338  | -10.2588  | -6.3445 |
| #14 | -13.5860  | -11.4174  | -15.3101  | -15.1848  | -11.5736  | -11.8136  | -13.4017  | -13.1168  | -14.4153  | -13.7340  | -12.1475  | **-11.0398** |
| #15 | -10.6250  | **-6.3864**  | -8.5152  | -14.4129  | -8.8497  | -9.1823  | -11.1711  | -8.2824  | -10.0242  | -10.0310  | -11.7873  | -7.2836 |
| #16 | -12.7760  | **-7.6617**  | -12.0659  | -15.7520  | -11.1811  | -9.7448  | -12.8441  | -10.1712  | -12.7225  | -11.2023  | -13.2840  | -9.5225 |
| #17 | -9.1349  | -7.8922  | **-7.5550**  | -14.8067  | -8.6838  | -8.5554  | -9.0545  | -8.8435  | -13.1039  | -9.2014  | -10.5132  | -8.2917 |
| #18 | -7.8139  | **-6.3981**  | -7.0177  | -9.9497  | -6.8967  | -7.4360  | -7.8960  | -7.7172  | -7.7402  | -7.6044  | -9.4315  | -6.5126 |
| #19 | -7.7791  | **-5.1361**  | -6.1350  | -10.0236  | -6.4178  | -7.2561  | -8.4832  | -8.0752  | -7.6749  | -7.5310  | -7.3381  | -5.2859 |
| #20 | -8.7288  | **-6.8535**  | -6.8611  | -10.1206  | -8.0806  | -8.0215  | -8.2490  | -8.4467  | -8.6777  | -8.0888  | -8.7366  | -8.5228 |
| #21 | -9.9892  | **-7.4999**  | -7.8347  | -10.3566  | -8.5581  | -8.7530  | -9.8498  | -8.7204  | -10.0927  | -10.1350  | -10.1805  | -8.6313 |
| #22 | -8.2565  | **-6.4141**  | -7.0828  | -10.3714  | -7.8222  | -8.3561  | -8.1644  | -7.6854  | -8.1602  | -7.8964  | -9.2537  | -7.3795 |
| #23 | -10.5596  | **-8.4695**  | -11.0236  | -10.9863  | -10.5045  | -10.4873  | -10.8490  | -10.4558  | -10.5967  | -10.0067  | -11.5786  | -8.8920 |
| #24 | -7.4290  | **-6.3265**  | -6.5829  | -9.9197  | -7.5716  | -7.3804  | -7.3889  | -7.2018  | -7.2735  | -8.3577  | -7.8655  | -6.8204 |
| #25 | -8.6966  | **-7.3209**  | -7.3584  | -10.2487  | -8.6459  | -8.4864  | -8.7351  | -8.7708  | -8.7751  | -8.6232  | -9.5188  | -8.2231 |
| #26 | -10.4036  | **-8.1406**  | -9.8170  | -10.7759  | -9.4746  | -9.9278  | -10.2736  | -9.8876  | -10.8830  | -10.4039  | -11.7137  | -9.0665 |
| #27 | -8.3085  | **-6.9525**  | -9.0720  | -8.6901  | -8.3203  | -7.6965  | -8.4551  | -7.5666  | -8.2597  | -8.1728  | -8.3824  | -7.7096 |
| #28 | -10.3143  | **-8.2867**  | -11.8390  | -12.3479  | -9.0235  | -9.4168  | -10.7287  | -9.4159  | -10.5844  | -9.9678  | -9.3942  | -8.9728 |
| #29 | -9.2996  | -8.7272  | -9.7385  | -11.1071  | -9.1716  | -9.0826  | -9.3372  | -8.8763  | -9.4594  | -8.7742  | **-8.4608**  | -8.6932 |
| #30 | -8.1476  | **-6.9149**  | -9.4497  | -9.5444  | -7.0898  | -7.0563  | -8.2066  | -7.0195  | -8.0732  | -8.0185  | -10.4707  | -6.9506 |
| #31 | -8.9102  | -8.1518  | -9.3229  | -11.1002  | -8.6799  | -8.4040  | -8.9522  | -8.2892  | -8.9591  | -8.0575  | -11.3062  | **-8.0516** |
| #32 | -9.8999  | -7.6313  | -8.0334  | -10.4726  | -8.0854  | -8.3027  | -9.4242  | **-7.6278**  | -9.0285  | -8.4252  | -8.0141  | -7.7741 |
| Average | -9.7745  | **-7.3760**  | -9.1437  | -11.7868  | -8.9772  | -9.0308  | -9.9603  | -8.9840  | -9.8945  | -9.4487  | -10.2170  | -8.0500 |

Full proposed dataset is available in [here](https://www.dropbox.com/scl/fi/p7n0lmjq1fbn2msm2ohly/IMU_deblur_dataset.rar?rlkey=bb67jn700d3k1uakfux9ht82p&dl=0).

# Reference

[1]: https://openaccess.thecvf.com/content_CVPR_2019/html/Chen_Blind_Image_Deblurring_With_Local_Maximum_Gradient_Prior_CVPR_2019_paper.html "L. Chen, F. Fang, T. Wang, and G. Zhang, “Blind image deblurring with local maximum gradient prior,” in Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, 2019, pp. 1742–1750."

[2]: https://link.springer.com/article/10.1007/s11263-014-0727-3 "Whyte O, Sivic J, Zisserman A. Deblurring shaken and partially saturated images[J]. International journal of computer vision, 2014, 110: 185-201."

[3]: https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/html/Huo_Blind_Non-Uniform_Motion_Deblurring_Using_Atrous_Spatial_Pyramid_Deformable_Convolution_CVPRW_2022_paper.html "Huo D, Masoumzadeh A, Yang Y H. Blind non-uniform motion deblurring using atrous spatial pyramid deformable convolution and deblurring-reblurring consistency[C]//Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2022: 437-446."

[4]: https://arxiv.org/abs/2305.05146 "Gao H, Yang J, Zhang Y, et al. A Mountain-Shaped Single-Stage Network for Accurate Image Restoration[J]. arXiv preprint arXiv:2305.05146, 2023."

[5]: https://link.springer.com/chapter/10.1007/978-3-031-20071-7_2 "Chen L, Chu X, Zhang X, et al. Simple baselines for image restoration[C]//European conference on computer vision. Cham: Springer Nature Switzerland, 2022: 17-33."

[6]: https://openaccess.thecvf.com/content/CVPR2023/html/Kong_Efficient_Frequency_Domain-Based_Transformers_for_High-Quality_Image_Deblurring_CVPR_2023_paper.html "Kong L, Dong J, Ge J, et al. Efficient frequency domain-based transformers for high-quality image deblurring[C]//Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2023: 5886-5895."

[7]: https://openaccess.thecvf.com/content_CVPR_2020/html/Ren_Neural_Blind_Deconvolution_Using_Deep_Priors_CVPR_2020_paper.html "Ren D, Zhang K, Wang Q, et al. Neural blind deconvolution using deep priors[C]//Proceedings of the IEEE/CVF conference on computer vision and pattern recognition. 2020: 3341-3350."

[8]: https://ieeexplore.ieee.org/abstract/document/10146429 "Huo D, Masoumzadeh A, Kushol R, et al. Blind image deconvolution using variational deep image prior[J]. IEEE Transactions on Pattern Analysis and Machine Intelligence, 2023."

[9]: https://ieeexplore.ieee.org/abstract/document/7463539 "Zhang Y, Hirakawa K. Combining inertial measurements with blind image deblurring using distance transform[J]. IEEE Transactions on Computational Imaging, 2016, 2(3): 281-293."

[10]: https://ieeexplore.ieee.org/abstract/document/8658406 "Mustaniemi J, Kannala J, Särkkä S, et al. Gyroscope-aided motion deblurring with deep networks[C]//2019 IEEE winter conference on applications of computer vision (WACV). IEEE, 2019: 1914-1922."

[11]: https://oar.princeton.edu/handle/88435/pr1fk0n "Liu Y, Wang J, Cho S, et al. A no-reference metric for evaluating the quality of motion deblurring[J]. ACM Transactions on Graphics, 2013."
