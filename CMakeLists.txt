# cmake_minimum_required(VERSION 3.4.1)
# PROJECT(projectname)

# set(project_name projectname)
# set(project_root ${PROJECT_SOURCE_DIR})
# set(project_src ${project_root}/src)
# set(project_include ${project_root}/include)
# set(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR})

# set(CMAKE_CXX_STANDARD 11)  #设置使用c11标准编译程序
# add_definitions(-std=c++11) #设置使用c11标准编译程序

# set(CMAKE_BUILD_TYPE "Debug") #Debug Release
# set(CMAKE_CXX_FLAGS_DEBUG "$ENV{CXXFLAGS} -O -Wall -g -ggdb -fpermissive")#在debug下不优化,即采用最低级别的O0
# set(CMAKE_CXX_FLAGS_RELEASE "$ENV{CXXFLAGS} -O3 -Wall")#在release下采用最高级别优化

# include_directories(
#     /usr/include/
#     ${project_include}
# )

# link_directories(
#     /usr/lib/aarch64-linux-gnu/
# )

# aux_source_directory(${project_src}/ src)

# add_executable(${project_name} ${src})

# target_link_libraries(
#     ${project_name}
#     -lpthread
#     -lmysqlclient
# )
