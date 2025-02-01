 Advancing Arabic Sign Language Recognition: A Hybrid CNN + Transformer Approach

In my latest project, I took Arabic Sign Language (ArSL) recognition a step further by integrating Transformers with CNNs, combining the power of spatial feature extraction and sequential pattern learning.

# Why a Hybrid Model?
While CNNs excel at detecting local patterns, they lack the ability to capture long-range dependencies in sign gestures. 
By incorporating Transformers, the model gains a global contextual understanding, leading to better recognition accuracy and generalization.

# Key Enhancements:
✔️ CNN for feature extraction – Detects edges, textures, and patterns.
✔️ Positional encoding – Provides spatial awareness to the Transformer.
✔️ Multi-head self-attention – Focuses on different gesture parts simultaneously.
✔️ Layer normalization & residual connections – Ensures stability and efficient learning.
✔️ Global Average Pooling instead of flattening – Reduces overfitting while keeping important features.
✔️ Regularization & optimized training – Dropout and Adam optimizer for better generalization.


# dataset : https://drive.google.com/drive/folders/1y5t9wrmMdsAlLjxAA7Mqa8JezOSdVStt?usp=sharing
