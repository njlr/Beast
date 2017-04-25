include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'beast',
  header_only = True,
  header_namespace = 'beast',
  exported_headers = subdir_glob([
    ('include/beast', '**/*.hpp'),
    ('include/beast', '**/*.ipp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
