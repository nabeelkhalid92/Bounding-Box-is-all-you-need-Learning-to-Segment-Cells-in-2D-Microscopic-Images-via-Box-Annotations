# Bounding Box is all you need: Learning to Segment Cells in 2D Microscopic Images via Box Annotations
icroscopic imaging is crucial in science and medicine, providing important insights into cellular biology. Accurate identification and characterization of individual cells in these images are essential to this process. Deep learning-based cell segmentation, which involves delineating cells from complex microscopic images, is pivotal for cell analysis. It serves as the foundation for extracting meaningful information about cell morphology, spatial organization, and interactions. However, traditional deep-learning models for cell segmentation require extensive and expensive annotation masks for each cell in the image, posing a significant challenge. To address this issue, this study introduces CellBoxify, a novel pipeline that streamlines cell instance segmentation. Unlike traditional methods, CellBoxify operates solely on bounding box annotations, making it approximately seven times faster than manual segmentation mask annotation for each cell. The proposed approach's effectiveness is evident in its performance on the LIVECell dataset, a well-known resource for cell segmentation research. Achieving 83.40\% of the fully supervised performance on this dataset demonstrates the efficacy of the proposed method.
