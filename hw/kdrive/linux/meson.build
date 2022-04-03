srcs_linux = [
    'linux.c',
]


if build_evdev
    srcs_linux += 'evdev.c'
endif

linux = static_library('linux',
    srcs_linux,
    include_directories: [
        inc,
        include_directories('../src')
    ],
    dependencies: common_dep,
)
