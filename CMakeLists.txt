set(includedirs .)
set(srcs )
set(srcs_dir .)
set(priv_includes)
set(requires arduino)
set(priv_requires)

idf_component_register(INCLUDE_DIRS ${includedirs} PRIV_INCLUDE_DIRS ${priv_includes} SRCS ${srcs} SRC_DIRS ${src_dirs} REQUIRES ${requires} PRIV_REQUIRES ${priv_requires})
