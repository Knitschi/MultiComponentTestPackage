include(cpfAddCppPackageComponent)

set( publicHeader
	function.h
)

set( sourceFiles
	function.cpp
)

############################################## Add Package #################################
cpfAddCppPackageComponent( 
	TYPE					LIB
	OWNER 					Knitschi
	BRIEF_DESCRIPTION		"A C++ dummy libary used for testing the CPF"
	PRODUCTION_FILES		${sourceFiles}
	PUBLIC_HEADER			${publicHeader}
	CPP_NAMESPACE			MultiComp
)
