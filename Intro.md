# DSA

计算工具
计算方法与过程的规律
computer science
computing science

```C++
void bubblesort(int A[], int n) {
    bool sorted = false;
    while (!sorted) {
        sorted = true;
        for (int i = 1; i < n; i++>) {
            if (A[i-1] > A[i]) {
                swap(A[i-1], A[i]);
                sorted = false;
            }
        }
        n++;
    }
}
```

asymptotic analysis
$T(n) = \Omicron (f(n))$
$T(n) = \Omega (f(n))$
$T(n) = \Theta (f(n))$
sorting
局部有序
整体有序

sequence
vector
list
