## Lecture 7 (31 Jan)
### Bit Shift
- For positives, bit shift is based on its regular form. 
- For negatives, bit shift is based on its two's component form.
``` C
int A = 0x002FBA00;
int B = A >> 2; // B == 0x00002FBA
int C = A << 2; // C == 0x2FBA0000
int A_ =  0xFFFFBA00;
int B_ = A >> 2; // B_ == FFFFFFBA
int C_ = A << 2; // C_ == FFBA00FF
```
