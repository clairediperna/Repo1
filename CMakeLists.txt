# CMakeList.txt : CMake project for Quiz_1_DiPerna_CMake, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (Quiz_1_DiPerna_CMake "Quiz_1_DiPerna_CMake.cpp" "Quiz_1_DiPerna_CMake.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET Quiz_1_DiPerna_CMake PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
