# gtrick: Bag of Tricks for Graph Neural Networks

> Trick is all you need

## Tricks
* VirtualNode: [Neural Message Passing for Quantum Chemistry](https://arxiv.org/pdf/1704.01212.pdf)
* Position Encoding
* FLAG
* DropEdge


## Benchmark

### Virtual Node
 
| Dataset         |       GCN       | GCN + Virtual Node |       GIN       | GIN + Virtual Node |
|:---------------:|:---------------:|:------------------:|:---------------:|:------------------:|
|   ogbg-molhiv   | 0.7683 ± 0.0107 |   0.7330 ± 0.0293  | 0.7708 ± 0.0138 |   0.7673 ± 0.0082  |