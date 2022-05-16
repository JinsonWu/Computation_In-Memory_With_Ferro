# Hardware Neural Network Based on Computation In-Memory with Ferroelectric Material
With the advancement of deep learning, the need for considerate computation grows significantly. It generally costs several days to train a robust model utilizing state-of-art convolutional neural network (CNN). People have dedicated to accelerate the training procedure in various aspects, e.g. hardware accelerating card, parallel computing strategies, and computation in-memory (CIM). Among them, CIM has the potential to eliminate redundant data access and is able to be adopted universally. This project attempts to implement logics according to this concept, therefore devising scalable circuit design. To further enhance the efficiency and capability of general use, I brought the novel ferroelectric material inside the semiconductor as gate region. This non-volatile material enabled state storage, which could be employed as neurons preserving weights. Theoretically, the designed convolution units could reduce 50% of execution time since it produced the desired result without complicated data fetching.

## Ferroeletric Material

<img src="./Negative_Capacitance.png" width="500" length="900">

### Metal-Ferro-Insulator-Metal


<img src="./Ferro_MFIM_MFIS.png" width="600" length="500"> 
<img src="./Ferro_Property.png" width="600" length="500">

### Metal-Ferro-Insulator-PolySi

<img src="./MFIM_MFIS_Conductance.png" width="350" length="400">   <img src="./MFIM_MFIS_Current.png" width="300" length="300">  

### Metal-Ferro-Metal-Insulator-PolySi


<img src="./MFMIS.png" width="500" length="600">   <img src="./MFMIS_MFIS.png" width="300" length="300">  


## Proposed Logic Circuit Design Optimization


### Modified SRAM


<img src="./Modified_SRAM.png" width="800" length="600">

### Convolution Unit


<img src="./Proposed_CIM_Unit.png" width="550" length="800">

## Contact Info
Author: Chun-Sheng Wu, MS student in Computer Engineering @ Texas A&M University  
Email: jinsonwu@tamu.edu  
LinkedIn: https://www.linkedin.com/in/chunshengwu/  

*This is project was implemented under the supervision of Dr. Jiun-In Guo & Dr. Tien-Shen Chao in National Chiao Tung University*
