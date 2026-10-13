---
{"dg-publish":true,"permalink":"/semester-1/programming-fundamentals/class-activities-programming-fundamentals/","dg-note-properties":{}}
---

# 10 Problems 

1. ATM Withdrawal : 
Take the account balance and withdrawal amount as input. If the withdrawal amount is greater than the available balance, display "Insufficient Balance"; otherwise, display the remaining balance.

``` cpp
#include <iostream>
using namespace std;
int main () {
    
    int account_balance;
    int withdrawal_amount;

cout << "Enter your account balance:";    
cin >> account_balance;
cout << "Enter your withdrawal amount:";    
cin >> withdrawal_amount;
    
if(withdrawal_amount>account_balance){
    cout << "Insufficient Balance";
} else {
    cout << "Remaining Balance";
}
    }
```

2. Even/Odd Bill Number
Take a grocery bill number as input and determine whether the bill number is even or odd.

```cpp
#include <iostream>
using namespace std;
int main () {
    
	int grocery_bill_number;

cout << "Enter the grocery bill number: "; cin >> grocery_bill_number;

if(grocery_bill_number % 2==0) {
    cout << "Is Even";
} else {
    cout << "Is Odd";
}
    }
```

3. Movie Ticket Discount
Take the customer's age as input. If the age is below 12, give a 50% discount on the ticket otherwise, charge the full ticket price.

```cpp
#include <iostream>
using namespace std;
int main () {
    
	int customer_age;

cout << "Enter the age: ";
cin >> customer_age;

if(customer_age < 12) {
    cout << "50% DISCOUNT";
} else {
    cout << "PAY FULL PRICE";
}
    }
```

4. Electricity Bill
Take the number of electricity units consumed as input. If the units are less than 100, charge Rs. 10 per unit; otherwise, charge Rs. 15 per unit.

```cpp
#include <iostream>
using namespace std;

int main() {
    double units, bill;
    cout << "Enter electricity units consumed: ";
    cin >> units;

    if (units < 100) {
        bill = units * 10;
    } else {
        bill = units * 15;
    }

    cout << "Total Bill: Rs. " << bill << endl;
    return 0;
}
```

5. Student Attendance
Take the total number of classes and attended classes as input. Calculate the attendance percentage and determine whether the student is eligible based on a minimum attendance requirement of 75%.

```cpp
#include <iostream>
using namespace std;

int main() {
    double totalClasses, attendedClasses;
    cout << "Enter total classes: ";
    cin >> totalClasses;
    cout << "Enter attended classes: ";
    cin >> attendedClasses;

    if (totalClasses > 0) {
        double percentage = (attendedClasses / totalClasses) * 100;
        cout << "Attendance Percentage: " << percentage << "%" << endl;

        if (percentage >= 75) {
            cout << "Status: Eligible" << endl;
        } else {
            cout << "Status: Not Eligible" << endl;
        }
    } else {
        cout << "Invalid total classes entered." << endl;
    }

    return 0;
}
```

6. Login System
Take a username and password as input. If both are correct, display "Login Successful"; otherwise, display "Invalid Credentials".

```cpp
#include <iostream>
#include <string>
using namespace std;

int main() {
    string username, password;
    const string correctUser = "admin";
    const string correctPass = "12345";

    cout << "Enter username: ";
    cin >> username;
    cout << "Enter password: ";
    cin >> password;

    if (username == correctUser && password == correctPass) {
        cout << "Login Successful" << endl;
    } else {
        cout << "Invalid Credentials" << endl;
    }

    return 0;
}
```

7. Shopping Discount
Take the total shopping amount as input. If the amount is greater than Rs. 10,000, apply a 10% discount; otherwise, provide no discount.

```cpp
#include <iostream>
using namespace std;

int main() {
    double totalAmount;
    cout << "Enter total shopping amount: ";
    cin >> totalAmount;

    if (totalAmount > 10000) {
        double discount = totalAmount * 0.10;
        totalAmount -= discount;
        cout << "10% Discount Applied! Final Amount: Rs. " << totalAmount << endl;
    } else {
        cout << "No discount applied. Final Amount: Rs. " << totalAmount << endl;
    }

    return 0;
}
```

8. Temperature Alert
Take the temperature as input and display:
 Above 40 → "Extreme Heat"
 30–40 → "Hot"
 Below 30 → "Normal"

```cpp
#include <iostream>
using namespace std;

int main() {
    double temp;
    cout << "Enter temperature: ";
    cin >> temp;

    if (temp > 40) {
        cout << "Extreme Heat" << endl;
    } else if (temp >= 30) {
        cout << "Hot" << endl;
    } else {
        cout << "Normal" << endl;
    }

    return 0;
}
```

9. Parking Fee
Take the number of parking hours as input. Charge Rs. 100 for the first two hours and Rs. 50 for each additional hour.

```cpp
#include <iostream>
using namespace std;

int main() {
    double hours, fee;
    cout << "Enter parking hours: ";
    cin >> hours;

    if (hours <= 2) {
        fee = 100;
    } else {
        fee = 100 + (hours - 2) * 50;
    }

    cout << "Total Parking Fee: Rs. " << fee << endl;
    return 0;
}
```

9. Mobile Balance
Take the current mobile balance and recharge amount as input. Calculate and display the new balance

```cpp
#include <iostream>
using namespace std;

int main() {
    double currentBalance, rechargeAmount;
    cout << "Enter current balance: ";
    cin >> currentBalance;
    cout << "Enter recharge amount: ";
    cin >> rechargeAmount;

    double newBalance = currentBalance + rechargeAmount;
    cout << "New Balance: Rs. " << newBalance << endl;

    return 0;
}
```

10. Exam Pass/Fail
Take the student's marks as input. If the marks are 50 or above, display "Pass"; otherwise, display "Fail".

```cpp
#include <iostream>
using namespace std;

int main() {
    double marks;
    cout << "Enter marks: ";
    cin >> marks;

    if (marks >= 50) {
        cout << "Pass" << endl;
    } else {
        cout << "Fail" << endl;
    }

    return 0;
}
```

