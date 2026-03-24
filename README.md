# attention-in-transformers

A from-scratch implementation of all attention mechanisms in Transformers, coded in PyTorch.

Based on the DeepLearning.AI course **"Attention in Transformers: Concepts and Code in PyTorch"** by Josh Starmer.

---

## Progress

- [x] Self-Attention
- [ ] Masked Self-Attention
- [ ] Cross-Attention (Encoder-Decoder)
- [ ] Multi-Head Attention

---

## Setup

```bash
# Create and activate a virtual environment
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

### Requirements

- PyTorch >= 2.0.0
- Matplotlib >= 3.7.0
- Jupyter >= 1.0.0

---

## Usage

Run the Jupyter notebook to explore the attention implementations:

```bash
jupyter notebook notebooks/attention_in_transformers.ipynb
```

Or launch Jupyter Lab:

```bash
jupyter lab
```

---

## Project Structure

```
attention-in-transformers/
├── notebooks/
│   └── attention_in_transformers.ipynb   # Main notebook with implementations
├── requirements.txt
└── README.md
```
