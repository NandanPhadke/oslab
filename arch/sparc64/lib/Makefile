# $Id: Makefile,v 1.25 2000/12/14 22:57:25 davem Exp $
# Makefile for Sparc64 library files..
#

EXTRA_AFLAGS := -ansi
EXTRA_CFLAGS := -Werror

lib-y := PeeCeeI.o copy_page.o clear_page.o strlen.o strncmp.o \
	 memscan.o strncpy_from_user.o strlen_user.o memcmp.o checksum.o \
	 VISbzero.o VISmemset.o VIScsum.o VIScsumcopy.o \
	 VIScsumcopyusr.o VISsave.o atomic.o bitops.o \
	 U1memcpy.o U1copy_from_user.o U1copy_to_user.o \
	 U3memcpy.o U3copy_from_user.o U3copy_to_user.o U3patch.o \
	 copy_in_user.o user_fixup.o memmove.o \
	 mcount.o ipcsum.o rwsem.o xor.o find_bit.o delay.o iomap.o

lib-$(CONFIG_DEBUG_SPINLOCK) += debuglocks.o
lib-$(CONFIG_HAVE_DEC_LOCK) += dec_and_lock.o
