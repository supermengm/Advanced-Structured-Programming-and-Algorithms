# Big O
## Prove that the Big-O of the following loop is O(N)
```c
for (int i = 1; i <= n; i += c) {  
   // some O(1) expressions
}
```

## Find the Big-O of the following loops
```c
// c is constant
for (int i = 1; i <=n; i += c) {
   for (int j = 1; j <=n; j = pow(i, c)) {
      // some O(1) expressions
   }
}

for (int i = n; i > 0; i += c) {
   for (int j = i+1; j <= n; j *= c) {
      // some O(1) expressions
}
```
