# How to run
OSX
    nasm -o hello.tmp -f macho hello.s && ld -arch i386 -macosx_version_min 10.6 -no_pie -e _main -o hello.o hello.tmp

    ./hello.o
