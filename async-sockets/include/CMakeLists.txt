cmake_minimum_required(VERSION 3.23.2)
add_library(tcp_client 
basesocket.hpp
tcpsocket.hpp
tcpserver.hpp)
target_link_libraries(tcp_client PUBLIC lb_8k6p)