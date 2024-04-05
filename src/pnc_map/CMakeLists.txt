project(pnc_map)

add_library(${PROJECT_NAME}
SHARED
pnc_map.cpp)

target_link_directories(${PROJECT_NAME}
PUBLIC
${PNC_Map_Dir}
)

