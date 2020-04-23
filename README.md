#include<iostream>

using namespace std;

class example
{
public:
	example()
	{
		std::cout<<"this is constructor"<<endl;
	}
};
int main()
{
	example e1;
	return 0;
}
