include(cpfAddCppPackageComponent)

set( briefDescription "A dummy package-component." )

set( publicHeader
	function.h
)

set( sourceFiles
	function.cpp
)

############################################## Add Package #################################
cpfAddCppPackageComponent( 
	TYPE					LIB
	BRIEF_DESCRIPTION		${briefDescription}
	PRODUCTION_FILES		${sourceFiles}
	PUBLIC_HEADER			${publicHeader}
)
