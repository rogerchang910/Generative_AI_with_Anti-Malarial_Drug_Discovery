# Generative AI with Anti-Malarial Drug Discovery
## Abstract
Malaria is one of the most severe infectious diseases in the world. Due to the spread of drug resistance to the marketed antimalarial drugs, the discovery and development of new antimalarial drugs is one of the most pressing challenges. QSAR plays a crucial role in the field of drug design; however, building QSAR models will involve applying a descriptor selection algorithm to find descriptors from large and diverse datasets. In addition, the descriptors are hard to explain as they are related to the target activity and are indirect representations of chemical structures. As a result, it is difficult and time-consuming to find descriptors to build QSAR models from large datasets. 

This project takes the efforts in descriptor-free models one step forward and tries using Gated Recurrent Unit (GRU) on SMILES and SELFIES, and compares the result with a QSAR descriptor and ECFP-trained Random Forest model as a control comparison. The result of this study can indicate whether the descriptor-free model is viable for large datasets thus saving time and computational power to generate descriptors.

Referring to the paper "[Descriptor Free QSAR Modeling Using Deep Learning With Long Short-Term Memory Neural Networks](https://www.frontiersin.org/articles/10.3389/frai.2019.00017/full)" published by Chakravarti SK and Alla SRM, we take a further step to develop the model using the GRU component to achieve a comparable result.

## Contributors
Roger Chang, Ayush Shetty
