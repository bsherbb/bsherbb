#include<iostream>
#include<string>
using namespace std;
void Readmarks(int& mark1, int& mark2, int& mark3)
{
	cout << "pless Enter mark1" << endl;
	cin >> mark1;
	cout << "pless enter mark2" << endl;
	cin >> mark2;
	cout << "pless enter mark3" << endl;
	cin >> mark3;

}
int sum3mark(int mark1, int mark2, int mark3)
{
	return mark1 + mark2 + mark3;
	return mark1, mark2, mark3;
}
float clcletAvregmark(int mark1,int mark2,int mark3)
{
	return(float)sum3mark(mark1, mark2, mark3) / 3;
}
void printmarkAverg(float Averg)
{
	cout << "the Avreg=" << Averg << endl;
}
int main()
{
	int mark1, mark2, mark3;
	Readmarks(mark1, mark2, mark3);
	printmarkAverg(clcletAvregmark(mark1, mark2, mark3));

	return 0;
}
