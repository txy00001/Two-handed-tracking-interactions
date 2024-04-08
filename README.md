# hand-tnn

3D手势交互TNN部署工程，基于cmake构建跨平台编译

### windows平台构建
1. 安装cmake>3.4版本
2. 安装visual studio 

```PowerShell
mkdir build/x64 
cmake ./ -B build/x64 -A x64 -G "Visual Studio 17 2022"
cd build/x64
cmake --build ./
```
