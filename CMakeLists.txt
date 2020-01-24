cmake_minimum_required(VERSION 3.15)
project(MileStone2)

set(CMAKE_CXX_STANDARD 11)

add_executable(MileStone2 main.cpp Astar.h BestFirstSearch.cpp BestFirstSearch.h BfsSearch.h Searcheable.h CacheManager.cpp CacheManager.h
        ClientHandler.cpp ClientHandler.h MyClientHandler.cpp MyClientHandler.h Dfs.cpp Dfs.h
        FileCacheManager.cpp FileCacheManager.h Matrix.h Searcher.h Solver.cpp Solver.h State.h OA.cpp OA.h
        MySerialServer.cpp MySerialServer.h Server.cpp Server.h)