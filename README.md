# Electrode_Net

# Electrode Net: tailoring deep learning with signed distance field for fast and accurate multiscale design of porous electrodes

**Pengzhu Lin**<sup>a,1</sup>, **Jing Sun**<sup>a,1</sup>, **Yinglun Tang**<sup>b</sup>, **Jiayou Ren**<sup>a</sup>, **Xiaosa Xu**<sup>a</sup>, **Jin Li**<sup>a</sup>, **Changxiang He**<sup>a</sup>, **Shuaibin Wan**<sup>c</sup>, **Wenjia Li**<sup>b</sup>, **Tianshou Zhao**<sup>a,b\*</sup> <br/>

<sup>a</sup> Department of Mechanical and Aerospace Engineering, The Hong Kong University of Science and Technology, Hong Kong, China <br/>
<sup>b</sup> Department of Mechanical and Energy Engineering, Southern University of Science and Technology, Shenzhen, China <br/>
<sup>c</sup> Shenzhen Research Institute of Big Data, Shenzhen, China <br/>
<sup>\*</sup> Corresponding author: [Prof. T.S. Zhao](https://scholar.google.com/citations?user=0mUWHUQAAAAJ&hl=en) <br/>
<sup>\*</sup> Corresponding author: [Prof. W.J. Li](https://scholar.google.com/citations?useruser=pI-WVJMAAAAJ&hl=en) <br/>
<sup>1</sup> These authors contributed equally to this work. <br/>

## Abstract
Designing novel porous electrodes with desirable merits is the key to advancing next-generation high-performing flow cells such as fuel cells, water electrolyzers, and flow batteries. However, engineering porous electrodes rationally and methodically remains challenging because it demands an in-depth understanding of their complex microstructures with extremely high computational costs. In this study, we develop a tailored deep learning framework (named “Electrode Net”, a 3-dimensional convolutional neural network with signed distance field) to efficiently and accurately predict the anisotropic transport properties of porous electrodes. A comprehensive dataset consisting of 15,433 real and generated geometric samples and their corresponding anisotropic transport properties is constructed, using an experimentally and numerically validated pore-scale model. Electrode Net can significantly accelerate the design of porous electrodes by reducing the computational cost by up to 96% and with precise prediction (R-squared range: 0.95–0.99) of the porosity, tortuosity, and permeability. The outstanding generalizability of our model is further confirmed by accurate prediction of three practical flow cell electrodes in fuel cells, water electrolyzers, and flow batteries. Furthermore, we demonstrate a practical multiscale electrode design by incorporating the pore-scale anisotropic transport properties from Electrode Net into cell-scale simulations, enabling the rational and efficient optimization of three essential parameters of the gas diffusion layers in proton exchange membrane fuel cells.
