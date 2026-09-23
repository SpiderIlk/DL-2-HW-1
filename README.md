## Task 1.5

### Simple dataset

Hyperparameters:

```python
PTS = 50
HIDDEN = 2
RATE = 0.5
data = minitorch.datasets["Simple"](PTS)
ScalarTrain(HIDDEN).train(data, RATE, max_epochs=500)
```

Training logs are available here:

[Simple training log](logs/module1_simple.txt)

### Diag dataset

Hyperparameters:

```python
PTS = 50
HIDDEN = 2
RATE = 0.5
data = minitorch.datasets["Diag"](PTS)
ScalarTrain(HIDDEN).train(data, RATE, max_epochs=500)
```

Training logs are available here:

[Diag training log](logs/module1_diag.txt)

### Split dataset

Hyperparameters:

```python
PTS = 50
HIDDEN = 5
RATE = 0.5
data = minitorch.datasets["Split"](PTS)
ScalarTrain(HIDDEN).train(data, RATE, max_epochs=500)
```

Training logs are available here:

[Split training log](logs/module1_split.txt)

### Xor dataset

Hyperparameters:

```python
PTS = 50
HIDDEN = 10
RATE = 0.5
data = minitorch.datasets["Xor"](PTS)
ScalarTrain(HIDDEN).train(data, RATE, max_epochs=500)
```

Training logs are available here:

[Xor training log](logs/module1_xor.txt)

## Task 2.5

### Simple dataset

Hyperparameters:

```python
PTS = 50
HIDDEN = 2
RATE = 0.5
data = minitorch.datasets["Simple"](PTS)
ScalarTrain(HIDDEN).train(data, RATE, max_epochs=500)
```

Training logs are available here:

[Simple training log](logs/module2_simple.txt)

### Diag dataset

Hyperparameters:

```python
PTS = 50
HIDDEN = 2
RATE = 0.5
data = minitorch.datasets["Diag"](PTS)
ScalarTrain(HIDDEN).train(data, RATE, max_epochs=500)
```

Training logs are available here:

[Diag training log](logs/module2_diag.txt)

### Split dataset

Hyperparameters:

```python
PTS = 50
HIDDEN = 5
RATE = 0.5
data = minitorch.datasets["Split"](PTS)
ScalarTrain(HIDDEN).train(data, RATE, max_epochs=500)
```

Training logs are available here:

[Split training log](logs/module2_split.txt)

### Xor dataset

Hyperparameters:

```python
PTS = 50
HIDDEN = 10
RATE = 0.5
data = minitorch.datasets["Xor"](PTS)
ScalarTrain(HIDDEN).train(data, RATE, max_epochs=500)
```

Training logs are available here:

[Xor training log](logs/module2_xor.txt)
