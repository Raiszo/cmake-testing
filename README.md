# cmake-testing
cmake for using in visual studio (no IDE)


```powershell
cd build
cmake -G "Visual Studio 15 2017 Win64" ..\src\
msbuild .\hello-cmake.sln
cd debug
.\hello-cmake.exe
```

To get a release :D
```powershell
msbuild /t:Build /p:Configuration=Release .\hello-cmake.sln 
```