build_modules(${CMAKE_CURRENT_SOURCE_DIR})

install(FILES gameserv.example.conf
  DESTINATION ${CONF_DIR}
)
