catch2_dep = dependency('catch2', fallback: ['catch2'])

simple_test = executable('blobify-test', 'simple_test.cpp',
                         dependencies: [blobify_dep, catch2_dep])

test('simple_test', simple_test)
