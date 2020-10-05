# Resources

This document contains a curated list of research papers, tutorials, datasets, and workshops related to 3D human and clothing digitization.

### Areas:

#### 3D Human Reconstruction and Digitization

#### Virtual Try-On, Image Generation in Fashion, Style Transfer

#### 3D Clothing Digitization

***

### 3D Human Reconstruction and Digitization:

1. **PIFuHD: Multi-Level Pixel-Aligned Implicit Function for High-Resolution 3D Human Digitization:** [website](https://shunsukesaito.github.io/PIFuHD/), [code](https://github.com/facebookresearch/pifuhd), [colab demo](https://colab.research.google.com/drive/11z58bl3meSzo6kFqkahMa35G5jmh2Wgt?usp=sharing)
    * recent and popular paper, the model requires only a single png image, also works if legs are missing or occluded
    * the output is an mp4 animation and 3D mesh output (obj file)
    * the colab demo contains useful tips on training our own images

2. **ExPose: Monocular Expressive Body Regression through Body-Driven Attention:** [website](https://arxiv.org/abs/2008.09062), [code](https://github.com/vchoutas/expose)
    * less popular than the paper above in terms of GitHub forks
    * focuses more on body and facial expression reconstruction

3. **Combining Implicit Function Learning and Parametric Models for 3D Human Reconstruction:** [website](https://arxiv.org/abs/2007.11432), [code](https://github.com/bharat-b7/IPNet)

4. **MakeHuman: A Review of the Modelling Framework:** [website](https://link.springer.com/chapter/10.1007/978-3-319-96077-7_23)
    * a review paper

5. **SiCloPe: Silhouette-Based Clothed People:** [website](https://vgl.ict.usc.edu/Research/siclope/)
    * an older and likely the first attempt to reconstruct 3D clothed human body with texture from a single image
    * no publicly available code can be found

6. **PIFu: Pixel-Aligned Implicit Function for High-Resolution Clothed Human Digitization:** [website](https://shunsukesaito.github.io/PIFu/), [code](https://github.com/shunsukesaito/PIFu)
    * also a very popular paper and has the useful colab demo 
    * the inputs are rendered images, however, the authors provide rendering code using free models in [RenderPeople](https://renderpeople.com/free-3d-people/)
    * original work of Pixel-Aligned Implicit Function for geometry and texture reconstruction, unifying sigle-view and multi-view methods, **PIFuHD** came later

7. **Monoport: Monocular Volumetric Human Teleportation :** [website](https://arxiv.org/abs/2007.13988), [code](https://github.com/Project-Splinter/MonoPort)
    * addresses a 3D human reconstruction via teleportation

***

### Virtual Try-On, Image Generation in Fashion, Style Transfer

1. **Learning to Dress 3D People in Generative Clothing:** [website](https://ps.is.mpg.de/publications/cape-cvpr-20), [code](https://github.com/QianliM/CAPE)
    * focuses on generating 3D images of dressed people

2. **M2E-Try On Net: Fashion from Model to Everyone:** [website](https://arxiv.org/abs/1811.08599)    
    * seems rather very basic, uses only 2D input images

3. **Joint Discriminative and Generative Learning for Person Re-identification:** [website](http://zdzheng.xyz/DG-Net/), [code](https://github.com/NVlabs/DG-Net)
    * introduces a GAN model that identifies the same people clothed differently, the dataset can be used for training our own GAN

4. **The Conditional Analogy GAN: Swapping Fashion Articles on People Images:** [website](https://arxiv.org/abs/1709.04695), [code](https://github.com/shaoanlu/Conditional-Analogy-GAN-keras)
    * 3-years old paper from Zalando research group
    * can't find most of the original code       

5. **Language Guided Fashion Image Manipulation with Feature-wise Transformations:** [website](https://arxiv.org/abs/1808.04000)
    * 2-years old paper, uses only 2D images for clothing swapping
    * uses NLP to detect similarity

6. **SwapNet: Image Based Garment Transfer:** [website](https://research.adobe.com/publication/swapnet-image-based-garment-transfer/), [code](https://github.com/andrewjong/SwapNet)
    * from Adobe, uses only 2D images for clothing swapping
    * official code has never been released

7. **CP-VTON+: Clothing Shape and Texture Preserving Image-Based Virtual Try-On:** [website](https://minar09.github.io/cpvtonplus/), [code](https://github.com/minar09/cp-vton-plus)
    * pretty recent paper (2020) but uses only 2D images of humans and clothes

8. **Towards Photo-Realistic Virtual Try-On by Adaptively Generating Preserving Image Content:** [website](https://arxiv.org/abs/2003.05863), [code](https://github.com/switchablenorms/DeepFashion_Try_On)
    * pretty recent paper (2020) but uses only 2D images of humans and clothes

9. **Learning to Transfer Texture from Clothing Images to 3D Humans:** [website](https://arxiv.org/abs/2003.02050), [code](https://github.com/aymenmir1/pix2surf)
    * promising paper, uses 3D images of humans and clothes

10. **SieveNet: A Unified Framework for Robust Image-Based Virtual Try-On:** [website](https://arxiv.org/abs/2001.06265), [code](https://github.com/levindabhi/SieveNet)
    * another promising paper although uses 2D images of humans and clothes from CP-VTON dataset


Other papers can be found by searching for `Image-to-Image Translation` keyword on `paperswithcode` [website](https://paperswithcode.com/task/image-to-image-translation)

***

### 3D Clothing Digitization

1. **Learning to Infer Implicit Surfaces without 3D Supervision:** [website](https://papers.nips.cc/paper/9039-learning-to-infer-implicit-surfaces-without-3d-supervision)
    * suggests an answer to the question of "how can we learn implicit function if we don't have 3D ground truth?"

2. **BCNet: Learning Body and Cloth Shape from A Single Image:** [website](https://arxiv.org/abs/2004.00214), [code](https://github.com/jby1993/BCNet)
    * automatically reconstructs garment and body shapes from a single near-front view RGB image
    * very limited code, have to contact the author

3. **DeepWrinkles: Accurate and Realistic Clothing Modeling:** [website](https://research.fb.com/publications/deepwrinkles-accurate-and-realistic-clothing-modeling/)
    * pretty good, albeit older paper, focuses on 3D surface deformation modeling, cloth simulation
    * official code has never been released

+ plus some other papers    
