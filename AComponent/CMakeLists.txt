include(cpfAddCppPackage)

set( briefDescription "A dummy package-component." )

set( PACKAGE_PRODUCTION_FILES
	main.cpp
	function.cpp
	function.h
)

############################################## Add Package #################################
cpfAddCppPackage( 
	TYPE					CONSOLE_APP
	BRIEF_DESCRIPTION		${briefDescription}
	PRODUCTION_FILES		${PACKAGE_PRODUCTION_FILES}
)
