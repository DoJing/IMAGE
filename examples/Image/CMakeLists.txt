include_directories(${MATH_INCLUDE_DIRS})
include_directories(../../include)
include_directories(../../src)
include_directories(../../../MATH)
link_directories(${MATH_LIBRARY_DIRS})
set(EXECUTABLE_OUTPUT_PATH ../../examples_bin)
link_directories(/home/doing/gitHub/MATH/lib)
add_executable(image_main image_main.cpp)
target_link_libraries(image_main image math)
