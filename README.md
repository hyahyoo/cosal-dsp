# Co-salient Object Detection Based on Deep Saliency Networks and Seed Propagation over an Integrated Graph
This paper presents a co-salient object detection method to find common salient regions in a set of images. We utilize deep saliency networks to transfer co-saliency prior knowledge and better capture high-level semantic information. The resulting initial co-saliency maps are enhanced by seed propagation steps over an integrated graph. The deep saliency networks are trained in a supervised manner to avoid weakly supervised online learning and exploit them not only to extract high-level features but also to produce both intra- and interimage saliency maps. Through a refinement step, the initial cosaliency maps can uniformly highlight co-salient regions and
locate accurate object boundaries. To handle input image groups inconsistent in size, we propose to pool multi-regional descriptors
including both within-segment and within-group information. In addition, the integrated multilayer graph is constructed to
find the regions that the previous steps may not detect by seed propagation with low-level descriptors. In this work, we
utilize the useful complementary components of high-, low-level information, and several learning-based steps. Our experiments
have demonstrated that the proposed approach outperforms comparable co-saliency detection methods on widely used public
databases and can also be directly applied to co-segmentation tasks.

[[pdf](https://ieeexplore.ieee.org/document/8419754)]
