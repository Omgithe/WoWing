set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${PROJECT_SOURCE_DIR}/bin)

#include_directories(${OPENGL_INCLUDE_DIR})

file(GLOB client_sources ./**.cpp ./**.c)

add_executable(
	client
	${client_sources}
	${lua_sources}
)
