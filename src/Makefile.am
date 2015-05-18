lib_LTLIBRARIES = lib_openfd_locks.la
lib_openfd_locks_la_SOURCES = lib_openfd_lock.c lib_openfd_lock.h
lib_openfd_locks_la_LDFLAGS = -module
lib_openfd_locks_la_CPPFLAGS = -isystem /usr/include/asm-generic -isystem /user/include
#include_HEADERS = stdio.h types.h stat.h unistd.h fcntl.h pthread.h stdlib.h string.h errno.h
bin_PROGRAMS = hellotest
hellotest_SOURCES = test_lib.c
hellotest_LDADD = lib_openfd_locks.la
