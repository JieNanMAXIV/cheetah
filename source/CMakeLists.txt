
ADD_SUBDIRECTORY(libcheetah)

if(BUILD_CHEETAH_ANA_MOD)
ADD_SUBDIRECTORY(cheetah_ana_pkg)
endif(BUILD_CHEETAH_ANA_MOD)

if(BUILD_PSANA)
ADD_SUBDIRECTORY(psana)
endif(BUILD_PSANA)

if(BUILD_CHEETAH_MYANA)
ADD_SUBDIRECTORY(cheetah_myana)
endif(BUILD_CHEETAH_MYANA)

if(BUILD_CHEETAH_SACLA)
ADD_SUBDIRECTORY(cheetah-sacla)
endif(BUILD_CHEETAH_SACLA)
