cmake_minimum_required(VERSION 3.14.19050301.0)
project(CMAKE_TRY_COMPILE CXX)
set(CMAKE_VERBOSE_MAKEFILE 1)
set(CMAKE_CXX_FLAGS "/DWIN32 /D_WINDOWS /W3 /GR /EHsc")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} ${COMPILE_DEFINITIONS}")
set(CMAKE_EXE_LINKER_FLAGS "${CMAKE_EXE_LINKER_FLAGS} ${EXE_LINKER_FLAGS}")
include_directories(${INCLUDE_DIRECTORIES})
set(CMAKE_SUPPRESS_REGENERATION 1)
link_directories(${LINK_DIRECTORIES})
cmake_policy(SET CMP0065 OLD)
cmake_policy(SET CMP0083 OLD)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY "E:/BaiduNetdiskDownload/study/vio/5/第5节BA_schur/BA_schur/out/build/x64-Debug/CMakeFiles/CMakeTmp")
add_executable(cmTC_a8073 "C:/Program Files (x86)/Microsoft Visual Studio/2019/Community/Common7/IDE/CommonExtensions/Microsoft/CMake/CMake/share/cmake-3.14/Modules/CMakeCXXCompilerABI.cpp")
target_link_libraries(cmTC_a8073 ${LINK_LIBRARIES})
