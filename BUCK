prebuilt_cxx_library(
  name = 'iterator', 
  header_namespace = 'boost', 
  header_only = True, 
  exported_headers = subdir_glob([
    ('include/boost', '**/*.hpp'), 
  ]), 
  deps = [
    'buckaroo.github.buckaroo-pm.boost-static_assert//:static-assert', 
  ], 
  visibility = [
    'PUBLIC', 
  ], 
)
