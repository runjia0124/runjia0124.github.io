---
title: "1.	Enhancing Underwater Image via Fusion and Contrastive Learning"
excerpt: "<br/><img src='/images/display.png'>"
collection: portfolio

---

### Highlights
* Propose a GAN structure with WaterNet (TIP’20) as its generator;

* Utilize a gated fusion mechanism to unify desirable features from white balance,

  histogram equalization, and gamma correction by learning three confidence maps;

* The combination of GAN loss and contrastive loss can recover the image through both 
  pixel and feature level;

* Quantitative results indicate a 15% rise on PSNR against SOTA methods
  
  
  
  

### Flowchart

![](https://raw.githubusercontent.com/runjia0124/runjia0124.github.io/master/img/uie.png)

### Representative Results

![](https://raw.githubusercontent.com/runjia0124/GSR-learning/main/archive/display.png)
The generator part is a gated fusion network, which fuses the inputs with the predicted confidence
maps to achieve the enhanced result.

The inputs are composed of several groups of pre-enhanced results based on traditional methods, including white balance (WB), histogram equalization (HE), and gamma correction(GC).
The inputs are first transferred to the refined inputs by the Feature Transformation Units (FTUs) and then the confidence
maps are predicted. At last, the enhanced result is achieved by fusing the refined inputs and the corresponding confidence maps.

### Reach me

E-mail: junko.lin@yahoo.com

