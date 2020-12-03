---
description: My personal notes on the ways you can use c++.
---

# C++

## Arrays

#### Allocation

The following code creates an array and sets all values within the array to 0.

```text
int array[10];

for(int i = 0; i < 10; i++) {
    array[i] = 0;
}
```

This next snippet acheives the same  result:

```text
int array[10] = {};
```

