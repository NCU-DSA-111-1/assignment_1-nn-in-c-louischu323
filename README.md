# Neural Network in C
Assignment 1

## Usage

## Compile & Run
```sh
# Compile
cd Neural_Network_in_C
gcc -o main main.c -lm layer.c neuron.c
# Run
./main
```
## Enter the Inputs for training examples, 2 bits in this case, 4 Inputs in total.

```sh
# Enter the input for examples:
Enter the Inputs for training example[0]:  0 0
Enter the Inputs for training example[1]:  0 1
Enter the Inputs for training example[2]:  1 0
Enter the Inputs for training example[3]:  1 1

```

## Enter the Desired Outputs for training example, 4 Desired Outputs in total
```sh
# Enter the Desired Outputs for training example
Enter the Desired Outputs (Labels) for training example[0]:  0 
Enter the Desired Outputs (Labels) for training example[1]:  1 
Enter the Desired Outputs (Labels) for training example[2]:  1 
Enter the Desired Outputs (Labels) for training example[3]:  0
```

## Enter 2-bit Input to test
```sh
#Enter input to test
Enter input to test: 0 0
Output: 0 
Enter input to test: 0 1
Output: 1 
Enter input to test: 1 0
Output: 1 
Enter input to test: 1 1 
Output: 0 
```


