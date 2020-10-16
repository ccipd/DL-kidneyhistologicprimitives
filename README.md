# Deep Learning-based segmentation of kidney histologic primitives on multiple stains

Contributors: Catherine Jayapandian, Yijiang Chen

In this work, we discuss how to train a U-Net based deep learning neural network, using PyTorch for segmentation of structurally normal histologic primitives from renal biopsies. 

The deep learning pipeline consists of 4 components:
1) Making the training/validation databases
2) Training a U-Net model
3) Visualizing results in the validation set
4) Generating deep learning segmentation output on the testing set. 

Please see attached source code and data samples that have been generated as part of this work for the segmentation of 6 structurally normal renal histologic primitives:
1) Glomerular Tuft 
2) Glomerular Unit (Tuft + Bowman's capsule)
3) Proximal Tubular segments
4) Distal Tubular segments
5) Arteries/Arterioles
6) Peritubular Capillaries

Multiple DL networks have been developed using biopsy images on multiple stains such as H&E, PAS, Trichrome and Silver. 

References:

Jayapandian, CP, Chen, Y, Janowczyk, AR, Palmer, MB, Cassol, CA, Sekulic, M, Hodgin, JB, Zee, J, Hewitt, SM, O’Toole, J, Toro, P, Sedor, JR, Barisoni, L, Madabhushi, A, “Development and evaluation of deep learning-based segmentation of histologic structures in the kidney cortex with multiple histologic stains”, Kidney Int. 2020 Aug 21:S0085-2538(20)30962-5. doi: 10.1016/j.kint.2020.07.044. Online ahead of print. [(PMID: 32835732)](https://pubmed.ncbi.nlm.nih.gov/32835732/). [data access](https://github.com/ccipd/DL-kidneyhistologicprimitives-data)
