#include <iostream>
using namespace std;

int main() {
    int a = 10;
    int b = 15;
    int c = 27;

    int *p1 = &a;
    int *p2 = &b;
    int *p3 = &c;

    cout << "a <- 10 = " << a << endl;
    cout << "b <- 15 = " << b << endl;
    cout << "c <- 27 = " << c << endl;
    cout << "p1 <- a = " << p1 << endl;
    cout << "p2 <- b = " << p2 << endl;
    cout << "*p1 <- c = " << *p1 << endl;
    cout << "a <- *p2 = " << *p2 << endl; // Perbaikan disini
    *p2 = 6;
    cout << "b <- 6 = " << *p2 << endl;
    cout << "p3 <- &b = " << p2 << endl;
    cout << "p3 <- &c = " << p3 << endl;
    cout << "*p1 <- *p3 = " << *p3 << endl;

    cout << endl;
    cout << "OUTPUT NYA ADALAH" << endl;
    cout << "------------------------------" << endl;
    cout << "nilai a adalah = " << a << endl;
    cout << "nilai b adalah = " << b << endl;
    cout << "nilai c adalah = " << c << endl;
    cout << "nilai p1 adalah = " << p1 << endl;
    cout << "nilai p2 adalah = " << p2 << endl;
    cout << "nilai p3 adalah = " << p3 << endl;

    cin.get();
    return 0;
}
