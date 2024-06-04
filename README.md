# Image Processing Labs

This project contains a series of Jupyter notebooks and Python scripts that demonstrate the use of Fourier Transform for image analysis. Each lab focuses on different aspects of Fourier Transform and image processing techniques.

## Project Structure

- `lab1/` - Contains the first lab notebook focusing on image contrast correction and histogram visualization.
- `lab2/` - Contains the second lab notebook which covers image noise analysis and filtering techniques.
- `lab3/` - Contains the third lab notebook and a `ressources.py` script. This lab introduces Fourier Transform analysis with functions such as `fourier2d_all`, `fourier2d_single_frenquency`, `fourier2d_many_frequencies`, and `fourier2d_vue3d_old`.
- `lab4/` - Contains the fourth lab notebook which delves into image segmentation techniques.
- `lab5/` - Contains the fifth lab notebook focusing on image segmentaation using ***Region Growing*** Algorithm

Each lab folder also contains a `resources/` directory with images and other files used in the lab exercises.

## Prerequisites

- Python 3.10 or higher
- pip

## Installation

1. Clone this repository to your local machine.

    ```sh
    git clone https://github.com/Hamza-cpp/img-processing-labs
    ```

2. Navigate to the project directory.

    ```sh
    cd ./path/to/img-processing-labs
    ```

3. Create and activate the virtual env:

    ```sh
    python -m venv .venv && source .venv/bin/activate
    ```

4. Install the necessary dependencies using pip:

    ```sh
    pip install -U pip
    pip install -r requirements.txt
    ```

## Running the Notebooks

To run the notebooks, you need to have Jupyter installed. If not, you can install it with:

```bash
pip install jupyter
```

Then, you can start Jupyter by running:

```bash
jupyter notebook
```

This will open a web browser where you can navigate to the notebook files **.ipynb** and open them.

## Contributing

Contributions are welcome. Please open an issue to discuss your idea or submit a Pull Request.
