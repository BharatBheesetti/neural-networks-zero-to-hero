# Neural Networks: Zero to Hero 
# Neural Networks: Zero to Hero

This repository contains my implementation and notes following Andrej Karpathy's "Neural Networks: Zero to Hero" course. Each directory corresponds to a different section of the course.

## Course Structure

1. **micrograd**: Building neural networks and backpropagation from scratch
   - Implementation of a tiny autograd engine
   - Basic neural network fundamentals

2. **makemore**: Introduction to language modeling
   - Bigram character-level language model
   - Introduction to PyTorch tensors
   - Basic framework of language modeling

3. **makemore_part2_mlp**: Multilayer Perceptron Implementation
   - Character-level language model using MLP
   - Basic machine learning concepts
   - Model training and evaluation

4. **makemore_part3_bn**: Activations, Gradients, and BatchNorm
   - Deep dive into MLP internals
   - Network health diagnostics
   - Batch Normalization implementation

5. **makemore_part4_backprop**: Manual Backpropagation
   - Manual implementation of backpropagation
   - Deep understanding of gradient flow
   - Working with PyTorch tensors

6. **makemore_part5_wavenet**: WaveNet-style Architecture
   - Deep neural network with tree structure
   - Implementation similar to DeepMind's WaveNet
   - Advanced PyTorch concepts

7. **gpt**: Building GPT From Scratch
   - Implementation of the Transformer architecture
   - Following "Attention is All You Need" paper
   - GPT-style language model

8. **tokenizer**: GPT Tokenizer Implementation
   - Building a tokenizer from scratch
   - Byte Pair Encoding (BPE)
   - String to token conversion and vice versa

## Setup

1. Create a Python virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install required packages:
```bash
pip install torch numpy matplotlib jupyter
```

## Course Resources

- Original course by Andrej Karpathy: [Neural Networks: Zero to Hero](https://karpathy.ai/zero-to-hero.html)
- YouTube playlist: [[Link to playlist](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ)]

## Progress Tracking

- [ ] micrograd
- [ ] makemore
- [ ] makemore Part 2: MLP
- [ ] makemore Part 3: BatchNorm
- [ ] makemore Part 4: Backprop
- [ ] makemore Part 5: WaveNet
- [ ] GPT Implementation
- [ ] Tokenizer Implementation

## Notes

Each directory contains:
- Implementation files (.py)
- Jupyter notebooks (.ipynb) for experiments
- README with section-specific notes