# Depth-assisted-Edge-aware-Mirroring-Network-for-Camouflaged-Object-Detection
"Xu Li", "Xiaosheng Yu", "peijun Xiao" ,and "Peng Chen"

Abstract—The core of edge-aware methods lies in the early generation of edge predictions, which more effectively localizes and aids in the segmentation of camouflaged objects. Due to the high visual similarity between camouflaged objects and their surrounding environments, edge prediction quality is paramount. However, edge predictions generated solely from RGB images are susceptible to interference from background, texture, and color, resulting in incomplete segmentation and, in some cases, the omission of targets, leading to suboptimal detection of camouflaged objects. To address this challenge, we propose a Depth-assisted Edge-aware Mirroring Network for Camouflaged Object Detection (DEMNet). Our framework first introduces a multimodal batch feature fusion module, which disentangles fine-grained depth features from RGB features and processes these channels in a unified manner. Additionally, a depth-edge-aware module and an edge-guided integrity aggregation module are designed to refine features through cross-fusion, simultaneously focusing on the global structure of camouflaged objects while continuously refining segmentation and edge features. Finally, a residual channel attention module is employed to guide the extraction of structural details from low-level features. Experimental results on the CAMO, COD10K, and NC4K datasets demonstrate that DEMNet outperforms 30 representative models, with an average performance improvement of 1.1%, 0.1%, 1.2%, and 10.6% over ZoomNeXt in "S" _"α" , "E" _"θ" , "F" _"β" ^"ω"   and "M" , respectively.




**Qualitative Comparison**

![图7-2](https://github.com/user-attachments/assets/a3ba05f6-fbff-45cb-acbc-2b4460508be4)


