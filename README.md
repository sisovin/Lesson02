# Lesson02


## Explanation

The code snippet is written in Python and utilizes the PyTorch library, a popular deep learning framework.

- `import torch`: This line imports the PyTorch library, making its functions and classes available for use.
- `x = torch.tensor([1, 2, 3])`: This line creates a PyTorch tensor from a list of values `[1, 2, 3]`. A tensor is a multi-dimensional array used to store data in PyTorch.
- `print(x)`: This line prints the tensor `x` to the console.
- `x = torch.rand(2, 3)`: This line creates a 2x3 tensor filled with random values between 0 and 1 using the `rand` function.
- `print(x)`: This line prints the new tensor `x` to the console.

## How to do it

To run this code, follow these steps:

1. **Install PyTorch**: If you haven't already, install PyTorch using pip:
   ```sh
   pip install torch
   ```
2. **Import PyTorch**: Add the following line at the top of your Python script or code block:
   ```python
   import torch
   ```
3. **Create a tensor**: Use the `torch.tensor()` function to create a tensor from a list of values, as shown in the code snippet.
4. **Print the tensor**: Use the `print()` function to display the tensor to the console.
5. **Create a random tensor**: Use the `torch.rand()` function to create a tensor filled with random values.
6. **Print the random tensor**: Use the `print()` function to display the random tensor to the console.

## Example Code

```python
import torch

# Create a tensor from a list of values
x = torch.tensor([1, 2, 3])
print(x)

# Create a random tensor
x = torch.rand(2, 3)
print(x)
```

## Tips

- Make sure you have PyTorch installed and imported correctly.
- The `torch.tensor()` function can also be used to create tensors from other data types, such as numpy arrays or lists of tuples.
- The `torch.rand()` function can be used to create tensors with random values in a specific range or distribution.
```
