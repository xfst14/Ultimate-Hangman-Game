cmake_minimum_required(VERSION 3.16)

project(UltimateHangmanGame
    VERSION 1.0
    LANGUAGES C)

set(CMAKE_C_STANDARD 11)
set(CMAKE_C_STANDARD_REQUIRED ON)

add_executable(ultimate_hangman
    hangmangame.c
)
