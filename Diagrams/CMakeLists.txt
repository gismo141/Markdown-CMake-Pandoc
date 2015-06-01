add_custom_target(diagramm ALL
	COMMAND /usr/local/bin/dot -Tpdf ${CMAKE_CURRENT_SOURCE_DIR}/diagramm.dot -o ${CMAKE_CURRENT_BINARY_DIR}/diagramm.pdf
)