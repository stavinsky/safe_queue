add_library(safequeue STATIC safequeue.cpp )
target_compile_features(safequeue PRIVATE cxx_range_for)
