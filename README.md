# cmake-testing
cmake for using in visual studio (no IDE)


```bash
cd build
cmake -G "Visual Studio 15 2017 Win64" ..\src\
msbuild .\hello-cmake.sln
cd debug
.\hello-cmake.exe
```