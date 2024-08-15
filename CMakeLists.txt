project(IconFontCppHeaders)

add_library(IconFontCppHeaders INTERFACE
        IconsMaterialDesignIcons.h
        IconsMaterialDesign.h
)

target_include_directories(IconFontCppHeaders INTERFACE ./)
