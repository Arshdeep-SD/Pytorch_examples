# PyTorch Examples

Deep-learning coursework notebooks, mostly PyTorch (one uses JAX).

| Notebook | Contents |
|---|---|
| `hw7.ipynb` | Neural network from scratch in NumPy (activations, backprop) |
| `hw8_1.ipynb` | MLP classifier on MNIST |
| `hw8_2.ipynb` | MLPs with dropout on Fashion-MNIST |
| `hw8_3.ipynb` | MLP on CIFAR-10 |
| `hw9.ipynb` | Transfer learning with a pretrained ResNet-34 on an image dataset |
| `dataset_generators.ipynb` | 2D toy datasets (pinwheel, etc.) |
| `final.ipynb` | VAE and GAN trained on 2D toy datasets |
| `model_info.ipynb` | Generator / discriminator architecture visualisation (torchviz) |
| `score_matching.ipynb` | Score matching on a checkerboard distribution (JAX) |
| `final_project.ipynb` | RNN on CSV time-series activity data |
| `final_project_2.ipynb` | Feature engineering and classical classifiers on the same data |

## Running

```bash
pip install torch torchvision numpy scipy pandas matplotlib seaborn scikit-learn h5py jupyter
jupyter notebook
```

Datasets (MNIST HDF5, `Data/`, `images/`) aren't included in the repo.
