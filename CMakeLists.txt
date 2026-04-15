cmake_minimum_required(VERSION 3.16)

project(UltimateHangmanGame
    VERSION 1.0
    LANGUAGES C)

set(CMAKE_C_STANDARD 11)
set(CMAKE_C_STANDARD_REQUIRED ON)

find_package(SDL2 REQUIRED)
find_package(SDL2_ttf_required)
find_package(SDL2_mixer REQUIRED)

add_executable(ultimate_hangman
    src/main.c
    src/game.c
    src/renderer.c
    src/ui.c
    src/assets.c
)

target_include directories (ultimate_hangman PRIVATE
    $(SDL2_INCLUDE_DIRS)
    $(SDL2_TTF_INCLUDE_DIRS)
    $(SDL2_MIXER_INCLUDE_DIRS)
)

target_link libraries (ultimate_hangman PRIVATE
    $(SDL2_LIBRARIES)
    SDL2_ttf
    SDL2_mixer
)