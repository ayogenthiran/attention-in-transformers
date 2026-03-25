# attention-in-transformers

Small **PyTorch** learning repo: attention built step by step in Jupyter notebooks—no Hugging Face, just tensors and `nn.Linear`.

## What’s here

| Notebook | Topic |
|----------|--------|
| `notebooks/attention_in_transformers.ipynb` | Self-attention: \(Q\), \(K\), \(V\), scores, softmax, output |
| `notebooks/masked_self_attention.ipynb` | Causal (decoder-style) masking so a position only attends to past and itself |
| `notebooks/multi_head_attention.ipynb` | Multi-head attention: split dimensions, several heads, concat back |
