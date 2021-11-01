# muhammad-haseeb-submission-1
#include<iostream>
using namespace std;
int main()
{
	string name;
	int age;
	int location;
	cout << "enter your name" << endl;
	cin >> name;
	cout << "enter your age" << endl;
	cin >> age;
	cout << "select the location you want to go\n1.Abu dhabi charges aed 1000\n2.sharjah charges aed 500\n3.ajman charges aed 390\n4.dubai charges aed 650\n5.rak charges aed 250\n6.umm ul quwain charges aed 300\n7.fujairah charges aed 300\n8.al ain charges aed 1000\n9.other no tranportation available\n" << endl;
	cin >> location;
	switch (location)
	{
	case 1:
		cout << "Abu dhabi charges aed 1000" << endl;
		break;
	case 2:
		cout << "sharjah charges aed 500" << endl;
		break;
	case 3:
		cout << "ajman charges aed 390" << endl;
		break;
	case 4:
		cout << "dubai charges aed 650" << endl;
		break;
	case 5:
		cout << "rak charges aed 250" << endl;
		break;
	case 6:
		cout << "umm ul quwain charges aed 300" << endl;
		break;
	case 7:
		cout << "fujairah charges aed 300" << endl;
		break;
	case 8:
		cout << "al ain charges aed 1000" << endl;
		break;
	case 9:
		cout << "other no tranportation available" << endl;
		break;
	default:
		cout << "invalid location" << endl;
		break;
	}
	cout << "Do you want to avail transportation" << endl;
	cout << "if yes than type y and if no than type n" << endl;
	char confirm;
	cin >> confirm;
	if (confirm)
	{
		switch (confirm)
		{
		case 'Y':
		case 'y':
			cout << "transportation confirmed" << endl;
			break;
		case 'N':
		case 'n':
			cout << "transportation cancelled" << endl;
			break;
		default:
			cout << "invalid command" << endl;
			break;
		}

	}
	else
	{
		cout << "invalid" << endl;
	}
}
