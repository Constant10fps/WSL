## A Project made in WSL
My main reason to create this was to practice working in WSL and VS Code connected to it. This is the code that sits in the ```heyworld.cpp``` file:

```cpp
#include <iostream>
#include <vector>
#include <string>

using namespace std;

int main()
{
   vector<string> msg {"Hello", "C++", "World", "from", "VS Code", "and the C++ extension!"};

   for (const string& word : msg)
   {
      cout << word << " ";
   }
   cout << endl;
}
```
It was taken from the official tutorial on how to use VS Code with WSL.
This repository is going to be updated with the more I do on the VM.