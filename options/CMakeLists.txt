otr_module(options NO-COMPAT BIN)
if(NOT WIN32 AND NOT APPLE)
    target_link_libraries(opentrack-options rt)
endif()
