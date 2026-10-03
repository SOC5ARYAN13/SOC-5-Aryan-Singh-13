#include <iostream>
using namespace std;

class Rectangle
{
private:
float length, breadth;

public:

void getData()
{
cout << "Enter length: ";
cin >> length;

cout << "Enter breadth: ";
cin >> breadth;
}

float area();
float perimeter();

void display()
{
cout << "Area = " << area() << endl;

cout << "Perimeter = " << perimeter() << endl;

}
};


float Rectangle::area()
{
return length * breadth;
}


float Rectangle::perimeter()
{
return 2 * (length + breadth);

}

int main()
{
Rectangle r;

r.getData();
r.display();

return 0;
}