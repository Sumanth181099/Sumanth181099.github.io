---
title: "Multi-Modal Domain Fusion for Multi-Modal Aerial View Object Classification"
#excerpt: "Our solution to the CVPR Perception Beyond Visible Spectrum Workshop 2022: Multi-Modal Aerial View Object Classification challenge. We proposed a novel Multi-Modal Domain Fusion(MDF) network to learn the domain invariant features from multi-modal data and use it to accurately classify the aerial view objects<br/><a href="https://arxiv.org/pdf/2212.07039.pdf">paper</a>    <a href="https://github.com/Sumanth181099/PBVS_MAVOC2022">code</a><br><img src='/images/Screenshot from 2023-10-05 19-16-19.png'>"

collection: portfolio
---
<table style="border-collapse: collapse; border: none; font-size:16px">
<tr style="border: none;">
<th style="border: none;"><img src="/images/Screenshot from 2023-10-05 19-16-19.png" width="200%" height="200%"/></th>
<th style="border: none; ">Our solution to the CVPR Perception Beyond Visible Spectrum Workshop 2022: <a href="http://vcipl-okstate.org/pbvs/22/challenge.html">Multi-Modal Aerial View Object Classification challenge</a>. We proposed a novel Multi-Modal Domain Fusion(MDF) network to learn the domain invariant features from multi-modal data by reducing the domain discrepancy using Wasserstein distance and use it to accurately classify the aerially viewed objects. To make the learning more efficient, class-conditional domain adaptation was achieved by passing the multi-modal data in pairs at a time to the two models in MDF, effectively making it a shared feature learner. <br>
<FONT COLOR="#808080">Sumanth V Udupa, Aniruddh Sikdar, Suresh Sundaram</FONT><br>
<a href="https://arxiv.org/pdf/2212.07039.pdf">paper</a>    <a href="https://github.com/Sumanth181099/PBVS_MAVOC2022">code</a><br>

</th>
</tr>
</table>

Object detection and classification using aerial images is a challenging task as the information regarding targets are not abundant. Synthetic Aperture Radar(SAR) images can be used for Automatic Target Recognition(ATR) systems as it can operate in all-weather conditions and in low light settings. But, SAR images contain salt and pepper noise(speckle noise) that cause hindrance for the deep learning models to extract meaningful features. Using just aerial view Electro-optical(EO) images for ATR systems may also not result in high accuracy as these images are of low resolution and also do not provide ample information in extreme weather conditions. Therefore, information from multiple sensors can be used to enhance the performance of Automatic Target Recognition(ATR) systems. In this paper, we explore a methodology to use both EO and SAR sensor's information to effectively improve the performance of the ATR systems by handling the shortcomings of each of the sensors. A novel Multi-Modal Domain Fusion(MDF) network is proposed to learn the domain invariant features from multi-modal data and use it to accurately classify the aerial view objects. The proposed MDF network achieves top-10 performance in the Track-1 with an accuracy of 25.3% and top-5 performance in Track-2 with an accuracy of 34.26% in the test phase on the PBVS MAVOC Challenge dataset.<br>

Recomended Citation: Sumanth Udupa, Aniruddh Sikdar, and Suresh Sundaram. "Multi-Modal Domain Fusion for Multi-modal Aerial View Object Classification." arXiv preprint arXiv:2212.07039 (2022).
