# Inception-UNet-GAN-for-Snow-and-Rain-Removals

Ibrahim Kajo · Mohamed Kas · Yassine Ruichek · Nidal Kamel

Submitted to International Journal of Computer Vision 

Paper link: 
##
<p>
This work contributes to the Computer Vision commnunity with an End-to-End GAN for rain and snow removal and with a realistic snow dataset for evaluating the SOTA techniques with clean background.
</p>
<p>

## Abstract 
The superior performance introduced by deep learning approaches in removing atmospheric particles such as snow and rain from a single image; favors their usage over classical ones. However, deep learning-based approaches still suffer from challenges related to the particle appearance characteristics such as size, type, and transparency. Furthermore, due to the unique characteristics of rain and snow particles, single network based deep learning approaches struggle in handling both degradation scenarios simultaneously.  In this paper, a global framework that consists of two Generative Adversarial Networks (GANs) is proposed where each handles the removal of each particle individually. The architectures of both desnowing and deraining GANs introduce the integration of a feature extraction phase with the classical U-net generator network which in turn enhances the removal performance in the presence of severe variations in size and appearance. Furthermore, a realistic dataset that contains pairs of snowy images next to their groundtruth images estimated using a low-rank approximation approach; is presented. The experiments show that the proposed desnowing and deraining approaches achieve significant improvements in comparison to the state-of-the-art approaches when tested on both synthetic and realistic datasets.
  

## SVD-based ground truth generation of realistic snow images 
<details><summary> Realistic Snow Dataset description</summary>
<p>
 A test subset that shows diverse background scenes (forests, buildings, and streets) with different snow densities are constructed. Using the aforementioned groundtruth generation scheme, we generate 83 pairs of snowy images of size $960 \times 540$ along with their corresponding groundtruth images. 

</p>
</details>
  
<details><summary> Realistic Snow Dataset download</summary>
<p>

  link : https://drive.utbm.fr/s/CJTsFZgGqMMCRin

</p>
</details>
    
## Proposed framework 
Coming soon
