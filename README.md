# Fashion Style Generation: Evolutionary Search with Gaussian Mixture Models in the Latent Space <br>
[Imke Grabe](mailto:imgr@itu.dk)<sup>1</sup>, [Jichen Zhu](https://drexel.edu/westphal/about/directory/ZhuJichen/)<sup>1</sup>, [Manex Agirrezabal](https://manexagirrezabal.github.io)<sup>2</sup>

<sup>1</sup>IT University of Copenhagen, Denmark, <sup>2</sup>University of Copenhagen, Denmark

[ArXiv](http://arxiv.org/abs/2204.00592) | 
Code: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1rLI9bwRbu9H62Ca3fwSn9W0neuQ_X45M?usp=sharing)<br>

## Description

This repository contrains the code for the above mentioned paper. The project suggests to guide the generation of a P-GAN with a GMM via a genetic algorithm to generate images that correspond to fashion styles.

![teaser](https://github.com/imkegrabe/fashionstyle-generation-GMM/blob/main/images/ev-model.png)

## Requirements

Python 3.6.9 <br/> 
numpy <br/> 
matplotlib <br/> 
torch <br/> 
torchvision <br/> 
h5py <br/> 
sklearn <br/> 
pickle <br/> 
deap <br/> 
Pytorch GAN Zoo: https://github.com/facebookresearch/pytorch_GAN_zoo <br/> 
MMFashion: https://github.com/open-mmlab/mmfashion <br/> 
FashionGen dataset: https://fashion-gen.com/ <br/> 

## Dataset
Rostamzadeh, N., Hosseini, S., Boquet, T., Stokowiec, W., Zhang, Y., Jauvin, C., Pal, C.: Fashion-Gen: The Generative Fashion Dataset and Challenge. arXiv preprint arXiv:1806.08317 (2018)

I can't find fashion-gen dataset... I filled the form in the link above, but didn't get mail! <br/> 
I have searched a lot and finally found train and validation data! <br/> 
Here you go: <br/> 
https://drive.google.com/drive/folders/1DyiDRVvVc7HqDah9BQZGDCQW7KeiH6MY?usp=share_link


## Citation
--------
If you use our code for your research, please cite:
```bibtex
@inproceedings{grabe_fashion_2022,
	title = {Fashion {Style} {Generation}: {Evolutionary} {Search} with {Gaussian} {Mixture} {Models} in the {Latent} {Space}},
	booktitle = {International {Conference} on {Computational} {Intelligence} in {Music}, {Sound}, {Art} and {Design} : {EvoMUSART} 2022},
	author = {Grabe, Imke and Zhu, Jichen and Agirrezabal, Manex},
	year = {2022},
	pages = {16},
}
