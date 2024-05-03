if(NOT ${INSTALL_LIBS_ONLY})
    file(GLOB INCLUDE_FILES "json/*.h")
    install(FILES
        ${INCLUDE_FILES}
        DESTINATION ${CMAKE_INSTALL_INCLUDEDIR}/json)
endif()