# Deep Learning Laboratory

This repository contains the original all-in-one Colab notebook plus **a separate standalone notebook for each of Experiments 1–10 and the Mini Project**. Each experiment notebook includes the shared dependency/runtime/data setup, its experiment instructions and code, captured execution outputs, plots, and an output check.

## Notebook

Open `DL_Exp01.ipynb` through `DL_Exp10.ipynb` or `DL_Mini_Project.ipynb` in Google Colab to run a single lab section. `Deep_Learning_Laboratory_Experiments_1-10_and_Mini_Project.ipynb` preserves the complete original sequence. A GPU runtime is recommended for the CNN, image-generation, and GAN experiments.

1. Choose **Runtime → Change runtime type → T4 GPU** when available.
2. In a standalone notebook, run its setup cells in order; setup installs packages and imports the lab datasets before the experiment cell.
3. Confirm the notebook's output check passes. For a complete set of generated files, use the original all-in-one notebook's final audit and ZIP packaging cells.

## Contents

- Experiment 1: Three-layer neural network from scratch (MNIST)
- Experiment 2: MLP configurations and activation functions
- Experiment 3: SGD with momentum versus Adam
- Experiment 4: CNN and learned-filter visualization
- Experiment 5: VGG, ResNet, and GoogLeNet
- Experiment 6: Bidirectional RNN versus feedforward network
- Experiment 7: Image captioning
- Experiment 8: Variational autoencoder
- Experiment 9: LSTM text generation
- Experiment 10: GAN with quantitative evaluation
- Mini project: CIFAR-10 baseline MLP versus advanced CNN

Each single-experiment notebook is named `DL_ExpNN.ipynb`; the CIFAR-10 mini project is `DL_Mini_Project.ipynb`. The setup cells are intentionally repeated so each file can be opened and run independently. Dataset setup imports the course's documented lab datasets and may take several minutes.

The notebook uses a mix of complete datasets and explicitly documented lab-sized subsets to keep Colab runs practical. The dataset manifest and code describe the sources and subset sizes. Downloaded runtime files under `/content/Deeplearning` are temporary; preserve the generated ZIP if you need model and dataset artifacts outside the current session.

## Reproducibility

The notebook uses fixed seeds where applicable and records package/runtime versions. Training results can vary with runtime hardware, library versions, and data-source availability. Review each experiment’s output rather than assuming a cell completed successfully; run the final audit before considering the lab complete.

## Attribution

Prepared as a personal coursework repository from the Colab laboratory notebook. Dataset and library credits are recorded in the notebook and its manifest.
