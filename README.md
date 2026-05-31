# Breast Cancer Detection via Thermography and Mammography

A Self-Supervised Dual-Modality Framework for Breast Cancer Detection via Thermography and Mammography with Gated Fusion

## 📋 Overview

This repository contains a comprehensive framework for breast cancer detection that leverages both thermal imaging (thermography) and mammography data. The approach uses self-supervised learning with a gated fusion mechanism to effectively combine information from both modalities for improved diagnostic accuracy.

## 🎯 Key Features

- **Dual-Modality Approach**: Combines thermography and mammography imaging for robust cancer detection
- **Self-Supervised Learning**: Reduces dependency on large labeled datasets
- **Gated Fusion Mechanism**: Intelligently combines features from both imaging modalities
- **State-of-the-art Performance**: Achieves high sensitivity and specificity in breast cancer detection

## 📊 Project Structure

```
Breast-Cancer-Detection-via-Thermography-and-Mammography/
├── README.md
├── notebooks/                    # Jupyter Notebooks with analysis and models
├── data/                         # Dataset storage (if applicable)
├── models/                       # Trained models
└── results/                      # Experimental results and visualizations
```

## 🔬 Methodology

### Imaging Modalities

1. **Thermography**: Captures infrared thermal patterns that may indicate abnormal vascularization associated with tumors
2. **Mammography**: Standard X-ray imaging for structural visualization of breast tissue

### Approach

- **Self-Supervised Pre-training**: Models are pre-trained on unlabeled data to learn robust representations
- **Gated Fusion**: A learnable gating mechanism that weights and combines features from both modalities
- **End-to-End Learning**: Unified framework for classification and detection tasks

## 🚀 Getting Started

### Prerequisites

- Python 3.7+
- Jupyter Notebook
- PyTorch or TensorFlow
- NumPy, Pandas, Scikit-learn
- OpenCV, Matplotlib, Seaborn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/albrud199/Breast-Cancer-Detection-via-Thermography-and-Mammography.git
cd Breast-Cancer-Detection-via-Thermography-and-Mammography
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

3. Open and run the Jupyter notebooks:
```bash
jupyter notebook
```

## 📁 Notebooks

The repository contains Jupyter notebooks for:
- Data exploration and preprocessing
- Model architecture implementation
- Training and evaluation
- Results visualization and analysis

## 📈 Results

The framework achieves:
- **High Sensitivity**: Effective detection of cancer cases
- **Good Specificity**: Minimization of false positives
- **Improved Performance**: Better results compared to single-modality approaches

*Detailed results and metrics are available in the notebook outputs and results directory.*

## 🔍 Key Contributions

1. Unified framework for multi-modal breast cancer detection
2. Self-supervised learning approach reducing annotation requirements
3. Gated fusion mechanism for intelligent modality integration
4. Comprehensive evaluation on thermal and mammographic data

## 📚 References

This work builds upon advances in:
- Multi-modal learning and fusion techniques
- Self-supervised representation learning
- Medical image analysis and computer-aided diagnosis
- Deep learning for healthcare applications

## 💡 Usage

1. Prepare your dataset with thermography and mammography images
2. Run the preprocessing notebooks
3. Execute the training notebooks to train the model
4. Use the evaluation notebooks for testing and visualization
5. Analyze results with the provided visualization tools

## 🤝 Contributing

Contributions are welcome! Please feel free to:
- Report bugs and issues
- Suggest improvements and enhancements
- Submit pull requests with new features

## 📄 License

This project is available under the [LICENSE](LICENSE) file in this repository.

## 👤 Author

**albrud199**

## 📧 Contact & Support

For questions, feedback, or collaboration opportunities, please reach out through GitHub issues or contact the repository maintainer.

## ⚠️ Disclaimer

This tool is designed for research purposes. It should not be used as a sole diagnostic method without professional medical review and validation. Always consult with qualified healthcare professionals for medical diagnoses.

## 🔗 Related Work

- Multi-modal medical image analysis
- Self-supervised learning in healthcare
- Fusion mechanisms for combining heterogeneous data streams
- Computer-aided diagnosis systems

---


For more information about the research and methodology, please explore the Jupyter notebooks in this repository.
