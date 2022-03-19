# luogu
# nothing
#include<iostream>
using namespace std;
int main() {
	int a, b, c, d,e,f;
	cin >> a >> b >> c >> d;
	if (d < b) {
		c--;
		f = d - b+60;
	}
	else {
		f = d - b ;
	}
	if (c < a) {
		e = c - a + 24;
	}
	e = c - a;
	cout << e << " " << f;

}
