Copied common-debug and common-release and common to /Maps/
Replaced OMIM_ROOT in common with path to omim checkout
Replaced all ../../data paths with ../../omim/data in *.pbxproj files (this was because omim as at ../../ relative to our project - we need to handle this for any case where omim migt be elsewhere.)
Added private.h to /Maps/ and changed the path referencing it
Corrected OMIM_ROOT to not be a relative path
