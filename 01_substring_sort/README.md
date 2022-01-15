# Instructions

## Install perf

    sudo apt install linux-tools-5.11.0-43-generic
    sudo apt install linux-cloud-tools-5.11.0-43-generic
    perf -v

## Install gperftools

    sudo apt-get update -y
    sudo apt-get install -y google-perftools

## Install clang++-11

    sudo apt install clang-11

## Compile and Execute

    clang++ -g -O3 -mavx2 -Wall -pedantic 01_substring_sort.c -o example && ./example