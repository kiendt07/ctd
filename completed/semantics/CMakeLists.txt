cmake_minimum_required(VERSION 3.5)

project(semantics_day4)

include_directories()
set(SourceFile main.c scanner.c debug.c parser.c reader.c charcode.c token.c error.c symtab.c semantics.c)

add_executable(semantics ${SourceFile})