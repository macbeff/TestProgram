#include "stdafx.h"
#include <iostream> 
 

void doPrint() 
{
    std::cout << "Is this a question?" << std::endl;
}
 

int main()
{
    std::cout << "Is... Is..." << std::endl;
    doPrint(); 
    std::cout << "Yes" << std::endl;
 
    return 0;
}
