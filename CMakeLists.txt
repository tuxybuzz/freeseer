set(FREESEER_SRC ${CMAKE_CURRENT_LIST_DIR}/src)

cmake_minimum_required (VERSION 2.8)
project(Freeseer)

include(${FREESEER_SRC}/freeseer/framework/CMakeLists.txt)
include(${FREESEER_SRC}/freeseer/frontend/default/CMakeLists.txt)
include(${FREESEER_SRC}/freeseer/frontend/configtool/CMakeLists.txt)
include(${FREESEER_SRC}/freeseer/frontend/talkeditor/CMakeLists.txt)
