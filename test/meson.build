sources = [
    'src/gtest_main.cpp',
    'src/test.cpp'
]

# dependencies
gtest = subproject('gtest')
gtest_dep = gtest.get_variable('gtest_dep')
#gtest_main_dep = dependency('gtest', main : true, required : true)
gmock_dep = dependency('gmock', main : true, required : true)
thread_dep = dependency('threads')

executable(
    'some_test', 
    sources,
    dependencies : [
        gtest_dep, 
#       gtest_main_dep, 
        gmock_dep, 
        thread_dep]
)
