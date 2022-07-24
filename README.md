# KTLT-page15
Giải bt số 2 trang 15 Kỹ Thuật Lập Trình 
 

#include <iostream>
using namespace std;

int sum(int a, int b)
{
	return a + b;
}

int tích(int a, int b)
{
	return a * b;
}

int thương(int a, int b)
{
	return a / b;
}

int hiệu(int a, int b)
{
	return a - b;
}

int main()
{
	int a, b;
	char choose = 0;
	cout << "\n Please type two number a and b: ";
	cin >> a; cin >> b;
	cout << "\n Please type ramdom number: ";
	cout << "\n Type + is sum " << "\n Type * is tich " << "\n Type - is hieu " << "\n Type / is thuong " << endl;
	cin >> choose;
if (choose == '+')
		cout << " Tổng là: " << sum(a, b);
else
 if (choose == '-')
			cout << " Hiệu là: " << hiệu(a, b);
 else if (choose == ' * ')
		cout << " Tích là: " << tích(a, b);
 else if (choose == '/')
			cout << " Thương là: " << thương(a, b);
else
			cout << " chào bạn ^-^ ";
	
	return 0;
}
