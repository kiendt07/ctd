cmake_minimum_required(VERSION 3.5)

project(completed)
include_directories()
set(SourceFile main.c instructions.c VM.c)

add_executable(kplrun ${SourceFile})