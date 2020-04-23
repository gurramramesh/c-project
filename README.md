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
class example2:public example
{
public:
        example2()
        {
                std::cout<<"this is dervied constructor"<<endl;
        }
};

int main()
{
	example e2;
	return 0;
}
