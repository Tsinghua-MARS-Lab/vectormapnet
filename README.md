# VectorMapNet

**VectorMapNet: End-to-end Vectorized HD Map Learning**


[Yicheng Liu](https://scholar.google.com/citations?user=vRmsgQUAAAAJ&hl=zh-CN), Tianyuan Yuan, [Yue Wang](https://people.csail.mit.edu/yuewang/), [Yilun Wang](https://scholar.google.com.hk/citations?user=nUyTDosAAAAJ&hl=en/), [Hang Zhao](http://people.csail.mit.edu/hangzhao/)

**[[Paper](https://arxiv.org/pdf/2206.08920.pdf)] [[Project Page](https://tsinghua-mars-lab.github.io/vectormapnet/)] [[Code](https://github.com/Mrmoore98/VectorMapNet_code)]**

**Abstract:**
Autonomous driving systems require a good understanding of surrounding environments, including moving obstacles and static High-Definition (HD) semantic map elements. Existing methods approach the semantic map problem by offline manual annotation, which suffers from serious scalability issues.  Recent learning-based methods produce dense rasterized segmentation predictions to construct maps. However, these predictions do not include instance information of individual map elements and require heuristic post-processing to obtain vectorized maps. To tackle these challenges, we introduce an end-to-end vectorized HD map learning pipeline, termed VectorMapNet. VectorMapNet takes onboard sensor observations and predicts a sparse set of polylines in the bird's-eye view. This pipeline can explicitly model the spatial relation between map elements and generate vectorized maps that are friendly to downstream autonomous driving tasks. Extensive experiments show that VectorMapNet achieve strong map learning performance on both nuScenes and Argoverse2 dataset, surpassing previous state-of-the-art methods by 14.2 mAP and 14.6mAP. Qualitatively, we also show that VectorMapNet is capable of generating comprehensive maps and capturing more fine-grained details of road geometry. To the best of our knowledge, VectorMapNet is the first work designed towards end-to-end vectorized map learning from onboard observations. 

**Questions/Requests:** 
Please file an [issue](https://github.com/Tsinghua-MARS-Lab/vecmapnet/issues) or send an email to [Yicheng](moooooore66@gmail.com).
