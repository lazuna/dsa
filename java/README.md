Algorithms (Pseudo-code)
- Bubble Sort

for i = 0 to A.length-2
    for j = 0 to A.length-2-i
        if A[j] > A[j + 1]
            tmp = A [j + 1]
            A[j + 1] = A[j]
            A[j] = tmp
