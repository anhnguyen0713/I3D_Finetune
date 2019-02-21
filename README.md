This repository holds code for my project "Evaluating the reliability of current state-of-the-art action recognition models under impact of adversarial examples".

To setup the original Inception 3D Network, please refer to this repository ([link](https://github.com/USTC-Video-Understanding/I3D_Finetune)).

Two AE crafting algorithms are implemented to attack TSN. They are Fast Gradient Sign Method and Basic Iterative Fast Gradient Sign Method proposed in this paper ([link](https://arxiv.org/abs/1611.01236)).

To perform FGSM attack, run the following script
```
python i3d_fgsm.py
```

To perform Basic Iterative FGSM attack, run the following script
```
python i3d_fgsm_iter.py
```
