# Multimodal Inference for 6D Camera Relocalization and Object Pose Estimation

[Mai Bui](http://campar.in.tum.de/Main/MaiBui), [Tolga Birdal](http://tbirdal.me/), [Haowen Deng](http://campar.in.tum.de/Main/HaowenDeng),  [Shadi Albarqouni](http://campar.in.tum.de/Main/ShadiAlbarqouni), [Leonidas Guibas](https://profiles.stanford.edu/leonidas-guibas) , [Slobodan Ilic](http://campar.in.tum.de/Main/SlobodanIlic) & [Nassir Navab](http://campar.in.tum.de/WebHome)

[Stanford University](http://www.stanford.edu) & [Technical University of Munich](http://www.tum.de) & Siemens AG

![Multimodal 6D Camera Pose Predictions](docs/framework.png)
In a highly ambiguous environment, similar looking views can easily confuse current camera pose regression models and lead to incorrect localization
results. Instead, given a query RGB image, our aim is to predict the possible modes as well as the associated uncertainties, which we model by the parameters
of Bingham and Gaussian mixture models.
