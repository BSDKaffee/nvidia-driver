NVIDIA_ROOT=	${.CURDIR}/../..

.if !defined(LOCALBASE)
LOCALBASE=	/usr/local
.endif

LIB=		   nvidia-gtk3
SHLIB_VERSION=	535.86.05
SHLIB_NAME=    lib${LIB}.so.${SHLIB_VERSION}
SHLIB_NO_LINK= 1
LIBDIR=		   ${LOCALBASE}/lib

.include <${NVIDIA_ROOT}/mk/nvidia.lib.mk>
