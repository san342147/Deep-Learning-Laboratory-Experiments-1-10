# Deep Learning Laboratory

This repository contains the Colab notebook for **Deep Learning Experiments 1–10 and the Mini Project**. The notebook includes experiment instructions, Python code, captured execution outputs, plots, and a final audit/download workflow.

## Notebook

Open `Deep_Learning_Laboratory_Experiments_1-10_and_Mini_Project.ipynb` in Google Colab. A GPU runtime is recommended for the CNN, image-generation, and GAN experiments.

1. Choose **Runtime → Change runtime type → T4 GPU** when available.
2. Run the notebook from the first cell in order; the setup cell installs its additional packages.
3. Confirm the final audit passes, then run the last packaging cell to download the generated datasets, models, metrics, and plots ZIP from the active Colab runtime.

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

The notebook uses a mix of complete datasets and explicitly documented lab-sized subsets to keep Colab runs practical. The dataset manifest and code describe the sources and subset sizes. Downloaded runtime files under `/content/Deeplearning` are temporary; preserve the generated ZIP if you need model and dataset artifacts outside the current session.

## Reproducibility

The notebook uses fixed seeds where applicable and records package/runtime versions. Training results can vary with runtime hardware, library versions, and data-source availability. Review each experiment’s output rather than assuming a cell completed successfully; run the final audit before considering the lab complete.

## Attribution

Prepared as a personal coursework repository from the Colab laboratory notebook. Dataset and library credits are recorded in the notebook and its manifest.
