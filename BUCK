load('//:buckaroo_macros.bzl', 'buckaroo_deps')
load('//:subdir_glob.bzl', 'subdir_glob')

prebuilt_cxx_library(
  name = 'spectra',
  header_only = True,
  header_namespace = '',
  exported_headers = subdir_glob([
    ('include', '**/*.h'),
  ]),
  licenses = [
    'LICENSE',
  ],
  deps = buckaroo_deps(),
  visibility = [
    'PUBLIC',
  ],
)
