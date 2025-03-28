# reading-nnfs

## NNFS

Notes and thoughts I've accumulated as I'm going through the NNFS book by [Sentdex](https://github.com/sentdex).

- Weights can only change the value of the output on the basis of the input.
- If the inputs are zero, no matter what the weights are the output is also 0. That's why we need the tuneable bias parameter to remove the restrictive anchor of the output being zero if the inputs are all 0.
- Example Models: https://www.youtube.com/watch?v=Ls1dJqZtI7w&ab_channel=sentdex
- How weights and biases impact a single neuron: https://www.youtube.com/watch?v=SRAFVJ5UbB0&ab_channel=sentdex
- Model 2x4 Cats Dogs: https://www.youtube.com/watch?v=fXSRfzhHPm0&ab_channel=sentdex, Model 2x4 Cats Dogs Code: https://www.youtube.com/watch?v=-6mZWjIEkDc&ab_channel=sentdex
- The math behind an example forward pass through a neural network: https://www.youtube.com/watch?v=xtzVuln1PV8&ab_channel=sentdex
  - Essentially doing the weighted sum, applying ReLU activation function, and then doing the weighted sum again etc. until a softmax.
- 
