project(level1)

find_package(Curses REQUIRED)

add_executable(p01_running_letter p01_running_letter/main.cpp)
target_include_directories(p01_running_letter PRIVATE ${CURSES_INCLUDE_DIR})
target_link_libraries(p01_running_letter PRIVATE ${CURSES_LIBRARIES})

add_executable(p02_is_prime p02_is_prime/main.cpp)

add_executable(p03_all_primes p03_all_primes/main.cpp)

add_executable(p04_goldbach p04_goldbach/main.cpp)

add_executable(p05_encrypt_decrypt p05_encrypt_decrypt/main.cpp)

add_executable(p06_hanoi p06_hanoi/main.cpp)

add_executable(p07_maze p07_maze/main.cpp)
target_include_directories(p07_maze PRIVATE ${CURSES_INCLUDE_DIR})
target_link_libraries(p07_maze PRIVATE ${CURSES_LIBRARIES})

add_executable(p08_push_boxes p08_push_boxes/main.cpp)
target_include_directories(p08_push_boxes PRIVATE ${CURSES_INCLUDE_DIR})
target_link_libraries(p08_push_boxes PRIVATE ${CURSES_LIBRARIES})

add_executable(p09_linked_list p09_linked_list/main.cpp)

add_executable(p10_warehouse p10_warehouse/main.cpp)