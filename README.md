# autotools-example-1

This simple shows how to use autotools (autoconf, automake, libtools).

1. mkdir src test build m4
2. Create hello.c in src directory and Makefile.am
3. Type #autoscan to automatically create configure file and remove file autoscan.log, then change the filename of configure.scan to configure.ac
4. Open configure.ac file, change AC_INIT, target name, version, bug
5. After modify configure.ac file, use autoreconf -vi
6.It will report error automake: You are advised to start using 'subdir-objects' option throughout your, Add this line to Makefile.am “AUTOMAKE_OPTIONS = subdir-objects”
7. Then go to build directory type ../configure to generate makefile in build directory.
8. After generating the hello bin file. 
