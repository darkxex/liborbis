# liborbis
 Libraries and samples for PlayStation 4 
 
 ## Requirements
 This repo requires to have properly the ps4toolchain and the ps4sdk installed.
 Additionally remember to have the bash environment variables declared, you can use:
 
```
cd /usr/local/orbisdev
 . ./orbisdev.sh
 ```

## Compile & Install
The compile process is quite simple, just do
```
cd /home/ps4dev/liborbis && cd libdebugnet && \
                                make && \
                                make install && \
                                cd .. && \
                                cd libelfloader && \
                                make && \
                                make install && \
                                cd .. && \
                                cd libps4link && \
                                make && \
                                make install && \
                                cd .. && \
                                cd liborbisPad && \
                                make && \
                                make install && \
                                cd .. && \
                                cd liborbisAudio && \
                                make && \
                                make install && \
                                cd .. && \
                                cd liborbisFile && \
                                make && \
                                make install && \
                                cd .. && \
                                cd libmod && \
                                make && \
                                make install && \
                                cd .. && \
                                cd portlibs && \
                                cd libz && \
                                make && \
                                make install && \
                                cd .. && \
                                cd libpng && \
                                make && \
                                make install && \
                                cd .. && \
                                cd .. && \
                                cd liborbis2d && \
                                make && \
                                make install && \
                                cd .. && \
                                cd liborbisFileBrowser && \
                                make && \
                                make install && \
                                cd .. && \
                                cd liborbisGl && \
                                make && \
                                make install && \
                                cd .. && \
                                cd liborbisXbmFont && \
                                make && \
                                make install && \
                                cd .. && \
                                cd liborbisKeyboard && \
                                make && \
                                make install
```

## Examples
The repo also contains a `samples` folder with several examples. If you wanna compile them just do:
```
cd samples && make clean all
```

## ENJOY

