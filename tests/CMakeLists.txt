add_executable(unit_test test.c)

target_link_libraries(unit_test ${LIBCONFIG_LIBRARIES} automata_incl rt)
