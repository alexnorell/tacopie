target_sources(tacopie
	PRIVATE
		tcp_socket.cpp;
)
target_include_directories(tacopie
	PRIVATE
		${CMAKE_CURRENT_SOURCE_DIR}
)