set(SOURCES
  test.cpp
)

add_executable(paltest_formatmessagew_test5
  ${SOURCES}
)

add_dependencies(paltest_formatmessagew_test5 coreclrpal)

target_link_libraries(paltest_formatmessagew_test5
  ${COMMON_TEST_LIBRARIES}
)
