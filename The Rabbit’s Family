#include <iostream>
using namespace std;

int rabbits(int n, int a = 1, int b = 1) {
    if (n == 1) return a;       
    if (n == 2) return b;       
    return rabbits(n - 1, b, a + b); 
}

int main() {
    int n;
    cin >> n;
    cout << rabbits(n);
    return 0;
}
