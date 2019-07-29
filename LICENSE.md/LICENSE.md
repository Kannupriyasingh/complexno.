#include <iostream>
#include<cmath>

using namespace std;

class complex
{
public:
    double re,im;
//member function method

  double norm()
  {
         return sqrt (re*re +im*im);
  }

void print ()
{
    cout <<"|"<<re<<"+j"<<im<<"|=";
    cout <<norm();
}

};

int main()
{
    complex c={4.2 ,5.6};



    c.print();

    return 0;
}
