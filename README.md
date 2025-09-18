## Files  

- **`numpynn.py`**  
  - Implements a fully connected neural network with NumPy.  
  - Includes forward propagation, loss computation, and manual gradient updates.  
  - Great for educational purposes to understand how backpropagation works under the hood.  

- **`pytorchnn.py`**  
  - Implements the same architecture in PyTorch.  
  - Uses `torch.nn.Module`, optimizers, and autograd for gradient computation.  
  - Easier to extend for larger models and training on GPUs.  
## Network Architecture  

Both implementations share a similar architecture:  

- Input layer: depends on dataset dimensionality  
- Hidden layers: fully connected (dense)  
- Activation functions: (e.g., ReLU / Sigmoid – depending on code)  
- Output layer: task-dependent (e.g., softmax for classification)  

