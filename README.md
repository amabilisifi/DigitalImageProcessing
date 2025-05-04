# ImageEnhanceLab

This repository contains the solution for Assignment 1 of the Digital Image Processing course (Spring 2025, Department of Mathematical Sciences). The project implements various image processing techniques, including intensity enhancement, histogram specification, color processing, spatial filtering, and noise removal.

## Setup

### Prerequisites
- Python 3.8+
- Jupyter Notebook

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/amabilisifi/ImageEnhanceLab.git
   cd ImageEnhanceLab
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```bash
   jupyter notebook src/HW1.ipynb
   ```

## Directory Structure
- **images/input/**: Input images (e.g., `Q1-input1.jpg`, `ACE.jpg`).
- **images/output/**: Output images (e.g., `Q1-output-neg.jpg`, `salt_pepper_noise_a_0.10.png`).
- **src/HW1.ipynb**: Jupyter notebook with the assignment solutions.
- **requirements.txt**: Python dependencies.
- **LICENSE**: MIT License.

## Usage
1. Place input images in `images/input/`.
2. Open `src/HW1.ipynb` and run the cells to generate outputs.
3. Outputs will be saved in `images/output/` (not tracked by Git).

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
