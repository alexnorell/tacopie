target_sources(tacopie
	PUBLIC
		tcp_socket.cpp;
)
target_include_directories(tacopie
	PUBLIC
		${CMAKE_CURRENT_SOURCE_DIR}
)