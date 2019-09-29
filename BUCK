prebuilt_cxx_library(
  name = 'glib',
  soname = 'libglib.so',
  shared_lib = 'lib/libglib-2.0.so',
  header_namespace = '',
  exported_headers = subdir_glob([
    ('lib/glib-2.0/include','**/*.h'),
    ('include/glib-2.0','**/*.h'),
  ]),
  visibility = ['PUBLIC']
)
