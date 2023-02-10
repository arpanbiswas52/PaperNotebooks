# This repository contains supplementary notebooks for different papers
**Note**: <i> For large notebooks which github can not open, please download the script (.ipynb) and open the file in Google colab to see the scripts and analysis </i>

**Paper: 
Biswas, A.; Ziatdinov, M.; Kalinin, S. V. Combining Variational Autoencoders and Physical Bias for Improved Microscopy Data Analysis. arXiv February 8, 2023. https://doi.org/10.48550/arXiv.2302.04216**

Notebook/Code link: 

**Script for custom ELBO loss:**

https://github.com/arpanbiswas52/PaperNotebooks/blob/main/custom_traceELBO.py

**Script for custom SVI class and trainner class:**

https://github.com/arpanbiswas52/PaperNotebooks/blob/main/customsvi.py

https://github.com/arpanbiswas52/PaperNotebooks/blob/main/customsvitrainer.py

**Example: STEM of Sm-doped BiFeO3**

**standard sh-VAE training (without implementing physical constraint to maximize the smoothness of latent space)**

<i> Distorted 2D latent manifolds </i>

![image](https://user-images.githubusercontent.com/19354142/217877970-f302e84e-0ea4-4a1c-bb8c-556f4803e574.png)

**standard sh-VAE training (without implementing physical constraint to maximize the smoothness of latent space)**

<i> No distortion </i>

![image](https://user-images.githubusercontent.com/19354142/217877767-0e985143-bc04-4dcc-84ff-b17263f6e9f5.png)

----------------------------------------------------------------------------------------------------------------------------------------------------
**Paper: 
Biswas, A., Rama Vasudevan, Maxim Ziatdinov, Sergei V. Kalinin " Optimizing Training Trajectories in Variational Autoencoders via Latent Bayesian Optimization Approach" 2023 Mach. Learn.: Sci. Technol. 4 015011 https://doi.org/10.1088/2632-2153/acb316**

Notebook/Code link: 

** Notebook for MNIST dataset:**

https://github.com/arpanbiswas52/PaperNotebooks/blob/main/LatentBO_jrVAE_MNIST(Notebook).ipynb

** Notebook for experimental plasmonic nanoparticles dataset:**

https://github.com/arpanbiswas52/PaperNotebooks/blob/main/LatentBO_jrVAE_PlasmonicNano(Notebook).ipynb

**Example: MNIST**

**suboptimal tuning of joint-rotationally invariant variational autoencoder**

<i> Overlapping of digits classifications in 2D latent manifolds </i>

![image](https://user-images.githubusercontent.com/19354142/217884020-d904f8be-340f-44ab-8962-4d9ea6f56d56.png)

**optimal tuning of joint-rotationally invariant variational autoencoder through latent Bayesian optimization**

<i> classification and disentanglement of all digits in 2D latent manifolds </i>

![image](https://user-images.githubusercontent.com/19354142/217883808-a98a2263-ebb3-4958-a5ac-f0246398bf86.png)

----------------------------------------------------------------------------------------------------------------------------------------------------

**Paper: 
Arpan Biswas, Anna N. Morozovska, Maxim Ziatdinov, Eugene A. Eliseev, and Sergei V. Kalinin “Multi-objective Bayesian optimization of ferroelectric materials with interfacial control for memory and energy storage applications” Journal of Applied Physics 130, 204102 (2021); https://doi.org/10.1063/5.0068903**

Notebook/Code link: 

https://github.com/arpanbiswas52/MOBO_AFI_Supplements

**Example (PZO): Exploration over parameter space containing FE and AFE hysteresis loops:**

**Building Pareto front to maximize energy storage and loss with Multi-objective Bayesian optimization**

![image](https://user-images.githubusercontent.com/19354142/217886178-a0f51fd1-ab19-45ef-af64-d197a4ce24f2.png)

----------------------------------------------------------------------------------------------------------------------------------------------------

**Paper: 
Anna N. Morozovska, Eugene A. Eliseev, Arpan Biswas, Hanna V. Shevliakova, Nicholas V. Morozovsky, Sergei V. Kalinin “Chemical control of polarization in thin strained films of a multiaxial ferroelectric: phase diagrams and polarization rotation” Phys. Rev. B 105, 094112 – Published 23 March 2022; https://doi.org/10.1103/PhysRevB.105.094112**

Notebook/Code link: 

https://github.com/arpanbiswas52/PaperNotebooks/blob/main/BTO_GPexplore.ipynb

**Paper: 
Anna N. Morozovska, Eugene A. Eliseev, Arpan Biswas, Nicholas V. Morozovsky, and Sergei V. Kalinin “Effect of Surface Ionic Screening on Polarization Reversal and Phase Diagrams in Thin Antiferroelectric Films for Information and Energy Storage” Phys. Rev. Applied 16, 044053 – Published 27 October 2021; https://doi.org/10.1103/PhysRevApplied.16.044053**

Notebook/Code link: 

https://github.com/arpanbiswas52/PaperNotebooks/blob/main/films_PZO_GPexplore.ipynb

----------------------------------------------------------------------------------------------------------------------------------------------------

<i> Please feel free to use these notebooks. Please cite the relevant papers and email at **arpanbiswas52@gmail.com** or **biswasa@ornl.gov** for any further questions </i>
