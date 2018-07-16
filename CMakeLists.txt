add_executable(leocpp_pgm src/cppPgm.cpp)
add_executable(lnrd_pgm src/cppPgm2.cpp)
target_link_libraries(lnrd_pgm abc.so)
target_link_libraries(leocpp_pgm abx.so xyz.so)
