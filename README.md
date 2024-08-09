# Exp_1
Aim -> (A) To print hello world command. (B) To make a calculator.

Theory -> C++ is a high level object-oriented programming language. It is also known as "C with class". It was developed by Bjarne Stroustrup in 1979. It implements all the OOPs concepts. It is a compiled language.

(A) To print an output in C++ we use cout command. Syntax: cout<<value_to_print<<value_to_print;

(B) Basic arithematic operations like addition, subtravtion, multiplication and division can be performed. To take input from the user, we use "cin" command.

#CODE A:

```
#include<iostream>
using namespace std;
int main()
{
    cout<<"HELLO WORLD!";     //Output - HELLO WORLD!
    return 0;
}

```

#CODE B:

```
#include<iostream>
using namespace std;
int main() {
    int n1, n2, sum=0, sub, prod, div;
    cout<<"Enter first number.";           //Output - Enter first number.25
    cin>>n1;
    cout<<"Enter second number.";          //Enter second number.5
    cin>>n2;
    sum=n1+n2;
    cout<<"Sum of the numbers is: "<<sum<<"\n";    //Sum of the numbers is: 30
    sub=n1-n2;
    cout<<"Difference of the numbers is: "<<sub<<"\n";  //Difference of the numbers is: 20
    prod=n1*n2;
    cout<<"Product of the numbers is: "<<prod<<"\n";        //Product of the numbers is: 125 
    div=n1/n2;
    cout<<"Quotient is: "<<div<<"\n";                      //Quotient is: 5
    return 0;
}
```


Output A: 

<img width="569" alt="Screenshot 2024-08-09 at 11 53 42" src="https://github.com/user-attachments/assets/4225f0af-93da-43e7-b751-a3ea7c981fe4">

Output B:

<img width="547" alt="Screenshot 2024-08-09 at 11 53 56" src="https://github.com/user-attachments/assets/caa2ea5a-46ea-4f4b-bae6-8db94c900e42">

Syntax: cin>>value_to_be_entered;

Conclusion -> In this experiment, I learnt about C++ programming lnguage, its basic commands and also made a program for calculator.
