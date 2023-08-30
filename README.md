# Dutch to English Machine Translation using PyTorch Seq2Seq RNN

This repository contains a machine translation project that translates Dutch sentences into English using PyTorch and a Sequence-to-Sequence (Seq2Seq) Recurrent Neural Network (RNN) model with attention.

## Dataset

The dataset used in this project is loaded from [http://www.manythings.org/anki/](http://www.manythings.org/anki/).

## Project Structure

- `Data/`: Data files, including the Dutch-English sentence pairs.
- `savedModel/`: Saved model weights (if applicable).
- `README.md`: This README file.
- `Translation-Dutch-to-English-PyTorch-Seq2Seq-RNN.ipynb`: The main Jupyter notebook containing the code.

## Usage

To use this project, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/vrajeshtrichy/AI-ML-NLP-MachineTranslation.git
   cd AI-ML-NLP-MachineTranslation
   ```

2. Open the `Translation-Dutch-to-English-PyTorch-Seq2Seq-RNN.ipynb` notebook in your Jupyter environment to explore the code and execute it.

3. Experiment with different inputs and sentences for translation.

## Dependencies

Make sure you have the following dependencies installed:

- Python (>=3.6)
- PyTorch
- Jupyter Notebook

You can install the required Python libraries using `pip`:

```bash
pip install torch jupyter
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The code in this project was developed based on the tutorials and documentation provided by PyTorch.
