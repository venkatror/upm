if (MRAA_IIO_FOUND)
    set (libname "l3gd20")
    set (libdescription "Tri-axis Digital Gyroscope")
    set (module_src ${libname}.cxx)
    set (module_hpp ${libname}.hpp)
    upm_module_init(mraa)
endif (MRAA_IIO_FOUND)
