set(SOURCES
    ddffield.cpp
    ddffielddefn.cpp
    ddfmodule.cpp
    ddfrecord.cpp
    ddfsubfielddefn.cpp
    ddfutils.cpp
)

add_library(iso8211 ${SOURCES})

install(TARGETS iso8211
        LIBRARY DESTINATION ${CATKIN_PACKAGE_LIB_DESTINATION}
        ARCHIVE DESTINATION ${CATKIN_PACKAGE_LIB_DESTINATION}
        RUNTIME DESTINATION ${CATKIN_GLOBAL_BIN_DESTINATION}
)
