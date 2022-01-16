# mytestProject
#include<iostream>

#define DAY_SEC 86400
#define HOURS_SEC 3600
#define MINUTES 60

using std::cout;
using std::endl;
using std::cin;

int main()
{
    long long  numberSec;
    
    cout << "Enter the numbers of seconds: ";
    cin >> numberSec;
    cout << numberSec << " seconds = " << numberSec / DAY_SEC;
    cout <<" days, " << (numberSec % DAY_SEC) / HOURS_SEC;
    cout <<" hours, " << (numberSec % HOURS_SEC) / MINUTES;
    cout <<" minutes, " << numberSec % MINUTES <<" seconds" << endl;


    return 0;
}
