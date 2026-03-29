This project implements a custom Deep Learning architecture designed for high-precision footwear classification (Boots, Sandals, Shoes). The core of the model relies on Factorized Inception Modules to reduce parameter count while maintaining complex feature extraction, coupled with a Spatial Attention Mechanism to focus on relevant object regions.
🚀 Key FeaturesFactorized Inception: Decomposes $3 \times 3$ and $5 \times 5$ convolutions into $1 \times N$ and $N \times 1$ to improve efficiency.Spatial Attention: Implements a bottleneck attention layer using Global Average and Max Pooling to weigh spatial features.High Accuracy: Achieved 96.8% accuracy on the validation set with stable convergence.Optimized Architecture: Uses Batch Normalization and Dropout to prevent overfitting and ensure numerical stability.
📊 Performance Results
Final Accuracy: ~96.8%

Loss: Successfully minimized with a stable validation curve.

Confusion Matrix: Shows excellent separation between classes, with minimal confusion
