# WebGPU C++ Header Generator for CMake

## Required

Python > 3.8  
Standard WebGPU header: https://github.com/webgpu-native/webgpu-headers  

## Usage

CMake: `target_link_libraries(TARGET PUBLIC webgpu-cpp-header)`  
CMake: `set(WEBGPU_NATIVE_HEADER "/path/to/header")`  
C++: `#include "webgpu/webgpu_cpp.hpp"`  

## Style

```
wgpu::InstanceDescriptor inst_desc;
auto instance = wgpu::CreateInstance(&inst_desc);
...
```
