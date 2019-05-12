# Segmentation Boundry loss

Paper: Boundary loss for highly unbalanced segmentation : https://arxiv.org/abs/1812.07032

This is a demonstration of Boundary Loss for refining segmentation of fine and rapidy changing boundaries. We tested this on various medical datasets and usually got an improvement of 1-2 dice scores or of around 3%. We first trained our model to saturation on dice and cross entropy and then continued training adding this loss. We found lower learning rates and momentum to be helpful.
