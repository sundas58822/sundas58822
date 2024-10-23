
#include<iostream>
using namespace std;

int main() {
    int i = 1;
    int password;
    int correctPassword = 12345;  
    
    while(i <= 5) {
        cout << "Enter the password: ";
        cin >> password;
        i++;
    }
        if(password == correctPassword) {
            cout << "The password is correct!"<< "Login successful." << endl;
             
        } else {
            cout << "Incorrect password"<<" Please try again"<<endl;
        
  }
    
    
    
    return 0;
}
