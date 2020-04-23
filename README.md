#include<iostream>

using namespace std;

class example
{
public:
	example()
	{
		std::cout<<"this is constructor"<<endl;
	}
	virtual	void display()
	{
	  std::cout<<"This is base class fun"<<endl;
	}
};

class example2:private example
{
public:
        example2()
        {
                std::cout<<"this is dervied constructor"<<endl;
        }
	void display()
	{
		std::cout<<"this is dervied fun"<<endl;
	}
};

int main()
{
	example e2;
	return 0;
}
