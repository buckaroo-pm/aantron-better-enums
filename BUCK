prebuilt_cxx_library(
  name = 'better-enums',
  header_only = True,
  header_namespace = '',
  exported_headers = [
    'enum.h',
  ],
  visibility = [
    'PUBLIC',
  ],
)

cxx_binary(
  name = 'test',
  srcs = ['test/performance/4-declare_enums.cc'],
  deps = [':better-enums']
)
