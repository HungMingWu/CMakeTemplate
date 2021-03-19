cmake_minimum_required (VERSION 3.15)
add_executable (CMakeTemplate main.cpp)
target_link_libraries(CMakeTemplate
PRIVATE
	fmt::fmt-header-only
)

