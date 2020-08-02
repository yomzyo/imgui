add_library(imgui   imgui.cpp
                    imgui_widgets.cpp
                    imgui_draw.cpp
                    imgui_demo.cpp
                    examples/imgui_impl_glfw.cpp
                    examples/imgui_impl_opengl3.cpp)

target_include_directories(imgui PUBLIC "${CMAKE_CURRENT_SOURCE_DIR}")
