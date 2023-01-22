cmake_minimum_required(VERSION 3.5)

project(leaver_lib) 

file(GLOB
	public_headers "*.h"
	sources "*.cpp")

add_library(${PROJECT_NAME} ${sources} ${public_headers})
