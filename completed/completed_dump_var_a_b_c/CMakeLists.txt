cmake_minimum_required(VERSION 3.5)

project(completed)
include_directories()
set(SourceFile main.c scanner.c debug.c parser.c reader.c charcode.c token.c error.c symtab-hoanthien.c semantics.c codegen.c instructions.c)

add_executable(completed ${SourceFile})