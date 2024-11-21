# Res-ViT
A Novel Vision Transformer with Probabilistic Residual in Self-attention
Note: 
1. MATLAB runtime engine for python is required to run the proposed algorithm
2. To generate results, saved_model folder should contains the trained models corresponding to the dataset
3. No trained models have been included with this repo to due to storage constraints. 
4. First run Proposed_ViT_attnFDSourse.ipynb to train the source model
5. Then run Proposed_ViT_cwru.ipynb, Proposed_ViT_cwru_noise.ipynb, Proposed_ViT_pbu.ipynb, Proposed_ViT_pbu_noise.ipynb to train the models
6. Then run GenResultsAll_cwru_ims.ipynb, GenResultsAll_cwru_ims_N.ipynb, GenResultsAll_pbu.ipynb, GenResultsAll_pbu_N.ipynb to generate results for all the cases.

Download following file and save the saved_models.

This is required to run the code.

https://drive.google.com/file/d/1EcKPSebDvc3KlSQOduF1UyHpa56Rv1cD/view?usp=sharing

The above code is the official implementation of the preprint "A Novel Vision Transformer with Probabilistic Residual in Self-attention for Pattern Recognition"
Its older version is as follow:
https://arxiv.org/abs/2306.01594

If this code or any part of the code is used for further research, please cite:
@misc{sharma2023novelvisiontransformerresidual,
      title={A Novel Vision Transformer with Residual in Self-attention for Biomedical Image Classification}, 
      author={Arun K. Sharma and Nishchal K. Verma},
      year={2023},
      eprint={2306.01594},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2306.01594}, 
}
