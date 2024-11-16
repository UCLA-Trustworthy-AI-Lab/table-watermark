# Table-Watermark

This repository contains example code for watermarking generative tabular data, as described in the paper:

**He, H., Yu, P., Ren, J., Wu, Y. N., & Cheng, G. (2024). Watermarking Generative Tabular Data.**  
[arXiv:2405.14018](https://arxiv.org/abs/2405.14018)

## Features

- Embed and verify watermarks in generative tabular data.
- Evaluate model performance on generated data with metrics **ROC-AUC Score** and **Wasserstein Distance**.
- Conduct experiments on multiple real-world tasks.

## Folder Structure

Ensure your data is organized as follows:

<base_path>/<task>/X_num_train_raw_syn_<i>.npy

- `<base_path>`: Root directory for your experiments.
- `<task>`: Task name (e.g., `gesture`, `house`).
- `X_num_train_raw_syn_<i>.npy`: Generated data file from the model.

### Citation

If you use this code, please cite:

@article{he2024watermarking,
  title={Watermarking Generative Tabular Data},
  author={He, H. and Yu, P. and Ren, J. and Wu, Y. N. and Cheng, G.},
  journal={arXiv preprint arXiv:2405.14018},
  year={2024}
}

