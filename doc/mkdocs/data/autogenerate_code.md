# How to autogenerate C++ code

!!! warning
    This tutorial is not yet ready

The capability of autogenerating C++ code from a Simulink model is provided by Simulink Coder. BlockFactory received a preliminary support of this toolbox, and only basic features are currently supported. Following the previous how-to, check these links for a simple example:

- [`AutogenerationExample.mdl`](https://github.com/robotology/blockfactory/tree/master/example/matlab/AutogenerationExample.mdl) A Simulink model with the right configuration of Simulink Coder
- [`example/matlab/AutogenerationExample_grt_rtw`](https://github.com/robotology/blockfactory/tree/master/example/matlab/AutogenerationExample_grt_rtw) The folder containing the autogenerated sources
- ['example/matlab/CMakeLists.txt'](https://github.com/robotology/blockfactory/blob/master/example/matlab/CMakeLists.txt) The CMake file for compiling the generated code
- [`src/main.cpp`](https://github.com/robotology/blockfactory/tree/master/example/src/main.cpp) A simple main function to execute the autogenerated code
