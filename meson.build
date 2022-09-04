project(
    'meson_template', 
    'cpp',
    default_options : ['cpp_std=c++20'],
    version: '0.0.1'
)

sources = [
    'src/main.cpp'
]

executable(
    meson.project_name(), 
    sources
)

# unit tests
subdir('test')