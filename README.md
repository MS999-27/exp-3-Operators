# exp-3-Operators
# Aim
To learn about arithmetic, logical, miscelleaneous and assignment operators on c++.
# Software Used
VS Code

# Problem Statement
1.) Write a code for boolean operators in c++.
2.) Write a code for checking equality of values in c++.
3.) Write a code for checking inequality of values in c++.

# Theory
The boolalpha function is a manipulator that sets the boolalpha flag, which tells the stream to read or write a bool value as text, according to the stream's locale.

The equal-to operator ( == ) returns true if both operands have the same value; otherwise, it returns false . The not-equal-to operator ( != ) returns true if the operands don't have the same value; otherwise, it returns false .
# Program codes
```javascript
//Bool
#include<iostream>
 using namespace std;
 int main()
{
    bool a = true;
    bool b = true;
    cout<<boolalpha;
    cout<<"a&&b: "<<(a&&b)<<endl;
    return 0;
}

//Equality Operator
#include<iostream>
using namespace std;
int main(){
    int a,b;
    cout<<"Enter first number: ";
    cin>>a;
    cout<<"Enter second number: ";
    cin>>b;
    cout<<"a==b: "<<(a==b)<<endl;
    return 0;
}

//Inequality Operator
#include<iostream>
 using namespace std;
 int main()
{
    int a,b;
    cout<<"enter first number: ";
    cin>>a;
    cout<<"enter second number: ";
    cin>>b;
    cout<<"a!=b: "<<(a!=b)<<endl;
    return 0;
}


 #include<iostream>
 using namespace std;
 int main()
{ int a,b;
    
    a = 1;
    b = 1;
    cout<<"a&b: "<<(a&b)<<endl;
    cout<<"a|b: "<<(a|b)<<endl;
    cout<<"a^b: "<<(a^b)<<endl;
    cout<<"a: "<<(~a)<<endl;
    cout<<"a<<b: "<<(a<<b)<<endl;
    cout<<"a>>b: "<<(a>>b)<<endl;
    
    return 0;
}
```

# Output
![Exp3-noteeq](https://github.com/user-attachments/assets/3fd712ac-788b-4547-a7e5-742b52090565)
t![Exp3-eq-logical ](https://github.com/user-attachments/assets/7b12386c-5b77-4187-b7b6-821302ede59f)
![Exp3-bool](https://github.com/user-attachments/assets/acbc6dbf-b3b7-491e-9f99-fd5952b6d6e3)
![Exp3 OP](https://github.com/user-attachments/assets/9ce68ba2-c213-4229-a2af-e001e275aa37)

# Conclusion
We learnt to use different operator in c++.
