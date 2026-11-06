## apple_macho_show

execute claude (arm64), 21 load commands, 4 libraries, 0 run paths, 844 imports, 1 exports, code-signed.

- Evidence: `ev_07f409b7d68f1a50728ae849387ccb7b952c145a6b5746a081cb8ba220190e4c`
- Confidence: observed
- Limitations:
  - Read from the file only; nothing was loaded or run.

```json
{
  "build_versions": [
    {
      "minos": "13.0.0",
      "platform": "macos",
      "sdk": "26.5.0",
      "tools": [
        "lld 23.1.2"
      ]
    }
  ],
  "code_signature": {
    "offset": 250034080,
    "size": 507760
  },
  "dyld_environment": [],
  "encryption": null,
  "entry_offset": 18110960,
  "exports": [
    {
      "addr": "0x100000000",
      "name": "__mh_execute_header"
    }
  ],
  "exports_total": 1,
  "header": {
    "arch": "arm64",
    "big_endian": false,
    "cpusubtype": 0,
    "cputype": 16777228,
    "filetype": 2,
    "filetype_name": "execute",
    "flag_names": [
      "NOUNDEFS",
      "DYLDLINK",
      "TWOLEVEL",
      "BINDS_TO_WEAK",
      "PIE",
      "HAS_TLV_DESCRIPTORS"
    ],
    "flags": 10551429,
    "is64": true,
    "ncmds": 21,
    "sizeofcmds": 2784
  },
  "imports": [
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "__DefaultRuneLocale",
      "slot": "0x10460c088"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "__Unwind_Resume",
      "slot": "0x10460c000"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNKSt13runtime_error4whatEv",
      "slot": "0x10460c040"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNKSt3__16locale9use_facetERNS0_2idE",
      "slot": "0x10460c160"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNKSt3__18ios_base6getlocEv",
      "slot": "0x10460c170"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt11logic_errorC2EPKc",
      "slot": "0x10460c118"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt12length_errorD1Ev",
      "slot": "0x10460c100"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt12out_of_rangeD1Ev",
      "slot": "0x10460c120"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt13runtime_errorC2ERKNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEE",
      "slot": "0x10460c048"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt13runtime_errorC2ERKS_",
      "slot": "0x10460c020"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt13runtime_errorD2Ev",
      "slot": "0x10460c008"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt20bad_array_new_lengthC1Ev",
      "slot": "0x10460c0f0"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt20bad_array_new_lengthD1Ev",
      "slot": "0x10460c0e0"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEaSERKS5_",
      "slot": "0x10460c090"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__113basic_ostreamIcNS_11char_traitsIcEEE6sentryC1ERS3_",
      "slot": "0x10460c178"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__113basic_ostreamIcNS_11char_traitsIcEEE6sentryD1Ev",
      "slot": "0x10460c148"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__14cerrE",
      "slot": "0x10460c030"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__15ctypeIcE2idE",
      "slot": "0x10460c168"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__16localeD1Ev",
      "slot": "0x10460c150"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__18ios_base33__set_badbit_and_consider_rethrowEv",
      "slot": "0x10460c140"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__18ios_base5clearEj",
      "slot": "0x10460c158"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZSt9terminatev",
      "slot": "0x10460c0d0"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZTISt12length_error",
      "slot": "0x10460c108"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZTISt12out_of_range",
      "slot": "0x10460c128"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZTISt13runtime_error",
      "slot": "0x10460c3d8"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZTISt20bad_array_new_length",
      "slot": "0x10460c0e8"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZTIi",
      "slot": "0x10460c050"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZTVSt12length_error",
      "slot": "0x10460c110"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZTVSt12out_of_range",
      "slot": "0x10460c130"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZdaPv",
      "slot": "0x10460c0a8"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZdlPv",
      "slot": "0x10460c010"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__Znam",
      "slot": "0x10460c0a0"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__Znwm",
      "slot": "0x10460c068"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "___cxa_allocate_exception",
      "slot": "0x10460c028"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "___cxa_begin_catch",
      "slot": "0x10460c0d8"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "___cxa_end_catch",
      "slot": "0x10460c138"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "___cxa_free_exception",
      "slot": "0x10460c0f8"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "___cxa_throw",
      "slot": "0x10460c018"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "___gxx_personality_v0",
      "slot": "0x10460da68"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "___maskrune",
      "slot": "0x10460c080"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "___stack_chk_fail",
      "slot": "0x10460c058"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "___stack_chk_guard",
      "slot": "0x10460c070"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_bzero",
      "slot": "0x10460c0b0"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_gettimeofday",
      "slot": "0x10460c060"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_memchr",
      "slot": "0x10460c098"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_memcmp",
      "slot": "0x10460c0c8"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_memcpy",
      "slot": "0x10460c0c0"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_memmove",
      "slot": "0x10460c078"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_memset",
      "slot": "0x10460c0b8"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_strlen",
      "slot": "0x10460c038"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__113basic_istreamIcNS_11char_traitsIcEEE3getEv",
      "slot": "0x10460c1c8"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__113basic_istreamIcNS_11char_traitsIcEEE4readEPcl",
      "slot": "0x10460c1b0"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt9bad_allocC1Ev",
      "slot": "0x10460c198"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt9bad_allocD1Ev",
      "slot": "0x10460c188"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZTISt9bad_alloc",
      "slot": "0x10460c190"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "___error",
      "slot": "0x10460c1c0"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_clearerr",
      "slot": "0x10460c1b8"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_free",
      "slot": "0x10460c180"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_posix_memalign",
      "slot": "0x10460c1a8"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_realloc",
      "slot": "0x10460c1a0"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNKSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE2atEm",
      "slot": "0x10460c230"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE2atEm",
      "slot": "0x10460c210"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE6appendEPKc",
      "slot": "0x10460c1e0"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE6appendEPKcm",
      "slot": "0x10460c1d8"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE6appendERKS5_mm",
      "slot": "0x10460c1f8"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE6assignEPKc",
      "slot": "0x10460c208"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE6assignEPKcm",
      "slot": "0x10460c218"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE6insertEmPKc",
      "slot": "0x10460c220"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE6resizeEmc",
      "slot": "0x10460c228"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE9push_backEc",
      "slot": "0x10460c1d0"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_strchr",
      "slot": "0x10460c1e8"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_strncmp",
      "slot": "0x10460c200"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_strtoul",
      "slot": "0x10460c1f0"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_bsearch",
      "slot": "0x10460c238"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "___cxa_atexit",
      "slot": "0x10460c248"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_strcmp",
      "slot": "0x10460c240"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "___darwin_check_fd_set_overflow",
      "slot": "0x10460c258"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_feof",
      "slot": "0x10460c278"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_ferror",
      "slot": "0x10460c268"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_fileno",
      "slot": "0x10460c270"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_fread",
      "slot": "0x10460c250"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_select",
      "slot": "0x10460c260"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE6appendEmc",
      "slot": "0x10460c280"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_snprintf",
      "slot": "0x10460c288"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_strrchr",
      "slot": "0x10460c290"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "___stderrp",
      "slot": "0x10460c5c0"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_fopen",
      "slot": "0x10460c310"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_fprintf",
      "slot": "0x10460c2d8"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_localtime_r",
      "slot": "0x10460c680"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_memset_pattern16",
      "slot": "0x10460c298"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_close",
      "slot": "0x10460c538"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_lseek",
      "slot": "0x10460c2a8"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_open",
      "slot": "0x10460c308"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_read",
      "slot": "0x10460c2a0"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_write",
      "slot": "0x10460c378"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_malloc",
      "slot": "0x10460c2b0"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_mktime",
      "slot": "0x10460c2b8"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_sysctlbyname",
      "slot": "0x10460c740"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNKSt3__115basic_stringbufIcNS_11char_traitsIcEENS_9allocatorIcEEE3strEv",
      "slot": "0x10460c448"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt13runtime_errorC1ERKNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEE",
      "slot": "0x10460c3e0"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt13runtime_errorD1Ev",
      "slot": "0x10460c3d0"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt16invalid_argumentD1Ev",
      "slot": "0x10460c510"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__111this_thread9sleep_forERKNS_6chrono8durationIxNS_5ratioILl1ELl1000000000EEEEE",
      "slot": "0x10460c340"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE5eraseEmm",
      "slot": "0x10460c3b0"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE6insertEmPKcm",
      "slot": "0x10460c3f8"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEED1Ev",
      "slot": "0x10460c5c8"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__113basic_istreamIcNS_11char_traitsIcEEED1Ev",
      "slot": "0x10460c490"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__113basic_ostreamIcNS_11char_traitsIcEEE3putEc",
      "slot": "0x10460c410"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__113basic_ostreamIcNS_11char_traitsIcEEE5flushEv",
      "slot": "0x10460c408"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__113basic_ostreamIcNS_11char_traitsIcEEElsEm",
      "slot": "0x10460c450"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__114basic_iostreamIcNS_11char_traitsIcEEED2Ev",
      "slot": "0x10460c420"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__115__thread_structC1Ev",
      "slot": "0x10460c578"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__115__thread_structD1Ev",
      "slot": "0x10460c580"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__116generic_categoryEv",
      "slot": "0x10460c320"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__118condition_variable10notify_allEv",
      "slot": "0x10460c488"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__118condition_variable10notify_oneEv",
      "slot": "0x10460c330"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__118condition_variable4waitERNS_11unique_lockINS_5mutexEEE",
      "slot": "0x10460c4e0"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__118condition_variableD1Ev",
      "slot": "0x10460c4f8"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__119__thread_local_dataEv",
      "slot": "0x10460c590"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__120__throw_system_errorEiPKc",
      "slot": "0x10460c3c8"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__14coutE",
      "slot": "0x10460c440"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__15mutex4lockEv",
      "slot": "0x10460c338"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__15mutex6unlockEv",
      "slot": "0x10460c328"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__15mutex8try_lockEv",
      "slot": "0x10460c3f0"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__15mutexD1Ev",
      "slot": "0x10460c4f0"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__16localeC1Ev",
      "slot": "0x10460c498"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__16thread4joinEv",
      "slot": "0x10460c508"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__16threadD1Ev",
      "slot": "0x10460c500"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__18ios_base4initEPv",
      "slot": "0x10460c4a0"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__19basic_iosIcNS_11char_traitsIcEEED2Ev",
      "slot": "0x10460c418"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__19to_stringEi",
      "slot": "0x10460c520"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt9exceptionD2Ev",
      "slot": "0x10460c598"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZTINSt3__112system_errorE",
      "slot": "0x10460c5a0"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZTISt16invalid_argument",
      "slot": "0x10460c518"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZTISt9exception",
      "slot": "0x10460c5a8"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZTTNSt3__118basic_stringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEEE",
      "slot": "0x10460c438"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZTVNSt3__113basic_istreamIcNS_11char_traitsIcEEEE",
      "slot": "0x10460c4a8"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZTVNSt3__115basic_streambufIcNS_11char_traitsIcEEEE",
      "slot": "0x10460c428"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZTVNSt3__115basic_stringbufIcNS_11char_traitsIcEENS_9allocatorIcEEEE",
      "slot": "0x10460c430"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZTVNSt3__118basic_stringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEEE",
      "slot": "0x10460c4d8"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZTVSt16invalid_argument",
      "slot": "0x10460c528"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "___cxa_rethrow",
      "slot": "0x10460c318"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "___dynamic_cast",
      "slot": "0x10460c4c8"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "___stdinp",
      "slot": "0x10460c2f0"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "___stdoutp",
      "slot": "0x10460c2e8"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "___toupper",
      "slot": "0x10460c3c0"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_closedir",
      "slot": "0x10460c4b0"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_dup2",
      "slot": "0x10460c540"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_execvp",
      "slot": "0x10460c530"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_exit",
      "slot": "0x10460c2d0"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_fclose",
      "slot": "0x10460c388"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_fcntl",
      "slot": "0x10460c300"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_fdopen",
      "slot": "0x10460c2f8"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_fflush",
      "slot": "0x10460c4e8"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_fork",
      "slot": "0x10460c548"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_fputc",
      "slot": "0x10460c3e8"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_fseek",
      "slot": "0x10460c4d0"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_fstat",
      "slot": "0x10460c460"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_fwrite",
      "slot": "0x10460c468"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_getcwd",
      "slot": "0x10460c480"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_getenv",
      "slot": "0x10460c2c8"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_gethostname",
      "slot": "0x10460c478"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_getpid",
      "slot": "0x10460c368"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_getuid",
      "slot": "0x10460c458"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_isatty",
      "slot": "0x10460c398"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_kill",
      "slot": "0x10460c360"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_lstat",
      "slot": "0x10460c3a8"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_opendir",
      "slot": "0x10460c4c0"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_pclose",
      "slot": "0x10460c370"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_pipe",
      "slot": "0x10460c558"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_popen",
      "slot": "0x10460c2c0"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_pthread_create",
      "slot": "0x10460c570"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_pthread_set_qos_class_self_np",
      "slot": "0x10460c350"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_pthread_setspecific",
      "slot": "0x10460c588"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_readdir",
      "slot": "0x10460c4b8"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_rename",
      "slot": "0x10460c470"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_rewind",
      "slot": "0x10460c550"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_setpriority",
      "slot": "0x10460c348"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_signal",
      "slot": "0x10460c358"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_stat",
      "slot": "0x10460c3a0"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_statvfs",
      "slot": "0x10460c390"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_strdup",
      "slot": "0x10460c400"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_strerror",
      "slot": "0x10460c2e0"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_strncasecmp",
      "slot": "0x10460c560"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_strnlen",
      "slot": "0x10460c568"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_strstr",
      "slot": "0x10460c380"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_strtoull",
      "slot": "0x10460c3b8"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_strtol",
      "slot": "0x10460c5d0"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNKSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE4copyEPcmm",
      "slot": "0x10460c5e0"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNKSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE4findEcm",
      "slot": "0x10460c608"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNKSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE7compareEmmPKc",
      "slot": "0x10460c5f0"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__19to_stringEm",
      "slot": "0x10460c5e8"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_chdir",
      "slot": "0x10460c5f8"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_raise",
      "slot": "0x10460c5d8"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_system",
      "slot": "0x10460c600"
    },
    {
      "library": "/usr/lib/libc++.1.dylib",
      "name": "__ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE7replaceEmmPKc",
      "slot": "0x10460c610"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_fputs",
      "slot": "0x10460c618"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_cfmakeraw",
      "slot": "0x10460c628"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_tcgetattr",
      "slot": "0x10460c630"
    },
    {
      "library": "/usr/lib/libSystem.B.dylib",
      "name": "_tcsetattr",
      "slot": "0x10460c620"
    }
  ],
  "imports_total": 844,
  "install_name": null,
  "libraries": [
    {
      "compatibility_version": "1.0.0",
      "current_version": "78.1.0",
      "kind": "load",
      "name": "/usr/lib/libicucore.A.dylib"
    },
    {
      "compatibility_version": "1.0.0",
      "current_version": "1.0.0",
      "kind": "load",
      "name": "/usr/lib/libresolv.9.dylib"
    },
    {
      "compatibility_version": "1.0.0",
      "current_version": "2100.43.0",
      "kind": "load",
      "name": "/usr/lib/libc++.1.dylib"
    },
    {
      "compatibility_version": "1.0.0",
      "current_version": "1356.0.0",
      "kind": "load",
      "name": "/usr/lib/libSystem.B.dylib"
    }
  ],
  "load_commands": [
    {
      "cmd": "LC_SEGMENT_64",
      "detail": {
        "fileoff": 0,
        "filesize": 0,
        "initprot": "---",
        "sections": [],
        "segname": "__PAGEZERO",
        "vmaddr": "0x0",
        "vmsize": 4294967296
      },
      "index": 0,
      "offset": 32,
      "size": 72
    },
    {
      "cmd": "LC_SEGMENT_64",
      "detail": {
        "fileoff": 0,
        "filesize": 73449472,
        "initprot": "r-x",
        "sections": [
          "__text",
          "__jsc_int",
          "__stubs",
          "__init_offsets",
          "__gcc_except_tab",
          "__const",
          "__literals",
          "__cstring",
          "__bun_builtins",
          "__ustring",
          "__unwind_info",
          "__eh_frame"
        ],
        "segname": "__TEXT",
        "vmaddr": "0x100000000",
        "vmsize": 73449472
      },
      "index": 1,
      "offset": 104,
      "size": 1032
    },
    {
      "cmd": "LC_SEGMENT_64",
      "detail": {
        "fileoff": 73449472,
        "filesize": 1523712,
        "initprot": "rw-",
        "sections": [
          "__got",
          "__const"
        ],
        "segname": "__DATA_CONST",
        "vmaddr": "0x10460c000",
        "vmsize": 1523712
      },
      "index": 2,
      "offset": 1136,
      "size": 232
    },
    {
      "cmd": "LC_SEGMENT_64",
      "detail": {
        "fileoff": 74973184,
        "filesize": 147456,
        "initprot": "rw-",
        "sections": [
          "__data",
          "__thread_vars",
          "__wtf_config",
          "__jsc_opcodes",
          "__thread_data",
          "__thread_bss",
          "__bss",
          "__common"
        ],
        "segname": "__DATA",
        "vmaddr": "0x104780000",
        "vmsize": 2064384
      },
      "index": 3,
      "offset": 1368,
      "size": 712
    },
    {
      "cmd": "LC_SEGMENT_64",
      "detail": {
        "fileoff": 75120640,
        "filesize": 174702592,
        "initprot": "rw-",
        "sections": [
          "__bun"
        ],
        "segname": "__BUN",
        "vmaddr": "0x104978000",
        "vmsize": 174702592
      },
      "index": 4,
      "offset": 2080,
      "size": 152
    },
    {
      "cmd": "LC_SEGMENT_64",
      "detail": {
        "fileoff": 249823232,
        "filesize": 718608,
        "initprot": "r--",
        "sections": [],
        "segname": "__LINKEDIT",
        "vmaddr": "0x10f014000",
        "vmsize": 720896
      },
      "index": 5,
      "offset": 2232,
      "size": 72
    },
    {
      "cmd": "LC_DYLD_CHAINED_FIXUPS",
      "detail": {
        "dataoff": 249823232,
        "datasize": 20200
      },
      "index": 6,
      "offset": 2304,
      "size": 16
    },
    {
      "cmd": "LC_DYLD_EXPORTS_TRIE",
      "detail": {
        "dataoff": 249843432,
        "datasize": 18840
      },
      "index": 7,
      "offset": 2320,
      "size": 16
    },
    {
      "cmd": "LC_SYMTAB",
      "detail": {
        "nsyms": 845,
        "stroff": 250018544,
        "strsize": 15528,
        "symoff": 249998432
      },
      "index": 8,
      "offset": 2336,
      "size": 24
    },
    {
      "cmd": "LC_DYSYMTAB",
      "detail": null,
      "index": 9,
      "offset": 2360,
      "size": 80
    },
    {
      "cmd": "LC_LOAD_DYLINKER",
      "detail": {
        "name": "/usr/lib/dyld"
      },
      "index": 10,
      "offset": 2440,
      "size": 32
    },
    {
      "cmd": "LC_UUID",
      "detail": {
        "uuid": "4C4C4422-5555-3144-A114-05A85A469CA7"
      },
      "index": 11,
      "offset": 2472,
      "size": 24
    },
    {
      "cmd": "LC_BUILD_VERSION",
      "detail": {
        "minos": "13.0.0",
        "platform": "macos",
        "sdk": "26.5.0",
        "tools": [
          "lld 23.1.2"
        ]
      },
      "index": 12,
      "offset": 2496,
      "size": 32
    },
    {
      "cmd": "LC_MAIN",
      "detail": {
        "entryoff": 18110960,
        "stacksize": 18874368
      },
      "index": 13,
      "offset": 2528,
      "size": 24
    },
    {
      "cmd": "LC_LOAD_DYLIB",
      "detail": {
        "compatibility_version": "1.0.0",
        "current_version": "78.1.0",
        "name": "/usr/lib/libicucore.A.dylib"
      },
      "index": 14,
      "offset": 2552,
      "size": 56
    },
    {
      "cmd": "LC_LOAD_DYLIB",
      "detail": {
        "compatibility_version": "1.0.0",
        "current_version": "1.0.0",
        "name": "/usr/lib/libresolv.9.dylib"
      },
      "index": 15,
      "offset": 2608,
      "size": 56
    },
    {
      "cmd": "LC_LOAD_DYLIB",
      "detail": {
        "compatibility_version": "1.0.0",
        "current_version": "2100.43.0",
        "name": "/usr/lib/libc++.1.dylib"
      },
      "index": 16,
      "offset": 2664,
      "size": 48
    },
    {
      "cmd": "LC_LOAD_DYLIB",
      "detail": {
        "compatibility_version": "1.0.0",
        "current_version": "1356.0.0",
        "name": "/usr/lib/libSystem.B.dylib"
      },
      "index": 17,
      "offset": 2712,
      "size": 56
    },
    {
      "cmd": "LC_FUNCTION_STARTS",
      "detail": {
        "dataoff": 249862272,
        "datasize": 136160
      },
      "index": 18,
      "offset": 2768,
      "size": 16
    },
    {
      "cmd": "LC_DATA_IN_CODE",
      "detail": {
        "dataoff": 249998432,
        "datasize": 0
      },
      "index": 19,
      "offset": 2784,
      "size": 16
    },
    {
      "cmd": "LC_CODE_SIGNATURE",
      "detail": {
        "dataoff": 250034080,
        "datasize": 507760
      },
      "index": 20,
      "offset": 2800,
      "size": 16
    }
  ],
  "mitigations": {
    "canary": true,
    "code_signature": true,
    "control_flow_guard": null,
    "encrypted": null,
    "fortify": null,
    "high_entropy_va": null,
    "no_seh": null,
    "nx": true,
    "pie": true,
    "relro": null,
    "stripped": true
  },
  "path": "/Users/user/1104/binaries/claude-code-2.1.301-darwin-arm64/claude",
  "rpaths": [],
  "segments": [
    {
      "fileoff": 0,
      "filesize": 0,
      "initprot": "---",
      "sections": [],
      "segname": "__PAGEZERO",
      "vmaddr": "0x0",
      "vmsize": 4294967296
    },
    {
      "fileoff": 0,
      "filesize": 73449472,
      "initprot": "r-x",
      "sections": [
        "__text",
        "__jsc_int",
        "__stubs",
        "__init_offsets",
        "__gcc_except_tab",
        "__const",
        "__literals",
        "__cstring",
        "__bun_builtins",
        "__ustring",
        "__unwind_info",
        "__eh_frame"
      ],
      "segname": "__TEXT",
      "vmaddr": "0x100000000",
      "vmsize": 73449472
    },
    {
      "fileoff": 73449472,
      "filesize": 1523712,
      "initprot": "rw-",
      "sections": [
        "__got",
        "__const"
      ],
      "segname": "__DATA_CONST",
      "vmaddr": "0x10460c000",
      "vmsize": 1523712
    },
    {
      "fileoff": 74973184,
      "filesize": 147456,
      "initprot": "rw-",
      "sections": [
        "__data",
        "__thread_vars",
        "__wtf_config",
        "__jsc_opcodes",
        "__thread_data",
        "__thread_bss",
        "__bss",
        "__common"
      ],
      "segname": "__DATA",
      "vmaddr": "0x104780000",
      "vmsize": 2064384
    },
    {
      "fileoff": 75120640,
      "filesize": 174702592,
      "initprot": "rw-",
      "sections": [
        "__bun"
      ],
      "segname": "__BUN",
      "vmaddr": "0x104978000",
      "vmsize": 174702592
    },
    {
      "fileoff": 249823232,
      "filesize": 718608,
      "initprot": "r--",
      "sections": [],
      "segname": "__LINKEDIT",
      "vmaddr": "0x10f014000",
      "vmsize": 720896
    }
  ],
  "selected": {
    "align": null,
    "arch": "arm64",
    "cpusubtype": 0,
    "cputype": 16777228,
    "offset": 0,
    "size": 250541840,
    "universal": false
  },
  "slices": [
    {
      "align": null,
      "arch": "arm64",
      "cpusubtype": 0,
      "cputype": 16777228,
      "offset": 0,
      "size": 250541840,
      "universal": false
    }
  ],
  "source_version": null,
  "uuid": "4C4C4422-5555-3144-A114-05A85A469CA7"
}
```

