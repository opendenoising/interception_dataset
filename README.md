This repository stores the dataset generated and used in _Electro-Magnetic Side-Channel Attack Through Learned Denoising and Classification, F. Lemarchand, F. Montreuil, C. Marlin, E. Nogues and M. Pelcat_. https://arxiv.org/abs/1910.07201



## Repository Structure
The files are stored as followed:

* train : 98722 clean/noisy pairs --> 3.9 Go
    * noisy : the intercepted samples --> 3.7 Go (around 700Mo per sub-directory)
        * 0-19999
        * 20000-39999
        * 40000-59999
        * 60000-79999
        * 80000-98722
    * ref : the clean samples --> 103 Mo
        * 0-19999
        * 20000-39999
        * 40000-59999
        * 60000-79999
        * 80000-98722
* test : 12563 clean/noisy pairs --> 537 Mo
    * noisy
    * ref
* val : 12325 clean/noisy pairs --> 522 Mo
    * noisy
    * ref
    
## Our work on complex noise restoration
We use this dataset as a case study for our research oriented on complex noise restoration. This repository is under the OpenDenoising GitHub organisation. 
You can find further information on our research in the repositories of that organisation. 

## Licensing

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

The dataset is free to use until you propagate the licence and you cite our paper using the following format:

@article{lemarchand2019electro,
  title={Electro-Magnetic Side-Channel Attack Through Learned Denoising and Classification},
  author={Lemarchand, Florian and Marlin, Cyril and Montreuil, Florent and Nogues, Erwan and Pelcat, Maxime},
  journal={arXiv preprint arXiv:1910.07201},
  year={2019}
}

## Contact
Florian Lemarchand : A@B.fr, A=florian.lemarchand and B = insa-rennes
