add_library(tacopie STATIC)
target_sources(tacopie
	PUBLIC
		tacopie.hpp;
)
target_include_directories(tacopie
	PUBLIC
		${CMAKE_CURRENT_SOURCE_DIR}
)
add_subdirectory(utils)
add_subdirectory(network)
