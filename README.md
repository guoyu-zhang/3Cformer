# Crossing the Channels: Improving PatchTST for Long-Term Forecasting

**3Cformer** is designed for **multivariate long-term time series forecasting (MLTSF)**, addressing the limitations of previous transformer models.

### What Previous Approaches Missed

- Channel-independent models ignore relationships between channels.
- Channel-dependent models fail to effectively capture cross-channel interactions.

### How 3Cformer Addresses This

- Builds on **PatchTST**, a strong channel-independent transformer.
- Adds a **Graph Convolutional Network (GCN)**.
- Uses a **cosine similarity-based graph** to explicitly model cross-channel dependencies.
- Evaluated on **5 real-world datasets**.
- Achieves **state-of-the-art performance**, especially when cross-channel correlations are strong.
