``` C++
/* Алгоритм Евклида поиска НОД
 * int a Делимое
 * int b Делитель
 */

int euclid_GCD(int a, int b){
    while(a != b){
        if(a > b)
            a -= b;
        else
            b -= a;
    }
    return a;
}
```
