# NeRF on mydata
Copy from https://github.com/yenchenlin/nerf-pytorch and train on mydata

### Dataset
We use a dataset named mydata stored in the data/nerf_synthetic directory. The data is randomly split into a training set (80%) and a testing set (20%) to ensure fair evaluation.

### Quick Start

```
python run_nerf.py --config configs/{DATASET}.txt
```

To test NeRF trained on different datasets: 

```
python run_nerf.py --config configs/{DATASET}.txt --render_only
```
replace `{DATASET}` with `trex` | `horns` | `flower` | `fortress` | `lego` | etc.

## Citation
```
@misc{lin2020nerfpytorch,
  title={NeRF-pytorch},
  author={Yen-Chen, Lin},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished={\url{https://github.com/yenchenlin/nerf-pytorch/}},
  year={2020}
}
```
