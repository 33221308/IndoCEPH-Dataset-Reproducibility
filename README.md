
# IndoCEPH Dataset Reproducibility

This repository provides reproducibility materials supporting the IndoCEPH dataset descriptor.

## Repository contents

- `config/` – dataset and training configuration files
- `splits/` – fixed dataset split lists used in the experiments
- `results/` – evaluation results underlying the technical validation
- `weights/` – information on the trained YOLOv9 model weights

## Dataset

The IndoCEPH dataset contains 1,316 lateral cephalometric radiographs annotated with 17 anatomical landmarks.

The image dataset and annotations are archived separately in Figshare.

## Model

Technical validation was performed using YOLOv9.

## Model weights

The trained model weight (`best.pt`) is provided separately because of the GitHub file-size limitation.

## Code

Training and inference were performed using the YOLOv9 implementation. Links to the corresponding scripts are provided in this repository.
