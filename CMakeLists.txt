cmake_minimum_required(VERSION 3.19)
project(AccountManager
        VERSION 0.0.1
        DESCRIPTION "VPN server account manager"
        LANGUAGES CXX)

add_executable(AccountManager src/main.cpp)
target_compile_features(AccountManager PRIVATE cxx_std_20)
