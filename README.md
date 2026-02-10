# DeepLearning_2025-26_KhushiSharma
This repository contains course work, projects, experiments, and notes for "Deep Learning" (Academic year 2025-26) by Khushi Sharma. It is organized to help reproduce experiments, run training and evaluation pipelines, and inspect results.

## Contents

- notebooks/ - Jupyter notebooks used for exploration and demonstration
- src/ - source code for models, datasets, training and evaluation scripts
- data/ - small example datasets or scripts to download larger datasets
- experiments/ - saved checkpoints, logs, and experiment configs
- reports/ - results, plots, and short write-ups

## Getting started

Prerequisites:

- Python 3.8+ (recommended 3.9 or 3.10)
- pip or conda for package management
- GPU with CUDA (optional but recommended for training)

Quick setup (using virtualenv):

```bash
python -m venv venv
source venv/bin/activate  # on Windows: venv\Scripts\activate
pip install -r requirements.txt
```

If requirements.txt is not present, install common packages used in this repo:

```bash
pip install torch torchvision matplotlib numpy pandas jupyterlab tqdm
```

## Usage

- Notebooks: open `notebooks/` with JupyterLab or Jupyter Notebook and run cells interactively.
- Training: example training script `python src/train.py --config experiments/configs/example.yaml` (adjust path/flags as needed).
- Evaluation: `python src/evaluate.py --checkpoint experiments/checkpoints/example.ckpt`.

Adjust configurations in `experiments/configs/` as required.

## Reproducing experiments

1. Prepare dataset (see `data/README.md` or the dataset-specific scripts in `data/`).
2. Modify or create a YAML config file under `experiments/configs/`.
3. Run training and save checkpoints to `experiments/checkpoints/`.
4. Use evaluation scripts or notebooks in `reports/` to generate metrics and plots.

## Contributing

Contributions are welcome. Open an issue describing the bug or enhancement and submit a pull request. Keep code style consistent and include tests or notebooks demonstrating changes.

## License

This project is released under the MIT License — see LICENSE for details.

## Contact

Khushi Sharma — github: @khushisharmacs28-cloud

Notes:
- Replace placeholder scripts and configuration examples with the actual scripts in the repo as they are added.
- If you want, tell me how you'd like the README tuned (more tutorial-style, minimal, detailed experiment logs) and I will update it.
