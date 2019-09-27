load('//:subdir_glob.bzl', 'subdir_glob')
load('//:buckaroo_macros.bzl', 'buckaroo_deps')

cxx_library(
  name = 'iterator',
  header_namespace = 'boost',
  exported_headers = subdir_glob([
    ('include/boost', '**/*.hpp'),
  ]),
  srcs = glob([
    "src/**/*.cpp",
  ]),
  deps = buckaroo_deps(),
  visibility = [
    'PUBLIC',
  ],
)
