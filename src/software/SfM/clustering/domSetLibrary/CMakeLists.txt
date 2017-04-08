add_library( domset domset.cc domset.h types.h )
target_include_directories( domset PUBLIC ${EIGEN_INCLUDE_DIRS} )
target_include_directories( domset PRIVATE ../../../../third_party )
