cmake_minimum_required(VERSION 3.9)
project(db_generator)

set(CMAKE_CXX_STANDARD 11)

add_executable(db_generator
        custom_db.cc
        custom_db.h
        db_generator.cc
        dbintree.cc
        dbintree.h
        dlist.cc
        dlist.h
        ExtraList.cc
        ExtraList.h
        FilterList.cc
        FilterList.h
        FlagList.cc
        FlagList.h
        PortList.cc
        PortList.h
        PrefixList.cc
        PrefixList.h
        ProtList.cc
        ProtList.h
        random_db.cc
        random_db.h
        redundant_filter_check.cc
        redundant_filter_check.h
        sbintree.cc
        sbintree.h
        stdinc.h
        TupleBST.cc
        TupleBST.h)
