aux_source_directory(. DIR_SRCS)
add_executable(tutorial04_organizing ../glad.c ${DIR_SRCS})
target_link_libraries(tutorial04_organizing glfw3)
