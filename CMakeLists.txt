        cmake_minimum_required(VERSION 2.8.3)
    project(urdf_tests)

    find_package(catkin REQUIRED)

    ## System dependencies are found with CMake's conventions
    find_package(catkin REQUIRED COMPONENTS roscpp tf geometry_msgs urdf rviz xacro std_msgs )

    ## Specify additional locations of header files
    ## Your package locations should be listed before other locations
    include_directories(include ${catkin_INCLUDE_DIRS})

    ## Call this before add_executable, else the executable might not be
    ## visible to rosrun
    catkin_package()

    ## Declare a C++ executable
    #add_executable(hello src/hello.cpp)


    ## Specify libraries to link a library or executable target against

    #target_link_libraries(hello
    #   ${catkin_LIBRARIES}
    # )
