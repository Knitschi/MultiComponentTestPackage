include(cpfInitPackageProject)

cpfInitPackageProject(
    BRIEF_DESCRIPTION "A repository containing dummy code that is used to test the multi-component-package feature of the CMakeProjectFramework."
    LONG_DESCRIPTION ""
    OWNER Knitschi
    WEBPAGE_URL "MultiComponentTestPackage"
    TARGET_NAMESPACE mctp
)

add_subdirectory(AComponent)
add_subdirectory(BComponent)