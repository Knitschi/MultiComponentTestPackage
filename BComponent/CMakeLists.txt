include(cpfAddCppPackageComponent)

set( PACKAGE_PUBLIC_HEADER
	function.h
)

set( PACKAGE_PRODUCTION_FILES
	function.cpp
)

############################################## Add Package #################################
cpfAddCppPackageComponent( 
	TYPE					LIB
	OWNER 					Knitschi
	BRIEF_DESCRIPTION		"A C++ dummy libary used for testing the CPF"
	PUBLIC_HEADER			${PACKAGE_PUBLIC_HEADER}
)
