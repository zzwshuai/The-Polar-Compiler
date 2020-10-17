To use the Polar Compiler, please choose the file polar_compiler_xx.pyc according to your Python version.

To generate architectures represented by formula F1(N,M) or F2(N,M), the code length N should be larger than 4, and the parallelism M should be larger than 2 and smaller than N. Both N and M should be powers of 2.

To generate architectures represented by formula F3(N,H), the code length N should be larger than 4, and the number of stages should range between 1 and log2(N). N should be a power of 2.

Please refer to my paper for more information.

@article{zhong2020polar,
  title={Polar compiler: Auto-generator of hardware architectures for polar encoders},
  author={Zhong, Zhiwei and Gross, Warren J and Zhang, Zaichen and You, Xiaohu and Zhang, Chuan},
  journal={IEEE Transactions on Circuits and Systems I: Regular Papers},
  volume={67},
  number={6},
  pages={2091--2102},
  year={2020},
  publisher={IEEE}
}
