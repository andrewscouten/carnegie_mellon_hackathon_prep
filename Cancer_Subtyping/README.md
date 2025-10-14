# Cancer Subtyping

## Literature Review

### Example

[1]
[He, K., Zhang, X., Ren, S., & Sun, J. (2016). *Deep residual learning for image recognition.* In *Proceedings of the IEEE conference on computer vision and pattern recognition (CVPR)* (pp. 770–778).](https://doi.org/10.1109/CVPR.2016.90)

  - **Summary:** ResNet (Residual Network) is a deep convolutional neural network architecture designed to overcome the degradation problem that occurs when neural networks become very deep. In traditional CNNs, as more layers are added, training accuracy often saturates and then degrades due to vanishing/exploding gradients. ResNet solved this by introducing residual learning, which allows layers to learn modifications (residuals) to the input rather than entire transformations.

## Cancer Subtyping 

Looking for recent (2025) papers with cancer subtyping, open source, deep learning, federated learning...

### [1] [A Review of Advanced Deep Learning Methods of Multi-Target Segmentation for Breast Cancer WSIs](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10979932)

- **Topics:** Breast Cancer, Segmentation, Multi-Target
- **Summary:** Offers a survey of segmentation methods and datasets for breast cancer, breaking down each dataset and its use. A great resource for similar tasks to help us pick and decipher various known datasets.

### [2] [Subtype-GAN: a deep learning approach for integrative cancer subtyping of multi-omics data](https://academic.oup.com/bioinformatics/article/37/16/2231/6143031)
- **Summary**: They used **deep representation learning (a MIMO GAN)** to fuse multi-omics (CNV, mRNA, miRNA, DNA methylation, and other omics data), then did **undepervised subtype discovery** via **consensus clustering over a Gaussian Mixture Model (GMM)**, identifying clincally meaningful cancer subtypes across 10 TCGA cohorts (BRCA, BLCA, KIRC, GBM, LUAD, PAAD, SKCM, STAD, UCEC and UVM, samples ~ 4154).
- - **Quick Knowledge Check**
  - **AE** stands for autoencoder which is a type of artificial neural network used to learn efficient codings of unlabeled data. It's a deterministic encoder -> decorder. Compact latent space
  - **VAE** stands for Variational autoencoder and is a probabilistic AE. Smooth latent space
  - **GAN** is generative adversarial network. Given a training set, this technique learns to generate new data with the same statistics as the training set. 
- **My thoughts**
- - I am not familiar with unsupervised models so I cannot give critiques to the model itself and the choices made when developing the model.
  - With that said I do wonder, as the model was trained only on TCGA data, how well it will do on different cohorts and datasets.
  - I do think this is a good example of how to use machine learning skills outside of the prior hackathon's theme. 
  - I also had a thought that although we may not use Subtype-GAN maybe we can steal the ideas and apply it to Andrew's knowledge graph.
  - - Add an unsupervised layer (AGAIN DO NOT KNOW ANYTHING ABOUT UNSUPERVISED LEARNING BUT WILLING TO LEARN)... Again do not know if necessary. 

### [3] [DeePathNet: A Transformer-Based Deep Learning Model Integrating Multiomic Data with Cancer Pathways](https://pubmed.ncbi.nlm.nih.gov/39530738/)
- Tera is on fire...

### [4] [Biological Knowledge Graph-Enhanced Cancer State Prediction Network with Adjustable Connections](https://academic.oup.com/bioinformatics/article/39/9/btad570/7273783)
- Sooo I am sorta excited about this one
  
### [5] [Breast Cancer Classification with Various Optimized Deep Learning Methods](https://pmc.ncbi.nlm.nih.gov/articles/PMC12293705/#sec1-diagnostics-15-01751)

### [6] [Federated Deep Learning Enables Cancer Subtyping by Proteomics](https://pubmed.ncbi.nlm.nih.gov/40488620/)

