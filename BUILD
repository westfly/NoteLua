# generated by genlibbuild

cc_library(
    name = 'llua',
    srcs = [
        'src/lapi.c',
        'src/lauxlib.c',
        'src/lbaselib.c',
        'src/lbitlib.c',
        'src/lcode.c',
        'src/lcorolib.c',
        'src/lctype.c',
        'src/ldblib.c',
        'src/ldebug.c',
        'src/ldo.c',
        'src/ldump.c',
        'src/lfunc.c',
        'src/lgc.c',
        'src/linit.c',
        'src/liolib.c',
        'src/llex.c',
        'src/lmathlib.c',
        'src/lmem.c',
        'src/loadlib.c',
        'src/lobject.c',
        'src/lopcodes.c',
        'src/loslib.c',
        'src/lparser.c',
        'src/lstate.c',
        'src/lstring.c',
        'src/lstrlib.c',
        'src/ltable.c',
        'src/ltablib.c',
        'src/ltm.c',
        'src/lundump.c',
        'src/lutf8lib.c',
        'src/lvm.c',
        'src/lzio.c',
    ],
    deps = [
        '#dl',
        '#readline'
    ],
    defs = [
        'LUA_COMPAT_5_2',
        'LUA_USE_LINUX'
    ]
)
cc_binary(
    name = 'luac',
    srcs = [
        'src/lua.c',
    ],
    deps = [
        ':llua'
    ]
)
cc_binary(
    name = 'lua',
    srcs = [
        'src/luac.c',
    ],
    deps = [
        ':llua'
    ]
)
