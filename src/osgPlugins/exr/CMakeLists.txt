INCLUDE_DIRECTORIES( ${OPENEXR_INCLUDE_DIR}/OpenEXR )

SET(TARGET_SRC ReaderWriterEXR.cpp )

SET(TARGET_EXTERNAL_LIBRARIES ${OPENEXR_LIBRARIES} ${ZLIB_LIBRARY} )

#### end var setup  ###
SETUP_PLUGIN(exr)
