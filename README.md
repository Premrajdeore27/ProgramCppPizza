# ProgramCppPizza(Using GETLINE)

#include <iostream>
#include <string>
using namespace std;

int main()
{
  
    string name = "Farm House";
    char size;
    int personItServes;
    float retailPrice;
    
    cout << "Enter Your Favorite pizza: ";
    getline(cin,name);     #Get Efficient output . don't do whitespace enconter
    cout << "Enter the Size Of The pizza as either 's','M' or ' L': ";
    cin >> size;
    cout << "Enter the number of person it Serves: ";
    cin >> personItServes;
    cout << "Enter the retailPrice: ";
    cin >> retailPrice ;
  
   cout << " Yay! You have Ordered a " << name << " Pizza of size " << size << " that Serves " << personItServes << ".\n Please Rs."
    << retailPrice <<" to the delivery person. ";


    return 0;
}
