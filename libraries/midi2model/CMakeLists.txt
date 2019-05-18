
include(AfAddQtSharedLibrary)

af_add_qt_shared_library(

	TARGET midi2model
	VERSION 0.1.0

	COMPILE_DEFINITIONS
		BUILDING_AF_MIDI2MODEL_LIBRARY

	SOURCES
		src/midi2model.cpp
		src/midi2model.h

	LINK_LIBRARIES
		Qt::Core
)
