include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'boost-intrusive',
  header_only = True,
  header_namespace = 'boost/intrusive',
  exported_headers = subdir_glob([
    ('include/boost/intrusive', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
