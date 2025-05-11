
# NequIP Reimplementation for Toluene

This repository contains a reimplementation of the Neural Equivariant Interatomic Potential (NequIP) model, specifically tailored for predicting the potential energy of the toluene molecule. The project leverages E(3)-equivariant graph neural networks to achieve high accuracy in modeling interatomic potentials.

## 📁 Repository Structure

- **`Main_full_nequip_1000frame_toluene.ipynb`**: Primary Jupyter notebook demonstrating the full NequIP model implementation and training on a dataset of 1000 toluene frames.

- **`Nequip_example_dataset_100frames.ipynb`**: Example notebook showcasing the model's application on a smaller dataset of 100 frames for quick testing and validation.

- **`custom.yaml`**: Configuration file specifying the model architecture, training parameters, and dataset paths.

- **`requirements.txt`**: List of Python dependencies required to run the notebooks and scripts.

## 🚀 Getting Started

### Prerequisites

Ensure you have Python 3.8+ installed. It's recommended to use a virtual environment to manage dependencies.

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Shaunak-Mukherjee/Nequip-reimplement-Toluene.git
   cd Nequip-reimplement-Toluene
   ```

2. **Create and activate a virtual environment (optional but recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install the required dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

## 🧪 Usage

1. **Run the main notebook:**

   Open `Main_full_nequip_1000frame_toluene.ipynb` in Jupyter Notebook or JupyterLab and execute the cells sequentially to train and evaluate the NequIP model on the toluene dataset.

2. **Test with a smaller dataset:**

   For a quicker demonstration or testing purposes, use the `Nequip_example_dataset_100frames.ipynb` notebook, which operates on a reduced dataset.

## 📊 Results

The model achieves high accuracy in predicting the potential energy of toluene molecules, demonstrating the effectiveness of E(3)-equivariant graph neural networks in modeling complex molecular systems.

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 📫 Contact

For questions or collaborations, please reach out via [LinkedIn](https://www.linkedin.com/in/shaunak-mukherjee-22b223a8).
