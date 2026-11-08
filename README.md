# IE500618-assignment3

Magnus Grande (individual assignment)

## How to run

1. Clone the repository
2. Create a virtual environment with **Python 3.13**.

  ```bash
  py install 3.13          # only needed if Python 3.13 isn't installed yet
  py -3.13 -m venv .venv
  .venv\Scripts\activate
  ```

3. Install the required packages

  ```bash
  pip install -r requirements.txt
  ```

4. Run the notebook `assignment3.ipynb` in Jupyter Notebook or Jupyter Lab, or inside an IDE or VSCode with the appropriate extensions installed. It can also be uploaded to Google Colab as it is, since Colab already has TensorFlow installed.

The Fashion-MNIST dataset is downloaded automatically by `tf.keras.datasets.fashion_mnist.load_data()` the first time the notebook runs. Running all cells takes about a minute and a half on a laptop CPU.
