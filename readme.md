### This repo contains settings for vscode in order to debug c++11 ( can be edited to work on newer versions ) on MacOS. Just drop it into the .vscode project folder
### Compiling single file for debugging within a folder:
```sh
g++ -Wall -std=c++11 -o main main.cpp --debug
```
### Compiling main with multiple header files
```sh
g++ -Wall -std=c++11 main.cpp BaseClass.cpp DerivedClass.cpp ExtraClass.cpp -o
main --debug
```
### ( main can be whatever you want your binary to be named )
### Finally, open your debugger in vscode and step through your code