AUX_SOURCE_DIRECTORY(. src_files)

ADD_EXECUTABLE(plusaudio-plugin ${src_files})

INSTALL(TARGETS plusaudio-plugin
	RUNTIME DESTINATION bin
)