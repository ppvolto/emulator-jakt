cmake_minimum_required(VERSION 3.16)

project(
    riskvjakt
    DESCRIPTION "RISC-V Emulator written in Jakt"
    LANGUAGES CXX)

find_package(Jakt CONFIG REQUIRED)

add_jakt_executable(riscvjakt
    MAIN_SOURCE src/main.jakt
#    MODULE_SOURCES
#        src/system.jakt
)

target_compile_definitions(riscvjakt PRIVATE SDL_MAIN_HANDLED)
