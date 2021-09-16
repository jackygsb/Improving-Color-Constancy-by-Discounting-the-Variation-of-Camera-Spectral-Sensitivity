-----------COPYRIGHT NOTICE STARTS WITH THIS LINE------------
Copyright (c) 2020
All rights reserved. This doucuments are a rough version for summarizing the results in publication [1],
which is available only for research purpose.

The dataset consists of the camera color spectral sensitivity curves (CSSs) of nine cameras that were used to caputre the NUS color constancy dataset [2] and some results of JOSA A [1]. In our JOSA A paper[1], we adopted the camera color sensitive curves of nine cameras from the NUS dataset to pre-train the matrix across two distinct CSSs. 
Extensive experiments on synthetic and real images show that our method can clearly improve the inter-CC performance for traditional CC algorithms. 
This paper [1] first studies the CSS effect on illuminant estimation arising in the interdataset-based CC (inter-CC), i.e., training a CC model on one dataset and then testing on another dataset captured by a distinct CSS. Many following work including the deep-learning based techniques have shown that taking the CSS effect into account, it is more likely to obtain the truly color constant images invariant to the changes of both illuminant and camera sensors.

Due to the problem of inter-CC performance has recently attracted the great attention for CC community, we have also attached the CSS data used in NUS color constancy dataset.
We would like to thank Dr. Dilip Kumar Prasad and Michael S. Brown [2] for providing their CSSs of NUS dataset. 
Many new inter-CC expeirments in the future could be appropriately compared with our propsoed technique due to the sharing of the dataset.  

If you use the dataset and the related method for research please clearly cite papers as follows.

1. Gao, S. B., Zhang, M., Li, C. Y., & Li, Y. J. (2017). Improving color constancy by discounting the variation 
of camera spectral sensitivity. JOSA A, 34(8), 1448-1462.

2. D. Cheng, D. K. Prasad, and M. S. Brown, “Illuminant estimation for color constancy: why spatial-domain methods work and the role of the color distribution,” JOSA A 31, 1049–1058 (2014).

Other datasets including the Hyperspectral images and the illuminants used in this study could be also accessed from the Refs cited in [1]. 

 
