# Text Classification Project

This project is part of the ML Ops course at Jio Institute. The goal of this project is to build and deploy a text classification model.

## Project Structure

- `data/`: Contains the dataset used for training and testing.
- `notebooks/`: Jupyter notebooks for data exploration and model development.
- `src/`: Source code for data preprocessing, model training, and evaluation.
- `models/`: Saved models and related artifacts.
- `scripts/`: Scripts for running the model and other utilities.
- `README.md`: Project documentation.

## Setup

1. Clone the repository:
    ```bash
    git clone <repository_url>
    cd text_classification
    ```

2. Create a virtual environment and install dependencies:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    pip install -r requirements.txt
    ```

## Usage

1. Preprocess the data:
    ```bash
    python src/preprocess.py
    ```

2. Train the model:
    ```bash
    python src/train.py
    ```

3. Evaluate the model:
    ```bash
    python src/evaluate.py
    ```

4. Run the model for predictions:
    ```bash
    python scripts/predict.py --input <input_text>
    ```

## Deployment

Instructions for deploying the model will be added here.

## Contributing

Feel free to open issues or submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License.

## Acknowledgements

- Jio Institute for providing the course and resources.
- The open-source community for their invaluable tools and libraries.
