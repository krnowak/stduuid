project('stduuid', ['cpp'],
        version: '1.2.2',
        default_options: ['cpp_std=c++17'])

stduuid_dep = declare_dependency(include_directories: include_directories('include'))

if meson.version().version_compare('>=0.54.0')
    meson.override_dependency('stduuid', stduuid_dep)
endif
