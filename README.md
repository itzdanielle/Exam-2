# Exam-2
#include <iostream>
using namespace std;

int main() {
 const double coffee = 8.50;
 int pounds;
 double discount;
 double total;
 double finalTotal;

 cout << "How many pounds of coffe would you like?" << endl;
 cin >> pounds;

  total = pounds * 8.50;
 if (pounds >= 3) {
  discount = total * .12;
  finalTotal = total - discount;
  cout << "Your total is $" << finalTotal << endl;
 }

 else {
   cout << "Your total is $" << total << endl;
 }





}

