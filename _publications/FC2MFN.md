---
 title: "Fully Complex-valued Fully Convolutional Multi-feature Fusion Network(FC2MFN) for Building Segmentation of InSAR images"
 collection: publications
 permalink: /publications/FC2MFN
# excerpt: 'Building segmentation in large-scale aerial images is challenging, especially for small buildings in dense and cluttered urban environments. Complex building structures with highly varied geometric footprints pose an additional challenge for the building segmentation task in satellite imagery. In this work, we propose to tackle the issue of detecting and segmenting small and complex-shaped buildings in Electro-Optical (EO) and SAR satellite imagery. A novel architecture Deep Multi-scale Aware Overcomplete Network (DeepMAO), is proposed that comprises an overcomplete branch that focuses on fine structural features and an undercomplete (U-Net) branch tasked to focus on coarse, semantic-rich features. Additionally, a novel self-regulating augmentation strategy, Loss-Mix, is proposed to increase pixel representation of misclassified pixels. DeepMAO is simple and efficient in accurately identifying small and geometrically complex buildings. Experimental results on SpaceNet 6 dataset, on both EO and SAR modalities, and the INRIA dataset show that DeepMAO achieves state-ofthe-art building segmentation performance, including small and complex-shaped buildings with a negligible increase in the parameter count. In addition, the presence of the overcomplete branch in DeepMAO helps in handling the speckle noise present in the SAR image modality.'
# gif: /images/deepmao_githubio.gif
 date: 2022-12-07
 venue: 'IEEE SSCI'
# paperurl: 'https://openaccess.thecvf.com/content/CVPR2023W/PBVS/papers Sikdar_DeepMAO_Deep_Multi-Scale_Aware_Overcomplete_Network_for_Building_Segmentation_in_CVPRW_2023_paper.pdf'
# citation: 'Aniruddh Sikdar, Sumanth Udupa, Prajwal Gurunath, Suresh Sundaram; Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops, 2023, pp. 487-496.'
---

<table style="border-collapse: collapse; border: none; font-size:16px">
<tr style="border: none;">
<th style="border: none;"><img src="/images/FC2MFN.gif" width="75%" height="75%"/></th>
<th style="border: none; "><a href="https://arxiv.org/pdf/2212.07084.pdf">Fully Complex-valued Fully Convolutional Multi-feature Fusion Network(FC2MFN) for Building Segmentation of InSAR images</a><br>
Aniruddh Sikdar*, Sumanth V Udupa*, Suresh Sundaram, Narasimhan Sundararajan<br>
*equal contribution<br>
<a href="https://arxiv.org/pdf/2212.07084.pdf">paper</a>  <a href="https://docs.google.com/presentation/d/1YL2UnWHnB7iSNhJsbpOtb8Yc71zBNFfV/edit?usp=sharing&ouid=104963490925330429223&rtpof=true&sd=true">slides</a><br>

</th>
</tr>
</table>

Building segmentation in high-resolution InSAR images is a challenging task that can be useful for large-scale surveillance. Although complex-valued deep learning networks perform better than their real-valued counterparts for complexvalued SAR data, phase information is not retained throughout the network, which causes a loss of information. This paper proposes a Fully Complex-valued, Fully Convolutional Multifeature Fusion Network (FC2MFN) for building semantic segmentation on InSAR images using a novel, fully complex-valued learning scheme. FC2 MFN learns multi-scale features, performs multi-feature fusion, and has a complex-valued output. For the particularity of complex-valued InSAR data, a new complexvalued pooling layer is proposed that compares complex numbers considering their magnitude and phase. This helps the network retain the phase information even through the pooling layer. Experimental results on the simulated InSAR dataset show that FC2 MFN achieves better results compared to other state-of theart methods in terms of segmentation performance and model complexity.<br>

Recomended Citation: Aniruddh Sikdar, Sumanth Udupa, Suresh Sundaram, and Narasimhan Sundararajan. "Fully Complex-valued Fully Convolutional Multi-feature Fusion Network (FC 2 MFN) for Building Segmentation of InSAR images." In 2022 IEEE Symposium Series on Computational Intelligence (SSCI), pp. 581-587. IEEE, 2022.

