This project implements a custom Deep Learning architecture designed for high-precision footwear classification (Boots, Sandals, Shoes). The core of the model relies on Factorized Inception Modules to reduce parameter count while maintaining complex feature extraction, coupled with a Spatial Attention Mechanism to focus on relevant object regions.
🚀 Key Features
  1-Factorized Inception: Decomposes $3 \times 3$ and $5 \times 5$ convolutions into $1 \times N$ and $N \times 1$ to improve efficiency.
  2-Spatial Attention: Implements a bottleneck attention layer using Global Average and Max Pooling to weigh spatial features.
  3-High Accuracy: Achieved 96.8% accuracy on the validation set with stable convergence
  
📊 Performance Results
  1-Final Accuracy: ~96.8%

  2-Loss: Successfully minimized with a stable validation curve.
  <img width="553" height="413" alt="image" src="https://github.com/user-attachments/assets/f6e86735-8201-4f07-b33c-c1314e91af97" />

  3-Confusion Matrix: Shows excellent separation between classes, with minimal confusion
   <img width="586" height="550" alt="image" src="https://github.com/user-attachments/assets/abf8988e-83a2-4e1a-bdaa-a6715bfa4ad2" />
