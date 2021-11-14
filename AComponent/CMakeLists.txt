include(cpfInitPackageProject)
include(cpfAddCppPackage)

cpfInitPackageProject()

set( briefDescription "A dummy package-component." )
set( longDescription "" )

############################################## Define source files ###################################################

set( PACKAGE_PRODUCTION_FILES
	main.cpp
	function.cpp
	function.h
)

############################################## Add Package #################################
cpfAddCppPackage( 
	PACKAGE_NAMESPACE		a
	TYPE					CONSOLE_APP
	BRIEF_DESCRIPTION		${briefDescription}
	LONG_DESCRIPTION		${longDescription}
	PRODUCTION_FILES		${PACKAGE_PRODUCTION_FILES}
)
