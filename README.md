#include<iostream>
using namespace std;
int main()
{
	int num = 1;
	int count = 0;
	cout << "plz enter an integer number:" << endl;
	cin >> num;
	for (int i = 1; i < num; i = i + 2)
		count++;
	cout <<"all odd number between 1 and num:"<< count << endl;

}
