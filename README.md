```cpp
#include <iostream>
#include <string>
#include <vector>

struct strings {
  std::string name;
　std::string country;
　std::string mainProgrammingLanguages;
};

int main(void) {
　std::vector<strings> profile(10);
　profile[0].name = "David";
　profile[0].country = "Germany";
  profile[0].mainProgrammingLanguages = "TypeScript";

  std::cout << "My name is ";
　std::cout << profile[0].name;
　std::cout << ", I  come from ";
　std::cout << profile[0].country;
　std::cout << " and my main programming language is ";
　std::cout << profile[0].mainProgrammingLanguages;
　std::cout << ". I also work with JavaScript, Node.js, SQL and C#.";
　return 0;
}
```
