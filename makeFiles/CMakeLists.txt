cmake_minimum_required(VERSION 2.8)
find_package( OpenCV REQUIRED )
project( image )
add_executable( image image.cpp)
target_link_libraries(image ${OpenCV_LIBS})
