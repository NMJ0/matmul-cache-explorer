# Matmul Cache Explorer

Interactive demo of loop tiling and loop reordering for matrix multiply, from the CS6886 ML compilers lecture (IIT Madras).

Step through `C[i][j] += A[i][k] * B[k][j]` against a tiny LRU cache and compare the cache misses for every loop order and tile size.

Live: https://nmj0.github.io/matmul-cache-explorer/
