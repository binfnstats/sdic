Sparse data to structured imageset conversion

Converts an M (samples) by N (features) sparse dataset to an M (number of images) by P (height) by P (width) imageset while attempting to give each image structure that is amenable for use with convolutional neural networks

P is given by the smallest even number that is greater than or equal to sqrt(N)


- The last column in mushroom is the target (0 or 1)
- 5 == x
- 0 = b
- 2 = f
- 4 = s 
