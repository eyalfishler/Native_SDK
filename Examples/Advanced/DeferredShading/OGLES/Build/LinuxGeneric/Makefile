#
# File			Makefile
# Title			Example makefile
#
# Copyright		Copyright (C) Imagination Technologies Limited.
#

.PHONY: clean

SDKDIR  = ../../../../../..
OUTNAME = OGLESDeferredShading
DEPENDS =  PVRCore PVRAssets PVREgl PVRNativeGles PVRGles PVRShell PVRUIRenderer
LIBRARIES =  PVRUIRenderer PVRShell PVRGles PVRNativeGles PVREgl PVRAssets PVRCore
LIBPATHS =  ../../../../../../Framework/Bin/Linux_$(PLAT_SUFFIX)/$(DEBUG_RELEASE)$(WS)

OBJECTS +=	\
           OGLES/OGLESDeferredShading.o

RESOURCES += \
           effect_MRT.pfx\
           effect_PLS.pfx\

COMMON_RESOURCES += \
           Marble.pvr\
           MarbleNormalMap.pvr\
           Table.pvr\
           scene.pod\
           pointlight.pod\


include $(SDKDIR)/Builds/Linux/make_example.mak
