project(linenoise C)

add_library(linenoise STATIC linenoise.c example.c)
target_compile_definitions(linenoise PUBLIC)