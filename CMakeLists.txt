file(GLOB_RECURSE SOURCES "src/lua/*.c")

idf_component_register(SRCS ${SOURCES} INCLUDE_DIRS "src/lua")
