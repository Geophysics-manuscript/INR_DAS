# README

## Overview

Welcome to the repository for the code associated with our anonymous under-review paper submitted to *Geophysics*. This code is designed to verify the effectiveness of our proposed method through synthetic examples. 

## Purpose

The primary objective of this code is to demonstrate the capability and performance of our method in separating complex from DAS data. Our approach, which leverages advanced signal processing techniques, is unsupervised and does not require external training datasets.

## Features

- **Unsupervised Method**: No need for external training datasets, making it easy to apply in various scenarios.
- **Synthetic Examples**: Included to validate the performance of our method.
- **Reproducible Research**: Code is provided to ensure that the results presented in the paper can be replicated and verified by other researchers.

## Requirements

To run the code, you'll need the following software and libraries installed:

- Python 3.x
- NumPy
- SciPy
- Matplotlib
- Pytorch

You can install the required packages using `pip`:

```bash
pip install numpy scipy matplotlib pytorch
```

## Usage

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Geophysics-manuscript/INR_DAS.git
   cd INR_DAS
   ```

2. **Run the Example**:

   Execute the Demo.ipynb script to run the synthetic example and verify the method:

   ```
   jupyter notebook Demo.ipynb
   ```

   This will generate plots and results demonstrating the effectiveness of the proposed method.

## Directory Structure

- `data.mat`: Directory containing synthetic data files.

## Contributing

We welcome contributions to enhance the functionality of this code. If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Contact

For any questions or further information, please contact us.

---

Thank you for using our code. We hope it proves valuable in your research and applications.
