#include <iostream>
using namespace std;

void reverseString(string s, int index) {
    if (index < 0) return;             
    cout << s[index];                   
    reverseString(s, index - 1);       
}

int main() {
    string s;
    cin >> s;
    reverseString(s, s.size() - 1);
    return 0;
}
