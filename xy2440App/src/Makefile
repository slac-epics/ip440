# Makefile.Host
TOP = ../..
include $(TOP)/configure/CONFIG

HTMLS += xycomIpac.html

DBD   += ip440.dbd
DBD   += Xy2440.dbd

# Source files (for depends target):
LIBSRCS += drvXy2440.c
LIBSRCS += devXy2440.c
#LIBSRCS += xipIo.c 

# Link everything into a library:
LIBRARY_IOC_Linux   = Xy2440 ip440
LIBRARY_IOC_vxWorks = Xy2440 ip440
LIBRARY_IOC_RTEMS   = Xy2440 ip440
Xy2440_LIBS += Ipac
ip440_LIBS += Ipac

include $(TOP)/configure/RULES
