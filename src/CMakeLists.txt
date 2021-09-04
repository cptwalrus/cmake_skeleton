cmake_minimum_required(VERSION 3.14)

#######################
## SERVER BUILD INFO ##
#######################
add_executable(Server server.cpp)

target_include_directories( Server 
    PUBLIC ${PROJECT_SOURCE_DIR}/include
    )


#######################
## CLIENT BUILD INFO ##
#######################
add_executable(Client client.cpp)

target_include_directories( Client 
    PUBLIC ${PROJECT_SOURCE_DIR}/include
    )
