# Custom GPT-2 Language Model (163M Parameters) Built from Scratch
A complete **from-scratch implementation** of a GPT-2 style Transformer-based Language Model in **PyTorch**. This project covers everything from tokenization to model architecture and training, demonstrating a deep understanding of LLM internals.

## Features
- GPT-2 style Transformer architecture (decoder-only) with 163M parameters.
- Custom tokenization and vocabulary building for text datasets.
- Multi-Head Self-Attention, Positional Embeddings, Layer Normalization, Feed Forward blocks implemented from scratch.
- Modular training pipeline with checkpointing and scalability in mind.
- Text generation support with sampling and temperature control.

## Project Structure
```
├── data/                # Raw and processed datasets  
├── GPT2_model.ipynb     # Main Jupyter Notebook with implementation  
├── checkpoints/         # Saved model checkpoints  
├── outputs/             # Generated text samples  
└── README.md            # Project documentation  
```

## Tech Stack
- **Language:** Python 3.10+
- **Frameworks/Libraries:** PyTorch, NumPy
- **Concepts:** Transformer Architectures, NLP, Deep Learning
- **Tools:** Jupyter Notebook

## Training & Results
- Trained on a sample text corpus using custom tokenization (~50K vocabulary).
- Achieved progressive loss reduction and generated coherent, context-aware text outputs.
- Sample text outputs are available in the `outputs/` folder.

## Example Output
```
Input Prompt: "The future of AI is"
Generated Text: "The future of AI is a fascinating journey where machines learn to assist, create, and evolve..."
```

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Build_LLM_From_Scratch.git
   cd Build_LLM_From_Scratch
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook and run all cells:
   ```bash
   jupyter notebook GPT2_model.ipynb
   ```

## Contributing
Pull requests and suggestions are welcome! For major changes, please open an issue first to discuss what you'd like to change.

## Show Your Support
If you like this project, please ⭐ the repo!
