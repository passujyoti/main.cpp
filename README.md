// CONSTUCRTOR //

/*#include <iostream>
using namespace std;
call mycall {
    private:
    mycall(){
        cout<<"marsidi"<<;
    }
};
int main (){

mycall myobj ;
class myclass{
        public:
        myclass(){
            cout<<"hello jyoti";
        }
    };
    int main()
    {

    myclass myobj;
    
    return 0;
}
 updated for PR
// CONSTRUCYOR
#include<iostream>
using namespace std;
class  mycar{
public:
mycar(){
    cout<<"cat,dog"<<"\n";
    cout<<"anjali";
}
};
int main (){
    mycar obj;
    return 0;
}

#include <iostream>
using namespace std;
class car {
    public:
   string  brand;
   string model;
   int year;
   car(string x,string y,int z){
 brand=x;
    model=y;
    year =z;

   }
};
int main (){
    car carobj1("BMW","FORTUNE",1935);
    car carobj2("ford","mustaj",1995);

    cout<<carobj1.brand<<" "<<carobj1.model<<" "<<carobj1.year<<"\n";
    cout<<carobj2.brand<<" "<<carobj2.model<<" "<<carobj2.year<<"\n";
    }


#include <iostream>
using namespace std;
class add{                          //the class
    int c;                              //access
    public:
    add(int a,int b);                    //constructor
    void display();
    ~add (){
        cout<<"\n object are distroyed";
    }include <iostream>

// Function declaration with void return type
void displayMessage() {
    std::cout << "Hello, World!" << std::endl;
}

int main() {
    // Calling the function
    displayMessage();
    
    return 0;
}
};
add::add(int a,int b){
    c=a+b;
}
void add::display (){
    cout<<"addition of two number is:"<<c;
}
int main(){
    int c ,d;
    cout<<"enter the value of c & d"<<"\n";
    cin>>c>>d;
    add a1(c,d);
    a1 .display();
}

#include <iostream>
using namespace std;
class add{
    int c;
    public:
    add(int a,int b);
    void display ();
        ~add (){
            cout<<"\n oject the distoryed";
        }
};
add::add(int a,int b){
    c=a+b;
}
void add::  display()
{
cout<<"the addition of two number is"<<c;
}
int main(){
    int c,d;
    cout<<"enter the value of c & d"<<"\n";
    cin>>c>>d;
    add a1 (c,d);
    a1.display();5
}

// WAP to subtraction two number using construstor & distructor in c++


#include <iostream>
using namespace std;
class sub{
    int c;
    public:
    sub(int a,int b);
    void display ();
    ~sub(){
        cout<<"\nobject are distoryed";
    }
};
sub ::sub(int a,int b){
    c=a*b;
    }
    void sub::display(){
        cout<<"the subtraction of two value is:"<<c;
    }
    int main()
    {
        int c,d;
        cout<<"enter the value of c & d"<<"\n";
        cin>>c>>d;
        sub a1(c,d);
        a1 . display ();
            }

// PONTER

 #include <iostream>
  using namespace std;
int main ()
{
 int var1=3;
int var2=24;
int var3=17;                   
 cout<<"address of the var1 "<<&var1<<endl;
cout<<"address of the var2 "<<&var2<<endl;
cout<<"address of the var3 "<<&var3<<endl;
                return 0;

 }

//  POINTER //

 #include <iostream>
using namespace std;
int main()
{
// declare variables
int var1 = 3;
int var2 = 24;
int var3 = 17;
// print address of var1
cout<< "Address of var1: "<<&var1 <<endl;
// print address of var2
cout<< "Address of var2: " <<&var2 <<endl;
// print address of var3
cout<< "Address of var3: " <<&var3 <<endl;
return 0;
}

// CLASS 

#include <iostream>
using namespace std;
class Box{
    public:
    double lenght ;
    double breadth;
    double height;

};
int main (){
    Box Box1;
    Box Box2;
    double volume =0.0;
    

    Box1.height = 5.0;
    Box1.lenght =6.0;
    Box1.breadth = 7.0;

    // for 2nd Box

    Box2.height= 10.0;
    Box2.lenght =12.0;
    Box2.breadth= 13.0;
    volume = Box1.height*Box1.lenght*Box1.breadth; 
    cout<<"volume of the Box1:-"<<volume<<endl;
     volume = Box2.height*Box2.lenght*Box2.breadth; 
    cout<<"volume of the Box2:-"<<volume<<endl;
    return 0;
}

// SWAPPING TWO NUMBER USING FUNCTION***
#include <iostream>
using namespace std;
int main (){
    int a,b,temperture;
    cout<<"before swapping:-";
    cin>>a;
        cout<<"before swapping:-";
    cin>>b;
    temperture=a;
    a=b;
    b=temperture;
    cout<<"after swapping :"<<endl;
    cout<<"a="<<a;
    cout<<"b="<<b;
    return 0;
}

#include  <bits/stdc++.h>
using namespace std;

int main() {
    fstream f1, f2;
    string ch;
    f1.open("file1.txt", ios::in);
    f2.open("file2.txt", ios::out);
    while (!f1.eof()) {
        getline(f1, ch);
        f2 << ch << endl;
    }
    f1.close();
    f2.close();
    return 0;
}

int main() {
    // Declare and initialize two numbers
    int num1 = 5, num2 = 10;

    // Print the original numbers
    std::cout << "Before swapping: num1 = " << num1 << ", num2 = " << num2 << std::endl;

    // Call the swap function
    swapNumbers(num1, num2);

    // Print the swapped numbers
    std::cout << "After swapping: num1 = " << num1 << ", num2 = " << num2 << std::endl;*/

#include <iostream>

// Function to swap two numbers using reference variables
void swapNumbers(int &a, int &b) {
    int temp = a;
    a = b;
    b = temp;
}

int main() {
    // Declare and initialize two numbers
    int num1 = 5, num2 = 10;

    // Print the original numbers
    std::cout << "Before swapping: num1 = " << num1 << ", num2 = " << num2 << std::endl;

    // Call the swap function
    swapNumbers(num1, num2);

    // Print the swapped numbers
    std::cout << "After swapping: num1 = " << num1 << ", num2 = " << num2 << std::endl;

    return 0;
}
