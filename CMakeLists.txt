cmake_minimum_required( VERSION 3.2 )

project( "VulkanGuide2" )

include_directories( ${PROJECT_SOURCE_DIR}/external/glfw/include )
include_directories( ${PROJECT_SOURCE_DIR}/external/glm/glm )

add_subdirectory( project0_model_loader )
