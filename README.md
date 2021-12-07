# IMAGE_RECOGNITION_CAR_PERSON

Develop and Train the model to detect person and cars in an image

# Methodology Used : Mask RCNN Network

MRCNN consists of two definitive parts: the backbone network and the network head thus inheriting the Faster R-CNN architecture. The convolutional backbone network, which is based either on Feature Pyramid Network (FPN) or ResNet101, works as features extractor over the whole image. On top of this lies Region Proposal Network (RPN) that samples multiscale RoI (regions of interest) for the head. The network head does bounding box recognition and mask prediction that is applied to each RoI. In between, RoIAlign layer finely aligns RPN-extracted multiscale features with the input.
