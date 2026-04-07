# GPT Religious Text Project

A character-level GPT trained on five religious and philosophical texts from Project Gutenberg for text generation experiments.

### Dataset

The project uses 5 religious and philosophical texts from Project Gutenberg for training and experimentation:

1. **The Book of Meditations** – Marcus Aurelius  
2. **The Book of Mormon** – Joseph Smith  
3. **The Gospel of Buddha** – Paul Carus  
4. **The King James Bible** – Various authors  
5. **The Koran** – Translated by Multiple Translators

These texts are included in the repository under `data/archive/`.

## Files

- `notebook/` – Jupyter notebooks for preprocessing, training, and generating text – also contains saved model
- `data/archive/` – Original `.txt` files from Project Gutenberg.
- `README.md` – This file.

## Setup

1. Clone the repository.
2. Install dependencies (Python 3.10+ recommended): pip install torch numpy matplotlib jupyter
3. Open Jupyter Notebook in the `notebook/` folder.

## Usage

1. Preprocess text data.
2. Train the GPT model with chosen hyperparameters.
3. Generate text from the trained model.

## Notes

- Designed for experimentation; GPU recommended.
- Model is small, for learning/experiments only.

## License

Project Gutenberg texts are public domain.
