## 📁 Repository Structure

```bash
├── configuration/
│   └── model_configuration.json           # Model configuration
├── data_preprocessing/
│   └── data_preprocessing.py              # Data cleaning & preprocessing
├── evaluation_metrics/
│   └── evaluation_metrics_calculator.py   # Custom evaluation metrics
├── figures/                               # Framework & uncertainty visualizations
├── model/
│   ├── bayesian_encoder.py                # Hierarchical Bayesian encoder
│   ├── calibration.py                     # Adaptive calibration
│   ├── classification_network.py          # Disease classification agent
│   ├── consistency_validation.py          # Consistency validation agent
│   ├── enhanced_bayesian_framework.py     # Full model integration
│   ├── multi_objective_loss.py            # Multi-objective loss
│   └── variational_linear.py              # Variational linear layers
├── main.py                                # Entry point for training/testing
├── requirements.txt                       # Environment dependencies
└── README.md                              # Project documentation
```

## 🚀 Quick Start

### Installation
```bash
# Clone repository
git clone https://github.com/dawoodrehman44/ICASSP-2026.git
cd ICASSP-2026

# Create environment
conda create -n bayesian_med python=3.8
conda activate bayesian_med

# Install dependencies
pip install -r requirements.txt

