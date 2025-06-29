# Bangla_E2E_ASR

<p align="center">
  <img src="image/keras.png" width="100" alt="Keras Logo">
</p>

Bangla_E2E_ASR is an open-source implementation of the DeepSpeech2 model for end-to-end speech recognition in Bangla. This project enables researchers and developers to train, evaluate, and deploy speech-to-text models for the Bangla language using modern deep learning techniques.

## Features

- **DeepSpeech2 Architecture**: Based on [Deep Speech 2: End-to-End Speech Recognition in English and Mandarin](https://arxiv.org/abs/1512.02595).
- **Spectrogram Feature Extraction**: Utilizes spectrograms for robust audio feature extraction.
- **Custom Language Support**: Easily adaptable for training on your own language datasets.
- **Keras Implementation**: Built with Keras for simplicity and flexibility.

## Requirements

- Python 3.5 or later
- [Keras](https://keras.io/)
- [librosa](https://librosa.org/) (for audio processing)

Install all dependencies using:

```bash
pip install -r requirements.txt
```

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/Bangla_E2E_ASR.git
   cd Bangla_E2E_ASR
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Prepare your dataset:**
   - Place your audio files and corresponding transcripts in the `data/` directory.
   - Update data loading scripts as needed for your dataset format.
4. **Train the model:**
   ```bash
   python train_utils.py
   ```
5. **Test or sample predictions:**
   ```bash
   python sample.py
   ```

## Directory Structure

- `model/` - Pretrained and intermediate model weights
- `data/` - Place your training and testing data here
- `results/` - Model outputs and results
- `utils.py`, `data_generator.py`, etc. - Core scripts for model, data, and training

## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements, bug fixes, or new features.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

If you use this project in your research or applications, please consider citing or starring the repository. Thank you for your support!
