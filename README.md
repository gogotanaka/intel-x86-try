# How to run
OSX

    nasm -o main.tmp -f macho main.s && ld -arch i386 -macosx_version_min 10.6 -no_pie -e _main -o main.o main.tmp

    ./hello.o
