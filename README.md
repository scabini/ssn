# SSN
Code for Spatio-Spectral Networks (SSN), a method to compute color-texture descriptors from images, from the paper "Spatio-spectral networks for color-texture analysis".

Preprint: https://arxiv.org/abs/1909.06446

Journal version: https://www.sciencedirect.com/science/article/pii/S0020025519310874


The code was implemented using Matlab and C++. 

The binary "mexa64" works on Linux 64 bit systems. If you are running a different system you need to compile the "SSN_getFeatureMaps.cpp" source via MEX, eg:

mex('SSN_getFeatureMaps.cpp')


If you use our method, please cite the work:

Scabini, Leonardo FS, Lucas C. Ribas, and Odemir M. Bruno. "Spatio-spectral networks for color-texture analysis." Information Sciences 515 (2020): 64-79.

@article{scabini2020spatio,
  title={Spatio-spectral networks for color-texture analysis},
  author={Scabini, Leonardo FS and Ribas, Lucas C and Bruno, Odemir M},
  journal={Information Sciences},
  volume={515},
  pages={64--79},
  year={2020},
  publisher={Elsevier}
}
