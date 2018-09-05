# cmake_minimum_required(VERSION <specify CMake version here>)
project(lianti_master C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(lianti_master
        bedidx.c
        bgzf.c
        bgzf.h
        cnv.c
        count.c
        cv.c
        faidx.c
        faidx.h
        group.c
        hts.c
        hts.h
        kdq.h
        khash.h
        kseq.h
        ksort.h
        kstring.h
        kthread.c
        kvec.h
        ldup.c
        lorenz.c
        main.c
        pileup.c
        razf.c
        razf.h
        sam.c
        sam.h
        sv.c
        trim.c)
