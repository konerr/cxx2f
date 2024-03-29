cmake_minimum_required (VERSION 3.1)
project(main Fortran CXX)
#

add_definitions(-DFORTRAN_UNDERSCORE -DFORTRAN_LOWERCASE)
add_executable(rflump main.C clop.C rflump.F90)

#target_link_libraries(rflump )
# target_link_libraries(main GKlib metis)
