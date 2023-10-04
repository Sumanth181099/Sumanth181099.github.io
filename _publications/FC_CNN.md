---
 title: "Fully complex-valued deep learning model for visual perception"
 collection: publications
 permalink: /publications/
# excerpt: 'Building segmentation in large-scale aerial images is challenging, especially for small buildings in dense and cluttered urban environments. Complex building structures with highly varied geometric footprints pose an additional challenge for the building segmentation task in satellite imagery. In this work, we propose to tackle the issue of detecting and segmenting small and complex-shaped buildings in Electro-Optical (EO) and SAR satellite imagery. A novel architecture Deep Multi-scale Aware Overcomplete Network (DeepMAO), is proposed that comprises an overcomplete branch that focuses on fine structural features and an undercomplete (U-Net) branch tasked to focus on coarse, semantic-rich features. Additionally, a novel self-regulating augmentation strategy, Loss-Mix, is proposed to increase pixel representation of misclassified pixels. DeepMAO is simple and efficient in accurately identifying small and geometrically complex buildings. Experimental results on SpaceNet 6 dataset, on both EO and SAR modalities, and the INRIA dataset show that DeepMAO achieves state-ofthe-art building segmentation performance, including small and complex-shaped buildings with a negligible increase in the parameter count. In addition, the presence of the overcomplete branch in DeepMAO helps in handling the speckle noise present in the SAR image modality.'
# gif: /images/deepmao_githubio.gif
 date: 2023-06-04
 venue: 'IEEE ICASSP'
# paperurl: 'https://openaccess.thecvf.com/content/CVPR2023W/PBVS/papers Sikdar_DeepMAO_Deep_Multi-Scale_Aware_Overcomplete_Network_for_Building_Segmentation_in_CVPRW_2023_paper.pdf'
# citation: 'Aniruddh Sikdar, Sumanth Udupa, Prajwal Gurunath, Suresh Sundaram; Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops, 2023, pp. 487-496.'
---

<table style="border-collapse: collapse; border: none; font-size:16px">
<tr style="border: none;">
<th style="border: none;"><img src="/images/ICASSP_githubio.JPG" width="75%" height="75%"/></th>
<th style="border: none; "><a href="https://ieeexplore.ieee.org/document/10095290">Fully complex-valued deep learning model for visual perception</a><br>
Aniruddh Sikdar*, Sumanth V Udupa*, Suresh Sundaram<br>
*equal contribution<br>
<a href="https://ieeexplore.ieee.org/document/10095290">paper</a><br>

</th>
</tr>
</table>

Deep learning models operating in the complex domain are used due to their rich representation capacity. However, most of these models are either restricted to the first quadrant of the complex plane or project the complex-valued data into the real domain, causing a loss of information. This paper proposes that operating entirely in the complex domain increases the overall performance of complex-valued models. A novel, fully complex-valued learning scheme is proposed to train a Fully Complex-valued Convolutional Neural Network (FC-CNN) using a newly proposed complex-valued loss function and training strategy. Benchmarked on CIFAR-10, SVHN, and CIFAR-100, FC-CNN has a 4-10% gain compared to its real-valued counterpart, with the same number of parameters. It achieves comparable performance to state-of-the-art complex-valued models on CIFAR-10 and SVHN with fewer parameters. For the CIFAR-100 dataset, it achieves state-of-the-art performance with 25% fewer parameters. FC-CNN shows better training efficiency and much faster convergence than all the other models.<br>

Recomended Citation: Aniruddh Sikdar, Sumanth Udupa, and Suresh Sundaram. "Fully complex-valued deep learning model for visual perception." ICASSP 2023-2023 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP). IEEE, 2023.
