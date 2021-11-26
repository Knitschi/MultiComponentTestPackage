include(cpfPackageProject)

cpfPackageProject(
    BRIEF_DESCRIPTION "A repository containing dummy code that is used to test the multi-component-package feature of the CMakeProjectFramework."
    LONG_DESCRIPTION ""
    OWNER Knitschi
    WEBPAGE_URL "MultiComponentTestPackage"
    TARGET_NAMESPACE mctp
    COMPONENTS
        AComponent
        BComponent
    PACKAGE_FILES
        LICENSE
        README.md
)
