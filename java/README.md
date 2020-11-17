Algorithms (Pseudo-code)
- Bubble Sort

for i = 0 to A.length-2
    for j = 0 to A.length-2-i
        if A[j] > A[j + 1]
            tmp = A [j + 1]
            A[j + 1] = A[j]
            A[j] = tmp


- Selection Sort

for i = 0 to A.length - 2
    minIndex = i;
    for j = i + 1 to A.length - 1
        if (data[j] < data[minIndex])
            minIndex = j
    tmp = data[minIndex]
    data[minIndex] = data[i]
    data[i] = tmp
