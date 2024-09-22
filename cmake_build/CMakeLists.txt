cmake_minimum_required(VERSION 3.11)
project(study)

include_directories(
    include
    ${OpenCV_INCLUDE_DIRS}
)

find_package(OpenCV REQUIRED)

