cmake_minimum_required(VERSION 3.5)

add_executable(channel-buffering channel-buffering.c)
target_link_libraries(channel-buffering PRIVATE neco)

add_executable(channels channels.c)
target_link_libraries(channels PRIVATE neco)

add_executable(channels2 channels2.c)
target_link_libraries(channels2 PRIVATE neco)

add_executable(coroutines coroutines.c)
target_link_libraries(coroutines PRIVATE neco)

add_executable(echo-client echo-client.c)
target_link_libraries(echo-client PRIVATE neco)

add_executable(echo-server echo-client.c)
target_link_libraries(echo-server PRIVATE neco)

add_executable(select select.c)
target_link_libraries(select PRIVATE neco)

add_executable(signals select.c)
target_link_libraries(signals PRIVATE neco)

