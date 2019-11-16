# piramida
Make a Pyramid with n X
// piramida.cpp : This file contains the 'main' function. Program execution begins and ends there.
//

#include <iostream>
#include <math.h>

using namespace std;
int main()
{
	int i = 0, n;
	cout << "Korisnice daj neki n! \n";
	cin >> n;

	do {
		i = i + 1;

		for (int j = 0; j < n - i; j++) cout << " ";
		for (int j = 0; j < 2*i-1; j++) cout << "X";

		cout << endl;

	} while (i < n);
}
