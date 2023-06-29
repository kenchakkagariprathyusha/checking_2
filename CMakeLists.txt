cmake_minimum_required(VERSION 3.0.0)




project(Single CXX)




#add_compile_options(-std=c11)




set( CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_HOME_DIRECTORY} )

   

set( CMAKE_LIBRARY_OUTPUT_DIRECTORY ${CMAKE_HOME_DIRECTORY} )

include(CTest)




enable_testing()

add_executable(Single single_linked_list.cpp )

set(CPACK_PROJECT_NAME ${PROJECT_NAME})




set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})




include(CPack)