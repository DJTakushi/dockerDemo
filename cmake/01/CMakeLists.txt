cmake_minimum_required(VERSION 3.10)

project(Tutorial VERSION 1.0)

configure_file(TutorialConfig.h.in TutorialConfig.h)

add_executable(Tutorial ../Cmake/Help/guide/tutorial/Step1/tutorial.cxx)

target_include_directories(Tutorial PUBLIC "")

