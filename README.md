# maryland
#include <iostream>
using namespace std;

int main() {
	int  answer;
	int calories;

	cout << "Enter 1 for vegetarian, 0 otherwise:" << endl;
	cin >> answer;
	cout << "Enter calories:" << endl;
	cin >> calories;

	if (answer == 1 && calories < 100) {
		cout << "Fruit" << endl;
	}
	else if (answer == 1 && calories >= 100) {
		cout << "Oatmeal" << endl;
	}
	else if (answer == 0 && calories < 200) {
		cout << "Power bar" << endl;
	}
	else if (answer == 0 && calories >= 200) {
		cout << "Anything" << endl;
	}


}
