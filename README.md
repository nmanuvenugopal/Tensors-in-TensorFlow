# Tensors-in-TensorFlow

In TensorFlow, tensors are the fundamental data structures used to represent data. They are similar to multi-dimensional arrays or matrices but are more general in nature. A tensor is a mathematical concept that can represent scalars (0-dimensional tensors), vectors (1-dimensional tensors), matrices (2-dimensional tensors), or even higher-dimensional data.

Tensors in TensorFlow have the following key properties:

1. Rank: The rank of a tensor refers to the number of dimensions it has. For example, a scalar has a rank of 0, a vector has a rank of 1, a matrix has a rank of 2, and so on.

2. Shape: The shape of a tensor defines the number of elements along each dimension. For example, a 1-dimensional tensor (vector) with 5 elements has a shape of (5,), and a 2-dimensional tensor (matrix) with 3 rows and 4 columns has a shape of (3, 4).

3. Data Type: Tensors in TensorFlow have a specific data type, such as float32, int64, etc., which determines the type of data they can hold.

TensorFlow is a popular open-source deep learning framework, and it leverages tensors to represent and perform computations on multi-dimensional data, which is prevalent in machine learning and deep learning tasks. Tensors enable efficient and optimized numerical computations by utilizing hardware acceleration, like GPUs and TPUs.

Tensors are the building blocks of TensorFlow, and you can use them to represent and manipulate data in various machine learning and deep learning models.

We have various type of Tensors available and they are 
1.  Varibale
2.  Constant
3.  Placeholder
4.  SparseTensor

Except the varibale tensor, none of the other tensors mentioned above mutable, in other words they are immutable that means thier values cannot be changed during the execution.

