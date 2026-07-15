# Seasonal Station-Keeping of High-Altitude Balloons with Deep Reinforcement Learning





This repository documents research I contributed to as a **Software and Machine Learning Research Intern at the U.S. Naval Research Laboratory (NRL)** and as a co-author of the following publication:

> Tristan K. Schuler, Chinthan Prasad, Georgiy Kiselev, and Donald Sofge,  
> **“Seasonal Station-Keeping of Short Duration High Altitude Balloons Using Deep Reinforcement Learning,”**  
> *2025 IEEE Aerospace Conference*, 2025.  
> DOI: [10.1109/AERO63441.2025.11068667](https://doi.org/10.1109/AERO63441.2025.11068667)

## Read the Paper

<p align="center">
  <a href="paper/NRLPaper.pdf">
    <img src="assets/paper-preview.png" alt="First page of the published paper" width="700">
  </a>
</p>

<p align="center">
  <strong><a href="paper/NRLPaper.pdf">Open the PDF</a></strong>
  &nbsp;|&nbsp;
  <strong><a href="https://doi.org/10.1109/AERO63441.2025.11068667">View the official publication</a></strong>
</p>

## Research Overview

The project investigated whether deep reinforcement learning could enable short-duration, altitude-controlled high-altitude balloons to remain near a target region despite dynamic and partially observable wind conditions.

The research combined:

- Deep Q-Network (DQN) training for simulated balloon station-keeping.
- A custom simulation environment using ERA5 wind forecasts as observations.
- Synthetic, higher-resolution wind fields generated from historical radiosonde measurements.
- Hyperparameter optimization and large-scale experiment tracking.
- Evaluation across seasonal wind conditions using time-within-region and forecast-diversity metrics.

The published results show that trained agents could remain within a 50 km target region for approximately half of a simulated flight under favorable conditions, while performance varied substantially by season and wind diversity.

## My Contributions

During my NRL internship, I contributed to the machine-learning and data-processing work supporting this research, including:

- Implementing and evaluating reinforcement-learning models in Python and PyTorch.
- Running and analyzing large-scale training experiments using Optuna, Weights & Biases, and TensorBoard.
- Improving simulation and training efficiency through numerical interpolation work in NumPy.
- Contributing to data-generation workflows for higher-resolution synthetic wind fields.
- Supporting experiment analysis, visualization, and preparation of the published article.


## Source Code Availability

The publication does not provide a public source-code repository. The research code and associated internal materials are not included here and are not available for redistribution by the repository owner.

## Technologies and Methods

- Python and NumPy
- PyTorch
- Deep Q-Networks (DQN)
- Reinforcement learning
- Optuna
- Weights & Biases
- TensorBoard
- ERA5 reanalysis data
- Radiosonde data processing
- Time-series and spatial interpolation
- Scientific visualization

## Citation

```bibtex
@inproceedings{schuler2025seasonal,
  title     = {Seasonal Station-Keeping of Short Duration High Altitude Balloons Using Deep Reinforcement Learning},
  author    = {Schuler, Tristan K. and Prasad, Chinthan and Kiselev, Georgiy and Sofge, Donald},
  booktitle = {2025 IEEE Aerospace Conference},
  year      = {2025},
  doi       = {10.1109/AERO63441.2025.11068667}
}
```

## Contact

For questions about my publicly discussable contributions or professional experience, connect with me on [LinkedIn](https://www.linkedin.com/in/georgiy-kiselev2002/).
