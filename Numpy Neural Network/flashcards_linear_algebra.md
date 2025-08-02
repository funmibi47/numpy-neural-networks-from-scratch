# Neural Network Flashcards

- 1. **What is a dot product?**
    - **Definition**: The dot product of two vectors is the sum of the products of their corresponding elements.
    - **Formula**:
        
        $$
        a \cdot b = \sum_{i=1}^{n} a_i b_i
        $$
        
    - **Use**: Measures similarity or computes weighted sums in neural nets.
- 2. **How do you multiply two matrices?**
    - **Rule**: Multiply rows of the first matrix with columns of the second.
    - **Shape Condition**:
        
        $$
        A_{(m \times n)} \cdot B_{(n \times p)} = C_{(m \times p)}
        $$
        
    - **Used for**: Calculating activations between layers.
- 3. **What is an eigenvector used for?**
    - **Meaning**: A vector whose direction doesn't change under a linear transformation.
    - **Used in**: PCA, stability analysis, etc.
- 4. **How do you calculate a determinant?**
    - **2x2 Example**:
        
        $$
        det=ad - bc
        \quad \text{for} \quad 
        \begin{bmatrix}
        a & b \\
        c & d
        \end{bmatrix}
        $$
        
    - **Use**: To check matrix invertibility.
- 5. **Why are inverses important in solving systems?**
    - **Use**:
        
        Solving:
        
        $$
        Ax=b⇒x= A^{-1}b
        $$
        
    - **Important** in: Optimization, least squares, and backprop.