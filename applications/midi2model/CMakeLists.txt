
include(AfAddQtConsoleApplication)

af_add_qt_console_application(

	TARGET midi2model

	SOURCES
		src/main.cpp

	LINK_LIBRARIES
		Af::Midi2Model
)
