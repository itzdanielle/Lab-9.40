# Lab-9.40
#include <iostream>
#include <string>
using namespace std;

int main() {
 
  int number;
  string name;
  

  cout << "Hey what's your name?" << endl;
  cin >> name;

  cout << "Pick a numer between 1 and 5:" << endl;
  cin >> number;

  if (number == 1) {
    cout << "how are you " << name << "?" << endl;
  }
  else if (number == 2) {
    cout << "Greetings " << name << endl;
  }
  else if (number == 3) {
    cout << "How is your day going " << name << "?" << endl;
  }
  else if (number == 4) {
    cout << "Have a great day " << name << "!" << endl;
  }
  else if (number == 5) {
    cout << "Have a great rest of your day " << name << "!" << endl;
  }

}
