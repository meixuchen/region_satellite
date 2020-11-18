# Infrastructure For Reproducibility

[Meixu Chen]() [[]()]<sup>1</sup>
[Dominik Fahrner]() [[`@DominikFahrner`](https://twitter.com/DominikFahrner)]<sup>2</sup>
[Dani Arribas-Bel](http://darribas.org) [[`@darribas`](https://twitter.com/darribas)]<sup>1</sup>
[Francisco Rowe](http://www.franciscorowe.com) [[`@fcorowe`](http://twitter.com/fcorowe)]<sup>1</sup>

<sup>1</sup> *Geographic Data Science Lab, University of Liverpool, Liverpool, United Kingdom*
<sup>2</sup> *Institute for Risk and Uncertainty, University of Liverpool, Liverpool, United Kingdom*

## Build a Docker image of our repository

Go to: https://mybinder.org/, then: https://github.com/meixuchen/region_satellite. Click launch. 

It will take a while to build a Docker image in your local machine the first time. Once an image has already been built, it will not be rebuilt the second time. 

Alternatively, go to: https://mybinder.org/v2/gh/meixuchen/region_satellite/HEAD to interact directly with the Binder we created and shared in the server.

## Interacting with the notebook

As the image has already been built, a JupyterHub server will host you to our repository's content. You can open the notebook and start reproducing our results. 

You are good to go to reproduce the paper!

**Note**: The image downloading section of the notebook will not work on Binder, so please skip the downloading and cropping sections and continue from the mosaicking section. 


[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/meixuchen/region_satellite/master)
