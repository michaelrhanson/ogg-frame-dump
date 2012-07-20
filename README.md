ogg-frame-dump
==============

A simple command line tool to dump frames from an OGG Theora video.

Depends on libtheora and libogg.

I used tup for the build system; sorry if that's a pain for you.  You can just `gcc -ltheora -logg -o ogg-frame-dump main.c` if you like.

Usage right now is just
`ogg-frame-dump < my-movie.ogv`

An output_frames directory will be created and frames dumped into it in .ppm format.
